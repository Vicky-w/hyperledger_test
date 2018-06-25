# 环境介绍
   电脑系统为window10，安装VMware虚拟机，并安装ubuntu-16.04-desktop-amd64.iso 镜像。
   后续操作使用的都为Ubuntu 系统。
   如果没有制定目录须自行创建。
# 基础操作
  ## 切换用户
  - `sudo su`

  ## 基础依赖安装
  - `sudo apt-get install vim`
  - `sudo apt-get install lrzsz`
  - `sudo apt-get install git`

  ## 上传依赖
  - `cd /home/vickywang/base`

  上传所有package所有包到此目录下
  - `tar -zxvf *******`

  解压所有包目录

  ```
    ├── base
        	├── go
	        ├── jdk1.8.0_144
	        ├── node-v6.9.4-linux-x64
	        ├── GoLand-2018.1.5               tool
	        ├── WebStorm-181.5281.31          tool

  ```

  ## 环境变量配置


  - `sudo vim  /etc/profile`

  ```
         export GOROOT=/home/vickywang/base/go
         export GOPATH=/home/vickywang/myCode/go/gopath
         export NODE_HOME=/home/vickywang/base/node-v6.9.4-linux-x64
        export NODE_PATH=$NODE_HOME/lib/node_modules
        export JAVA_HOME=/home/vickywang/base/jdk1.8.0_144
         export CLASSPATH=.:$JAVA_HOME/lib:$JAVA_HOME/jre/lib:$CLASSPATH
        export PATH=$PATH:$NODE_HOME/bin:$JAVA_HOME/bin:$JAVA_HOME/jre/bin:$GOROOT/bin
  ```
  - `source /etc/profile`

Go 版本

  - `go version`
  ```
    go version go1.8.3 linux/amd64
  ```
Java 版本

  - `java -version`
  ```
    java version "1.8.0_144"
    Java(TM) SE Runtime Environment (build 1.8.0_144-b01)
    Java HotSpot(TM) 64-Bit Server VM (build 25.144-b01, mixed mode)
  ```
Node 版本

  - `node -v`
  ```
        v6.9.4
  ```
  - `npm -v`
  ```
        3.10.10
  ```

  ## 安装Docker && Docker Compose

  ### Docker
      - `curl -sSL https://get.daocloud.io/docker | sh`
      - `sudo usermod -aG docker vickywang`

          Docker版本查询

  ```
            Client:
             Version:      18.05.0-ce
             API version:  1.37
             Go version:   go1.9.5
             Git commit:   f150324
             Built:        Wed May  9 22:16:25 2018
             OS/Arch:      linux/amd64
             Experimental: false
             Orchestrator: swarm

            Server:
             Engine:
              Version:      18.05.0-ce
              API version:  1.37 (minimum version 1.12)
              Go version:   go1.9.5
              Git commit:   f150324
              Built:        Wed May  9 22:14:32 2018
              OS/Arch:      linux/amd64
              Experimental: false

  ```

        卸载

             - `sudo apt-get remove docker docker-engine`
             - `rm -fr /var/lib/docker/`

### Docker Compose



  - `curl -L https://get.daocloud.io/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose`
  - `chmod +x /usr/local/bin/docker-compose`


        Docker Compose版本查询


  - `docker-compose -v`
  ```
     docker-compose version 1.21.2, build a133471
  ```

  ## 合约依赖

   - `apt-get install -y libsnappy-dev zlib1g-dev libbz2-dev libltdl-dev libtool`

  ## 更新
  ```
  - `apt-get update`
  - `apt-get upgrade`

  ```