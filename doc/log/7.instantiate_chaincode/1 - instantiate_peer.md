2018-07-03 02:34:08.446 UTC [endorser] ProcessProposal -> DEBU 59d Entering: Got request from 172.18.0.7:55314
2018-07-03 02:34:08.446 UTC [protoutils] ValidateProposalMessage -> DEBU 59e ValidateProposalMessage starts for signed proposal 0xc4228be1b0
2018-07-03 02:34:08.446 UTC [protoutils] validateChannelHeader -> DEBU 59f validateChannelHeader info: header type 3
2018-07-03 02:34:08.446 UTC [protoutils] checkSignatureFromCreator -> DEBU 5a0 begin
2018-07-03 02:34:08.446 UTC [protoutils] checkSignatureFromCreator -> DEBU 5a1 creator is &{Org2MSP f1f73cc30a2def8068a36dae53ea9655fffea3e6b7aa128a1ae3b9ba1ed344b9}
2018-07-03 02:34:08.446 UTC [protoutils] checkSignatureFromCreator -> DEBU 5a2 creator is valid
2018-07-03 02:34:08.447 UTC [protoutils] checkSignatureFromCreator -> DEBU 5a3 exits successfully
2018-07-03 02:34:08.447 UTC [protoutils] validateChaincodeProposalMessage -> DEBU 5a4 validateChaincodeProposalMessage starts for proposal 0xc4235cd9a0, header 0xc4228be540
2018-07-03 02:34:08.447 UTC [protoutils] validateChaincodeProposalMessage -> DEBU 5a5 validateChaincodeProposalMessage info: header extension references chaincode name:"lscc" 
2018-07-03 02:34:08.447 UTC [endorser] preProcess -> DEBU 5a6 [mychannel][3c7ea620] processing txid: 3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c
2018-07-03 02:34:08.447 UTC [fsblkstorage] retrieveTransactionByID -> DEBU 5a7 retrieveTransactionByID() - txId = [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:08.447 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 5a8 constructing new tx simulator
2018-07-03 02:34:08.447 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 5a9 constructing new tx simulator txid = [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:08.447 UTC [endorser] simulateProposal -> DEBU 5aa [mychannel][3c7ea620] Entry chaincode: name:"lscc" 
2018-07-03 02:34:08.447 UTC [endorser] disableJavaCCInst -> DEBU 5ab java chaincode enabled
2018-07-03 02:34:08.447 UTC [endorser] callChaincode -> DEBU 5ac [mychannel][3c7ea620] Entry chaincode: name:"lscc"  version: 1.1.1-snapshot-ff5e861
2018-07-03 02:34:08.447 UTC [ccprovider] NewCCContext -> DEBU 5ad NewCCCC (chain=mychannel,chaincode=lscc,version=1.1.1-snapshot-ff5e861,txid=3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c,syscc=true,proposal=0xc4235cd9a0,canname=lscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:08.447 UTC [chaincode] Launch -> DEBU 5ae chaincode is running(no need to launch) : lscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:08.447 UTC [chaincode] Execute -> DEBU 5af Entry
2018-07-03 02:34:08.447 UTC [chaincode] Execute -> DEBU 5b0 chaincode canonical name: lscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:08.447 UTC [chaincode] sendExecuteMessage -> DEBU 5b1 [3c7ea620]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 02:34:08.447 UTC [chaincode] setChaincodeProposal -> DEBU 5b2 Setting chaincode proposal context...
2018-07-03 02:34:08.447 UTC [chaincode] setChaincodeProposal -> DEBU 5b3 Proposal different from nil. Creating chaincode proposal context...
2018-07-03 02:34:08.447 UTC [chaincode] sendExecuteMessage -> DEBU 5b4 [3c7ea620]sendExecuteMsg trigger event TRANSACTION
2018-07-03 02:34:08.447 UTC [chaincode] processStream -> DEBU 5b5 [3c7ea620]Move state message TRANSACTION
2018-07-03 02:34:08.447 UTC [chaincode] handleMessage -> DEBU 5b6 [3c7ea620]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 02:34:08.447 UTC [chaincode] filterError -> DEBU 5b7 Ignoring NoTransitionError: no transition
2018-07-03 02:34:08.447 UTC [chaincode] processStream -> DEBU 5b8 [3c7ea620]sending state message TRANSACTION
2018-07-03 02:34:08.447 UTC [shim] func1 -> DEBU 5b9 [3c7ea620]Received message TRANSACTION from shim
2018-07-03 02:34:08.447 UTC [shim] handleMessage -> DEBU 5ba [3c7ea620]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 02:34:08.447 UTC [shim] beforeTransaction -> DEBU 5bb [3c7ea620]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 02:34:08.447 UTC [shim] handleGetState -> DEBU 5bc [3c7ea620]Sending GET_STATE
2018-07-03 02:34:08.447 UTC [chaincode] processStream -> DEBU 5bd [3c7ea620]Received message GET_STATE from shim
2018-07-03 02:34:08.447 UTC [chaincode] handleMessage -> DEBU 5be [3c7ea620]Fabric side Handling ChaincodeMessage of type: GET_STATE in state ready
2018-07-03 02:34:08.447 UTC [chaincode] afterGetState -> DEBU 5bf [3c7ea620]Received GET_STATE, invoking get state from ledger
2018-07-03 02:34:08.447 UTC [chaincode] filterError -> DEBU 5c0 Ignoring NoTransitionError: no transition
2018-07-03 02:34:08.447 UTC [chaincode] func1 -> DEBU 5c1 [3c7ea620] getting state for chaincode lscc, key mycc, channel mychannel
2018-07-03 02:34:08.447 UTC [stateleveldb] GetState -> DEBU 5c2 GetState(). ns=lscc, key=mycc
2018-07-03 02:34:08.447 UTC [chaincode] func1 -> DEBU 5c3 [3c7ea620]No state associated with key: 
mycc. Sending RESPONSE with an empty payload
2018-07-03 02:34:08.448 UTC [chaincode] 1 -> DEBU 5c4 [3c7ea620]handleGetState serial send RESPONSE
2018-07-03 02:34:08.448 UTC [shim] func1 -> DEBU 5c5 [3c7ea620]Received message RESPONSE from shim
2018-07-03 02:34:08.448 UTC [shim] handleMessage -> DEBU 5c6 [3c7ea620]Handling ChaincodeMessage of type: RESPONSE(state:ready)
2018-07-03 02:34:08.448 UTC [shim] sendChannel -> DEBU 5c7 [3c7ea620]before send
2018-07-03 02:34:08.448 UTC [shim] sendChannel -> DEBU 5c8 [3c7ea620]after send
2018-07-03 02:34:08.448 UTC [shim] afterResponse -> DEBU 5c9 [3c7ea620]Received RESPONSE, communicated (state:ready)
2018-07-03 02:34:08.448 UTC [shim] handleGetState -> DEBU 5ca [3c7ea620]GetState received payload RESPONSE
2018-07-03 02:34:08.448 UTC [shim] handlePutState -> DEBU 5cb [3c7ea620]Sending PUT_STATE
2018-07-03 02:34:08.448 UTC [chaincode] processStream -> DEBU 5cc [3c7ea620]Received message PUT_STATE from shim
2018-07-03 02:34:08.448 UTC [chaincode] handleMessage -> DEBU 5cd [3c7ea620]Fabric side Handling ChaincodeMessage of type: PUT_STATE in state ready
2018-07-03 02:34:08.448 UTC [chaincode] filterError -> DEBU 5ce Ignoring NoTransitionError: no transition
2018-07-03 02:34:08.448 UTC [chaincode] func1 -> DEBU 5cf [3c7ea620]state is ready
2018-07-03 02:34:08.448 UTC [chaincode] func1 -> DEBU 5d0 [3c7ea620]Completed PUT_STATE. Sending RESPONSE
2018-07-03 02:34:08.448 UTC [chaincode] 1 -> DEBU 5d1 [3c7ea620]enterBusyState trigger event RESPONSE
2018-07-03 02:34:08.448 UTC [chaincode] processStream -> DEBU 5d2 [3c7ea620]Move state message RESPONSE
2018-07-03 02:34:08.448 UTC [chaincode] handleMessage -> DEBU 5d3 [3c7ea620]Fabric side Handling ChaincodeMessage of type: RESPONSE in state ready
2018-07-03 02:34:08.448 UTC [chaincode] filterError -> DEBU 5d4 Ignoring NoTransitionError: no transition
2018-07-03 02:34:08.448 UTC [chaincode] processStream -> DEBU 5d5 [3c7ea620]sending state message RESPONSE
2018-07-03 02:34:08.448 UTC [shim] func1 -> DEBU 5d6 [3c7ea620]Received message RESPONSE from shim
2018-07-03 02:34:08.448 UTC [shim] handleMessage -> DEBU 5d7 [3c7ea620]Handling ChaincodeMessage of type: RESPONSE(state:ready)
2018-07-03 02:34:08.448 UTC [shim] sendChannel -> DEBU 5d8 [3c7ea620]before send
2018-07-03 02:34:08.448 UTC [shim] sendChannel -> DEBU 5d9 [3c7ea620]after send
2018-07-03 02:34:08.448 UTC [shim] afterResponse -> DEBU 5da [3c7ea620]Received RESPONSE, communicated (state:ready)
2018-07-03 02:34:08.448 UTC [shim] handlePutState -> DEBU 5db [3c7ea620]Received RESPONSE. Successfully updated state
2018-07-03 02:34:08.448 UTC [lscc] putChaincodeCollectionData -> DEBU 5dc No collection configuration specified
2018-07-03 02:34:08.448 UTC [shim] func1 -> DEBU 5dd [3c7ea620]Transaction completed. Sending COMPLETED
2018-07-03 02:34:08.448 UTC [shim] func1 -> DEBU 5de [3c7ea620]Move state message COMPLETED
2018-07-03 02:34:08.448 UTC [shim] handleMessage -> DEBU 5df [3c7ea620]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:34:08.448 UTC [shim] func1 -> DEBU 5e0 [3c7ea620]send state message COMPLETED
2018-07-03 02:34:08.448 UTC [chaincode] processStream -> DEBU 5e1 [3c7ea620]Received message COMPLETED from shim
2018-07-03 02:34:08.448 UTC [chaincode] handleMessage -> DEBU 5e2 [3c7ea620]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:34:08.448 UTC [chaincode] handleMessage -> DEBU 5e3 [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]HandleMessage- COMPLETED. Notify
2018-07-03 02:34:08.448 UTC [chaincode] notify -> DEBU 5e4 notifying Txid:3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c, channelID:mychannel
2018-07-03 02:34:08.448 UTC [chaincode] Execute -> DEBU 5e5 Exit
2018-07-03 02:34:08.448 UTC [ccprovider] NewCCContext -> DEBU 5e6 NewCCCC (chain=mychannel,chaincode=mycc,version=1.0,txid=3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c,syscc=false,proposal=0xc4235cd9a0,canname=mycc:1.0
2018-07-03 02:34:08.448 UTC [chaincode] Launch -> DEBU 5e7 launchAndWaitForRegister fetched 1826 bytes from file system
2018-07-03 02:34:08.448 UTC [chaincode] launchAndWaitForRegister -> DEBU 5e8 chaincode mycc:1.0 is being launched
2018-07-03 02:34:08.449 UTC [chaincode] getLaunchConfigs -> DEBU 5e9 Executable is chaincode
2018-07-03 02:34:08.449 UTC [chaincode] getLaunchConfigs -> DEBU 5ea Args [chaincode -peer.address=peer0.org2.example.com:7052]
2018-07-03 02:34:08.449 UTC [chaincode] getLaunchConfigs -> DEBU 5eb Envs [CORE_CHAINCODE_ID_NAME=mycc:1.0 CORE_PEER_TLS_ENABLED=true CORE_TLS_CLIENT_KEY_PATH=/etc/hyperledger/fabric/client.key CORE_TLS_CLIENT_CERT_PATH=/etc/hyperledger/fabric/client.crt CORE_PEER_TLS_ROOTCERT_FILE=/etc/hyperledger/fabric/peer.crt CORE_CHAINCODE_LOGGING_LEVEL=info CORE_CHAINCODE_LOGGING_SHIM=warning CORE_CHAINCODE_LOGGING_FORMAT=%{color}%{time:2006-01-02 15:04:05.000 MST} [%{module}] %{shortfunc} -> %{level:.4s} %{id:03x}%{color:reset} %{message}]
2018-07-03 02:34:08.449 UTC [chaincode] getLaunchConfigs -> DEBU 5ec FilesToUpload [/etc/hyperledger/fabric/client.key /etc/hyperledger/fabric/client.crt /etc/hyperledger/fabric/peer.crt]
2018-07-03 02:34:08.449 UTC [chaincode] launch -> DEBU 5ed start container: mycc:1.0(networkid:dev,peerid:peer0.org2.example.com)
2018-07-03 02:34:08.449 UTC [chaincode] launch -> DEBU 5ee start container with args: chaincode -peer.address=peer0.org2.example.com:7052
2018-07-03 02:34:08.449 UTC [chaincode] launch -> DEBU 5ef start container with env:
	CORE_CHAINCODE_ID_NAME=mycc:1.0
	CORE_PEER_TLS_ENABLED=true
	CORE_TLS_CLIENT_KEY_PATH=/etc/hyperledger/fabric/client.key
	CORE_TLS_CLIENT_CERT_PATH=/etc/hyperledger/fabric/client.crt
	CORE_PEER_TLS_ROOTCERT_FILE=/etc/hyperledger/fabric/peer.crt
	CORE_CHAINCODE_LOGGING_LEVEL=info
	CORE_CHAINCODE_LOGGING_SHIM=warning
	CORE_CHAINCODE_LOGGING_FORMAT=%{color}%{time:2006-01-02 15:04:05.000 MST} [%{module}] %{shortfunc} -> %{level:.4s} %{id:03x}%{color:reset} %{message}
2018-07-03 02:34:08.449 UTC [container] lockContainer -> DEBU 5f0 waiting for container(dev-peer0.org2.example.com-mycc-1.0) lock
2018-07-03 02:34:08.449 UTC [container] lockContainer -> DEBU 5f1 got container (dev-peer0.org2.example.com-mycc-1.0) lock
2018-07-03 02:34:08.449 UTC [dockercontroller] Start -> DEBU 5f2 Cleanup container dev-peer0.org2.example.com-mycc-1.0
2018-07-03 02:34:08.450 UTC [dockercontroller] stopInternal -> DEBU 5f3 Stop container dev-peer0.org2.example.com-mycc-1.0(No such container: dev-peer0.org2.example.com-mycc-1.0)
2018-07-03 02:34:08.450 UTC [dockercontroller] stopInternal -> DEBU 5f4 Kill container dev-peer0.org2.example.com-mycc-1.0 (No such container: dev-peer0.org2.example.com-mycc-1.0)
2018-07-03 02:34:08.451 UTC [dockercontroller] stopInternal -> DEBU 5f5 Remove container dev-peer0.org2.example.com-mycc-1.0 (No such container: dev-peer0.org2.example.com-mycc-1.0)
2018-07-03 02:34:08.451 UTC [dockercontroller] Start -> DEBU 5f6 Start container dev-peer0.org2.example.com-mycc-1.0
2018-07-03 02:34:08.451 UTC [dockercontroller] getDockerHostConfig -> DEBU 5f7 docker container hostconfig NetworkMode: net_byfn
2018-07-03 02:34:08.452 UTC [dockercontroller] createContainer -> DEBU 5f8 Create container: dev-peer0.org2.example.com-mycc-1.0
2018-07-03 02:34:08.454 UTC [dockercontroller] Start -> DEBU 5f9 start-could not find image <dev-peer0.org2.example.com-mycc-1.0-15b571b3ce849066b7ec74497da3b27e54e0df1345daff3951b94245ce09c42b> (container id <dev-peer0.org2.example.com-mycc-1.0>), because of <no such image>...attempt to recreate image
2018-07-03 02:34:08.454 UTC [chaincode-platform] generateDockerfile -> DEBU 5fa 
FROM hyperledger/fabric-baseos:x86_64-0.4.6
ADD binpackage.tar /usr/local/bin
LABEL org.hyperledger.fabric.chaincode.id.name="mycc" \
      org.hyperledger.fabric.chaincode.id.version="1.0" \
      org.hyperledger.fabric.chaincode.type="GOLANG" \
      org.hyperledger.fabric.version="1.1.1-snapshot-ff5e861" \
      org.hyperledger.fabric.base.version="0.4.6"
ENV CORE_CHAINCODE_BUILDLEVEL=1.1.1-snapshot-ff5e861
2018-07-03 02:34:08.455 UTC [golang-platform] GenerateDockerBuild -> INFO 5fb building chaincode with ldflagsOpt: '-ldflags "-linkmode external -extldflags '-static'"'
2018-07-03 02:34:08.455 UTC [golang-platform] GenerateDockerBuild -> INFO 5fc building chaincode with tags:  experimental
2018-07-03 02:34:08.455 UTC [util] DockerBuild -> DEBU 5fd Attempting build with image hyperledger/fabric-ccenv:x86_64-1.1.1-snapshot-ff5e861

