Make Fabric Images
=======
version:x86_64-1.1.1-snapshot-ff5e861


#Fabric 源码

- `cd /home/vickywang/myCode/go/gopath/src/github.com/hyperledger`
- `git clone https://github.com/hyperledger/fabric.git`


- `cd /home/vickywang/myCode/go/gopath/src/golang.org/x`
- `git clone https://github.com/golang/tools.git`
- `git clone https://github.com/golang/lint.git`


- `go get github.com/kardianos/govendor`
- `go get github.com/golang/lint/golint`
- `go get golang.org/x/tools/cmd/goimports`
- `go get github.com/onsi/ginkgo/ginkgo`
- `go get github.com/axw/gocov/...`
- `go get github.com/client9/misspell/cmd/misspell`
- `go get github.com/AlekSi/gocov-xml`
- `go get github.com/golang/protobuf/protoc-gen-go`


- `cd /home/vickywang/myCode/go/gopath/src/github.com/hyperledger/fabric`

## Make Orderer

- `make orderer`

log

```
make: execvp: ./scripts/goListFiles.sh: Permission denied
make: Warning: File 'docker-env.mk' has modification time 48997 s in the future
build/bin/orderer
CGO_CFLAGS=" " GOBIN=/home/vickywang/myCode/go/gopath/src/github.com/hyperledger/fabric/build/bin go install -tags "experimental" -ldflags "-X github.com/hyperledger/fabric/common/metadata.Version=1.1.1-snapshot-ff5e861 -X github.com/hyperledger/fabric/common/metadata.BaseVersion=0.4.6 -X github.com/hyperledger/fabric/common/metadata.BaseDockerLabel=org.hyperledger.fabric -X github.com/hyperledger/fabric/common/metadata.DockerNamespace=hyperledger -X github.com/hyperledger/fabric/common/metadata.BaseDockerNamespace=hyperledger -X github.com/hyperledger/fabric/common/metadata.Experimental=true" github.com/hyperledger/fabric/orderer
Binary available as build/bin/orderer
make: warning:  Clock skew detected.  Your build may be incomplete.
```

文件位置
`build/bin/orderer`

## peer

在Fabric目录下
`mkdir -p build/docker/gotools/bin`
拷贝之前的gopath/bin 目录下的内容在此文件下

- `make peer`

log

```
Installing chaintool
curl -fL https://nexus.hyperledger.org/content/repositories/releases/org/hyperledger/fabric/hyperledger-fabric/chaintool-1.1.1/hyperledger-fabric-chaintool-1.1.1.jar > build/bin/chaintool
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 16.4M  100 16.4M    0     0   968k      0  0:00:17  0:00:17 --:--:-- 1346k
chmod +x build/bin/chaintool
Creating build/goshim.tar.bz2
mkdir -p build/image/ccenv/payload
cp build/docker/gotools/bin/protoc-gen-go build/bin/chaintool build/goshim.tar.bz2 build/image/ccenv/payload
Building docker ccenv-image
docker build  -t hyperledger/fabric-ccenv build/image/ccenv
Sending build context to Docker daemon  23.78MB
Step 1/5 : FROM hyperledger/fabric-baseimage:x86_64-0.4.6
 ---> dbe6787b5747
Step 2/5 : COPY payload/chaintool payload/protoc-gen-go /usr/local/bin/
 ---> 38e280ac34d3
Step 3/5 : ADD payload/goshim.tar.bz2 $GOPATH/src/
 ---> f2e2f8759842
Step 4/5 : RUN mkdir -p /chaincode/input /chaincode/output
 ---> Running in 79a0832fd125
Removing intermediate container 79a0832fd125
 ---> 5ea5fc22c986
Step 5/5 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in 0f3348ae9931
Removing intermediate container 0f3348ae9931
 ---> 701e56ae3024
Successfully built 701e56ae3024
Successfully tagged hyperledger/fabric-ccenv:latest
docker tag hyperledger/fabric-ccenv hyperledger/fabric-ccenv:x86_64-1.1.1-snapshot-ff5e861
Creating build/javashim.tar.bz2
Creating build/protos.tar.bz2
mkdir -p build/image/javaenv/payload
cp build/javashim.tar.bz2 build/protos.tar.bz2 settings.gradle build/image/javaenv/payload
Building docker javaenv-image
docker build  -t hyperledger/fabric-javaenv build/image/javaenv
Sending build context to Docker daemon  50.18kB
Step 1/15 : FROM hyperledger/fabric-baseimage:x86_64-0.4.6
 ---> dbe6787b5747
Step 2/15 : RUN curl -sSL https://services.gradle.org/distributions/gradle-2.12-bin.zip > /tmp/gradle-2.12-bin.zip
 ---> Running in b4c1e8f91c5a
Removing intermediate container b4c1e8f91c5a
 ---> 88d90ad55ee0
Step 3/15 : RUN unzip -qo /tmp/gradle-2.12-bin.zip -d /opt && rm /tmp/gradle-2.12-bin.zip
 ---> Running in ce8bf4d30676
Removing intermediate container ce8bf4d30676
 ---> 00130603c29b
Step 4/15 : RUN ln -s /opt/gradle-2.12/bin/gradle /usr/bin
 ---> Running in a2c83519dcbb
Removing intermediate container a2c83519dcbb
 ---> d58488c7c450
Step 5/15 : ENV MAVEN_VERSION=3.3.9
 ---> Running in ccf2f691ce36
Removing intermediate container ccf2f691ce36
 ---> 6bd5ecaaf53a
Step 6/15 : ENV USER_HOME_DIR="/root"
 ---> Running in 38d71bc8ea9b
Removing intermediate container 38d71bc8ea9b
 ---> e2412ad67e76
Step 7/15 : RUN mkdir -p /usr/share/maven /usr/share/maven/ref   && curl -fsSL https://nexus.hyperledger.org/content/repositories/hosted_installers/apache-maven/apache-maven/$MAVEN_VERSION/apache-maven-$MAVEN_VERSION-bin.tar.gz     | tar -xzC /usr/share/maven --strip-components=1   && ln -s /usr/share/maven/bin/mvn /usr/bin/mvn
 ---> Running in 8ec65da24ba8
Removing intermediate container 8ec65da24ba8
 ---> e21203dce463
Step 8/15 : ENV MAVEN_HOME /usr/share/maven
 ---> Running in 7098f91b3b17
Removing intermediate container 7098f91b3b17
 ---> 580183f1cb00
Step 9/15 : ENV MAVEN_CONFIG "$USER_HOME_DIR/.m2"
 ---> Running in a5cbec0f57a7
Removing intermediate container a5cbec0f57a7
 ---> 732d969cb16e
Step 10/15 : ADD payload/javashim.tar.bz2 /root
 ---> aad572d96996
Step 11/15 : ADD payload/protos.tar.bz2 /root
 ---> acbba9d2009c
Step 12/15 : ADD payload/settings.gradle /root
 ---> 257b863b35a9
Step 13/15 : WORKDIR /root
Removing intermediate container 6d2b1ae38b5c
 ---> 2b2614fcf0f0
Step 14/15 : RUN core/chaincode/shim/java/javabuild.sh
 ---> Running in 47f16206694d
Removing intermediate container 47f16206694d
 ---> a3fe08282a30
Step 15/15 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in edbf2b7ddc97
Removing intermediate container edbf2b7ddc97
 ---> fda097aa3bc8
Successfully built fda097aa3bc8
Successfully tagged hyperledger/fabric-javaenv:latest
docker tag hyperledger/fabric-javaenv hyperledger/fabric-javaenv:x86_64-1.1.1-snapshot-ff5e861
build/bin/peer
CGO_CFLAGS=" " GOBIN=/home/vickywang/myCode/go/gopath/src/github.com/hyperledger/fabric/build/bin go install -tags "experimental" -ldflags "-X github.com/hyperledger/fabric/common/metadata.Version=1.1.1-snapshot-ff5e861 -X github.com/hyperledger/fabric/common/metadata.BaseVersion=0.4.6 -X github.com/hyperledger/fabric/common/metadata.BaseDockerLabel=org.hyperledger.fabric -X github.com/hyperledger/fabric/common/metadata.DockerNamespace=hyperledger -X github.com/hyperledger/fabric/common/metadata.BaseDockerNamespace=hyperledger -X github.com/hyperledger/fabric/common/metadata.Experimental=true" github.com/hyperledger/fabric/peer
Binary available as build/bin/peer
```



make 后 的docker images

- `docker images`

```
REPOSITORY                     TAG                             IMAGE ID            CREATED             SIZE
hyperledger/fabric-javaenv     latest                          fda097aa3bc8        2 minutes ago       1.52GB
hyperledger/fabric-javaenv     x86_64-1.1.1-snapshot-ff5e861   fda097aa3bc8        2 minutes ago       1.52GB
hyperledger/fabric-ccenv       latest                          701e56ae3024        7 minutes ago       1.39GB
hyperledger/fabric-ccenv       x86_64-1.1.1-snapshot-ff5e861   701e56ae3024        7 minutes ago       1.39GB
hyperledger/fabric-baseimage   x86_64-0.4.6                    dbe6787b5747        4 months ago        1.37GB
```


## Fabric 工具

- `make configtxgen`

```
build/bin/configtxgen
CGO_CFLAGS=" " GOBIN=/home/vickywang/myCode/go/gopath/src/github.com/hyperledger/fabric/build/bin go install -tags "experimental nopkcs11" -ldflags "-X github.com/hyperledger/fabric/common/tools/configtxgen/metadata.Version=1.1.1-snapshot-ff5e861" github.com/hyperledger/fabric/common/tools/configtxgen
Binary available as build/bin/configtxgen
```


- `make cryptogen`

```
build/bin/cryptogen
CGO_CFLAGS=" " GOBIN=/home/vickywang/myCode/go/gopath/src/github.com/hyperledger/fabric/build/bin go install -tags "experimental" -ldflags "-X github.com/hyperledger/fabric/common/tools/cryptogen/metadata.Version=1.1.1-snapshot-ff5e861" github.com/hyperledger/fabric/common/tools/cryptogen
Binary available as build/bin/cryptogen
```

- `make configtxlator`

```
build/bin/configtxlator
CGO_CFLAGS=" " GOBIN=/home/vickywang/myCode/go/gopath/src/github.com/hyperledger/fabric/build/bin go install -tags "experimental" -ldflags "-X github.com/hyperledger/fabric/common/tools/configtxlator/metadata.Version=1.1.1-snapshot-ff5e861" github.com/hyperledger/fabric/common/tools/configtxlator
Binary available as build/bin/configtxlator
```

## Docker

- `make orderer-docker`

```
Building build/docker/bin/orderer
# github.com/hyperledger/fabric/orderer
/tmp/go-link-291489850/000002.o: In function `pluginOpen':
/tmp/workdir/go/src/plugin/plugin_dlopen.go:19: warning: Using 'dlopen' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
/tmp/go-link-291489850/000000.o: In function `_cgo_b0c710f30cfd_C2func_getaddrinfo':
/tmp/go-build/net/_obj/cgo-gcc-prolog:46: warning: Using 'getaddrinfo' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
(cd sampleconfig && tar -jc *) > build/sampleconfig.tar.bz2
mkdir -p build/image/orderer/payload
cp build/docker/bin/orderer build/sampleconfig.tar.bz2 build/image/orderer/payload
Building docker orderer-image
docker build  -t hyperledger/fabric-orderer build/image/orderer
Sending build context to Docker daemon  29.02MB
Step 1/8 : FROM hyperledger/fabric-baseos:x86_64-0.4.6
x86_64-0.4.6: Pulling from hyperledger/fabric-baseos
1be7f2b886e8: Already exists
6fbc4a21b806: Already exists
c71a6f8e1378: Already exists
4be3072e5a37: Already exists
06c6d2f59700: Already exists
4d536120d8a5: Already exists
0baaf9ec263e: Already exists
Digest: sha256:c66f9e15d8467249bbe80667e94ad2ef877c3d3498510a2acf8e91cf8545e1ce
Status: Downloaded newer image for hyperledger/fabric-baseos:x86_64-0.4.6
 ---> 220e5cf3fb7f
Step 2/8 : ENV FABRIC_CFG_PATH /etc/hyperledger/fabric
 ---> Running in 8d3a1097c6b6
Removing intermediate container 8d3a1097c6b6
 ---> d728fab6015e
Step 3/8 : RUN mkdir -p /var/hyperledger/production $FABRIC_CFG_PATH
 ---> Running in 3176d75d0322
Removing intermediate container 3176d75d0322
 ---> 6e4c05da1e38
Step 4/8 : COPY payload/orderer /usr/local/bin
 ---> d85e8fb05e8e
Step 5/8 : ADD payload/sampleconfig.tar.bz2 $FABRIC_CFG_PATH/
 ---> 9bf4e37abe1d
Step 6/8 : EXPOSE 7050
 ---> Running in 511f05f5f5cf
Removing intermediate container 511f05f5f5cf
 ---> 6d9d99490b10
Step 7/8 : CMD ["orderer"]
 ---> Running in ad8c56cf7d22
Removing intermediate container ad8c56cf7d22
 ---> 21e1b0e9acdf
Step 8/8 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in f3dd1ab3d25e
Removing intermediate container f3dd1ab3d25e
 ---> 66588ba9b04c
Successfully built 66588ba9b04c
Successfully tagged hyperledger/fabric-orderer:latest
docker tag hyperledger/fabric-orderer hyperledger/fabric-orderer:x86_64-1.1.1-snapshot-ff5e861
```


- `make peer-docker`

```
Building build/docker/bin/peer
# github.com/hyperledger/fabric/peer
/tmp/go-link-523907468/000001.o: In function `pluginOpen':
/tmp/workdir/go/src/plugin/plugin_dlopen.go:19: warning: Using 'dlopen' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
/tmp/go-link-523907468/000000.o: In function `_cgo_b0c710f30cfd_C2func_getaddrinfo':
/tmp/go-build/net/_obj/cgo-gcc-prolog:46: warning: Using 'getaddrinfo' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
mkdir -p build/image/peer/payload
cp build/docker/bin/peer build/sampleconfig.tar.bz2 build/image/peer/payload
Building docker peer-image
docker build  -t hyperledger/fabric-peer build/image/peer
Sending build context to Docker daemon  35.43MB
Step 1/7 : FROM hyperledger/fabric-baseos:x86_64-0.4.6
 ---> 220e5cf3fb7f
Step 2/7 : ENV FABRIC_CFG_PATH /etc/hyperledger/fabric
 ---> Using cache
 ---> d728fab6015e
Step 3/7 : RUN mkdir -p /var/hyperledger/production $FABRIC_CFG_PATH
 ---> Using cache
 ---> 6e4c05da1e38
Step 4/7 : COPY payload/peer /usr/local/bin
 ---> 08642f0de63f
Step 5/7 : ADD  payload/sampleconfig.tar.bz2 $FABRIC_CFG_PATH
 ---> 2e92af8e0c23
Step 6/7 : CMD ["peer","node","start"]
 ---> Running in 9893c40cabe3
Removing intermediate container 9893c40cabe3
 ---> 622a7046c14a
Step 7/7 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in d98eaba64734
Removing intermediate container d98eaba64734
 ---> d201a4d6f605
Successfully built d201a4d6f605
Successfully tagged hyperledger/fabric-peer:latest
docker tag hyperledger/fabric-peer hyperledger/fabric-peer:x86_64-1.1.1-snapshot-ff5e861
```

- `make tools-docker`

```
Building build/docker/bin/cryptogen
# github.com/hyperledger/fabric/common/tools/cryptogen
/tmp/go-link-359203969/000002.o: In function `pluginOpen':
/tmp/workdir/go/src/plugin/plugin_dlopen.go:19: warning: Using 'dlopen' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
/tmp/go-link-359203969/000000.o: In function `_cgo_b0c710f30cfd_C2func_getaddrinfo':
/tmp/go-build/net/_obj/cgo-gcc-prolog:46: warning: Using 'getaddrinfo' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
Building build/docker/bin/configtxgen
# github.com/hyperledger/fabric/common/tools/configtxgen
/tmp/go-link-820790411/000000.o: In function `pluginOpen':
/tmp/workdir/go/src/plugin/plugin_dlopen.go:19: warning: Using 'dlopen' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
/tmp/go-link-820790411/000003.o: In function `_cgo_b0c710f30cfd_C2func_getaddrinfo':
/tmp/go-build/net/_obj/cgo-gcc-prolog:46: warning: Using 'getaddrinfo' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
Building build/docker/bin/configtxlator
# github.com/hyperledger/fabric/common/tools/configtxlator
/tmp/go-link-764031475/000002.o: In function `pluginOpen':
/tmp/workdir/go/src/plugin/plugin_dlopen.go:19: warning: Using 'dlopen' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
/tmp/go-link-764031475/000000.o: In function `_cgo_b0c710f30cfd_C2func_getaddrinfo':
/tmp/go-build/net/_obj/cgo-gcc-prolog:46: warning: Using 'getaddrinfo' in statically linked applications requires at runtime the shared libraries from the glibc version used for linking
mkdir -p build/image/tools/payload
cp build/docker/bin/cryptogen build/docker/bin/configtxgen build/docker/bin/configtxlator build/docker/bin/peer build/sampleconfig.tar.bz2 build/image/tools/payload
Building docker tools-image
docker build  -t hyperledger/fabric-tools build/image/tools
Sending build context to Docker daemon  93.57MB
Step 1/9 : FROM hyperledger/fabric-baseimage:x86_64-0.4.6
 ---> dbe6787b5747
Step 2/9 : ENV FABRIC_CFG_PATH /etc/hyperledger/fabric
 ---> Running in afb47d3b9609
Removing intermediate container afb47d3b9609
 ---> b2b69eaf7a0d
Step 3/9 : VOLUME /etc/hyperledger/fabric
 ---> Running in 1647769bae3b
Removing intermediate container 1647769bae3b
 ---> d51d385b1071
Step 4/9 : ADD  payload/sampleconfig.tar.bz2 $FABRIC_CFG_PATH
 ---> f873696c2486
Step 5/9 : COPY payload/cryptogen /usr/local/bin
 ---> 376ae916dedd
Step 6/9 : COPY payload/configtxgen /usr/local/bin
 ---> b31cc2994ed4
Step 7/9 : COPY payload/configtxlator /usr/local/bin
 ---> f34a7c09a4bb
Step 8/9 : COPY payload/peer /usr/local/bin
 ---> b73b445d2be8
Step 9/9 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in 6dae9b1e1412
Removing intermediate container 6dae9b1e1412
 ---> 10bb37804172
Successfully built 10bb37804172
Successfully tagged hyperledger/fabric-tools:latest
docker tag hyperledger/fabric-tools hyperledger/fabric-tools:x86_64-1.1.1-snapshot-ff5e861
```





- `make docker`

```
(cd build/docker/gotools/bin && tar -jc *) > build/gotools.tar.bz2
mkdir -p build/image/buildenv/payload
cp build/gotools.tar.bz2 build/docker/gotools/bin/protoc-gen-go build/image/buildenv/payload
Building docker buildenv-image
docker build  -t hyperledger/fabric-buildenv build/image/buildenv
Sending build context to Docker daemon   21.7MB
Step 1/5 : FROM hyperledger/fabric-baseimage:x86_64-0.4.6
 ---> dbe6787b5747
Step 2/5 : COPY payload/protoc-gen-go /usr/local/bin/
 ---> f8f6b5a9bd18
Step 3/5 : ADD payload/gotools.tar.bz2 /usr/local/bin/
 ---> c0794098bd35
Step 4/5 : RUN go install -a std
 ---> Running in 51fe8b0cd0b2
Removing intermediate container 51fe8b0cd0b2
 ---> 0d7761e324cd
Step 5/5 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in ec28832c77c2
Removing intermediate container ec28832c77c2
 ---> aa667e0dc2e4
Successfully built aa667e0dc2e4
Successfully tagged hyperledger/fabric-buildenv:latest
docker tag hyperledger/fabric-buildenv hyperledger/fabric-buildenv:x86_64-1.1.1-snapshot-ff5e861
mkdir -p build/image/testenv/payload
cp build/docker/bin/orderer build/docker/bin/peer build/sampleconfig.tar.bz2 images/testenv/install-softhsm2.sh build/image/testenv/payload
Building docker testenv-image
docker build  -t hyperledger/fabric-testenv build/image/testenv
Sending build context to Docker daemon  64.43MB
Step 1/10 : FROM hyperledger/fabric-buildenv:x86_64-1.1.1-snapshot-ff5e861
 ---> aa667e0dc2e4
Step 2/10 : ENV FABRIC_CFG_PATH /etc/hyperledger/fabric
 ---> Running in 74dbb5876392
Removing intermediate container 74dbb5876392
 ---> 7e9c1f3a4b1b
Step 3/10 : RUN mkdir -p   $FABRIC_CFG_PATH   /var/hyperledger/production
 ---> Running in ab44c392ec8b
Removing intermediate container ab44c392ec8b
 ---> 7c3e807b1ba7
Step 4/10 : ADD payload/sampleconfig.tar.bz2 $FABRIC_CFG_PATH
 ---> 5c4463534cdb
Step 5/10 : COPY payload/orderer /usr/local/bin
 ---> 4379ef89c638
Step 6/10 : COPY payload/peer /usr/local/bin
 ---> bff46e3de8c9
Step 7/10 : COPY payload/install-softhsm2.sh /tmp
 ---> 9ca227674b2f
Step 8/10 : RUN bash /tmp/install-softhsm2.sh && rm -f install-softhsm2.sh
 ---> Running in 5a1e4ad5bc9b
Get:1 http://security.ubuntu.com/ubuntu xenial-security InRelease [107 kB]
Get:2 http://archive.ubuntu.com/ubuntu xenial InRelease [247 kB]
Get:3 http://security.ubuntu.com/ubuntu xenial-security/universe Sources [81.2 kB]
Get:4 http://security.ubuntu.com/ubuntu xenial-security/main amd64 Packages [652 kB]
Get:5 http://archive.ubuntu.com/ubuntu xenial-updates InRelease [109 kB]
Get:6 http://archive.ubuntu.com/ubuntu xenial-backports InRelease [107 kB]
Get:7 http://archive.ubuntu.com/ubuntu xenial/universe Sources [9802 kB]
Get:8 http://security.ubuntu.com/ubuntu xenial-security/restricted amd64 Packages [12.7 kB]
Get:9 http://security.ubuntu.com/ubuntu xenial-security/universe amd64 Packages [450 kB]
Get:10 http://security.ubuntu.com/ubuntu xenial-security/multiverse amd64 Packages [3735 B]
Get:11 http://archive.ubuntu.com/ubuntu xenial/main amd64 Packages [1558 kB]
Get:12 http://archive.ubuntu.com/ubuntu xenial/restricted amd64 Packages [14.1 kB]
Get:13 http://archive.ubuntu.com/ubuntu xenial/universe amd64 Packages [9827 kB]
Get:14 http://archive.ubuntu.com/ubuntu xenial/multiverse amd64 Packages [176 kB]
Get:15 http://archive.ubuntu.com/ubuntu xenial-updates/universe Sources [257 kB]
Get:16 http://archive.ubuntu.com/ubuntu xenial-updates/main amd64 Packages [1028 kB]
Get:17 http://archive.ubuntu.com/ubuntu xenial-updates/restricted amd64 Packages [13.1 kB]
Get:18 http://archive.ubuntu.com/ubuntu xenial-updates/universe amd64 Packages [820 kB]
Get:19 http://archive.ubuntu.com/ubuntu xenial-updates/multiverse amd64 Packages [18.8 kB]
Get:20 http://archive.ubuntu.com/ubuntu xenial-backports/main amd64 Packages [5157 B]
Get:21 http://archive.ubuntu.com/ubuntu xenial-backports/universe amd64 Packages [8080 B]
Fetched 25.3 MB in 10min 42s (39.4 kB/s)
Reading package lists...
Reading package lists...
Building dependency tree...
Reading state information...
The following additional packages will be installed:
  libsofthsm2 softhsm2-common
The following NEW packages will be installed:
  libsofthsm2 softhsm2 softhsm2-common
0 upgraded, 3 newly installed, 0 to remove and 83 not upgraded.
Need to get 242 kB of archives.
After this operation, 935 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu xenial/universe amd64 softhsm2-common amd64 2.0.0-2ubuntu1 [5920 B]
Get:2 http://archive.ubuntu.com/ubuntu xenial/universe amd64 libsofthsm2 amd64 2.0.0-2ubuntu1 [194 kB]
Get:3 http://archive.ubuntu.com/ubuntu xenial/universe amd64 softhsm2 amd64 2.0.0-2ubuntu1 [42.6 kB]
debconf: unable to initialize frontend: Dialog
debconf: (TERM is not set, so the dialog frontend is not usable.)
debconf: falling back to frontend: Readline
debconf: unable to initialize frontend: Readline
debconf: (This frontend requires a controlling tty.)
debconf: falling back to frontend: Teletype
dpkg-preconfigure: unable to re-open stdin:
Fetched 242 kB in 2s (95.1 kB/s)
Selecting previously unselected package softhsm2-common.
(Reading database ... 22650 files and directories currently installed.)
Preparing to unpack .../softhsm2-common_2.0.0-2ubuntu1_amd64.deb ...
Unpacking softhsm2-common (2.0.0-2ubuntu1) ...
Selecting previously unselected package libsofthsm2.
Preparing to unpack .../libsofthsm2_2.0.0-2ubuntu1_amd64.deb ...
Unpacking libsofthsm2 (2.0.0-2ubuntu1) ...
Selecting previously unselected package softhsm2.
Preparing to unpack .../softhsm2_2.0.0-2ubuntu1_amd64.deb ...
Unpacking softhsm2 (2.0.0-2ubuntu1) ...
Setting up softhsm2-common (2.0.0-2ubuntu1) ...
debconf: unable to initialize frontend: Dialog
debconf: (TERM is not set, so the dialog frontend is not usable.)
debconf: falling back to frontend: Readline

Creating config file /etc/softhsm/softhsm2.conf with new version
Setting up libsofthsm2 (2.0.0-2ubuntu1) ...
Setting up softhsm2 (2.0.0-2ubuntu1) ...
The token has been initialized.
Removing intermediate container 5a1e4ad5bc9b
 ---> f4366cd9c83f
Step 9/10 : WORKDIR /opt/gopath/src/github.com/hyperledger/fabric
Removing intermediate container fa9d3f8b1e2a
 ---> 4370ef99637a
Step 10/10 : LABEL org.hyperledger.fabric.version=1.1.1-snapshot-ff5e861       org.hyperledger.fabric.base.version=0.4.6
 ---> Running in e5994193b087
Removing intermediate container e5994193b087
 ---> 6491fb314257
Successfully built 6491fb314257
Successfully tagged hyperledger/fabric-testenv:latest
docker tag hyperledger/fabric-testenv hyperledger/fabric-testenv:x86_64-1.1.1-snapshot-ff5e861
```


