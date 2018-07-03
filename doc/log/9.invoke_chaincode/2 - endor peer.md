2018-07-03 05:22:44.640 UTC [endorser] ProcessProposal -> DEBU b19 Entering: Got request from 172.18.0.7:45720
2018-07-03 05:22:44.640 UTC [protoutils] ValidateProposalMessage -> DEBU b1a ValidateProposalMessage starts for signed proposal 0xc422dae7b0
2018-07-03 05:22:44.640 UTC [protoutils] validateChannelHeader -> DEBU b1b validateChannelHeader info: header type 3
2018-07-03 05:22:44.640 UTC [protoutils] checkSignatureFromCreator -> DEBU b1c begin
2018-07-03 05:22:44.640 UTC [protoutils] checkSignatureFromCreator -> DEBU b1d creator is &{Org1MSP ac67b3a157128c9f7eaf4b0c38e09cef3b66e6664863161de2c42f7549ab5ffb}
2018-07-03 05:22:44.640 UTC [protoutils] checkSignatureFromCreator -> DEBU b1e creator is valid
2018-07-03 05:22:44.640 UTC [protoutils] checkSignatureFromCreator -> DEBU b1f exits successfully
2018-07-03 05:22:44.641 UTC [protoutils] validateChaincodeProposalMessage -> DEBU b20 validateChaincodeProposalMessage starts for proposal 0xc4233324b0, header 0xc422daeba0
2018-07-03 05:22:44.641 UTC [protoutils] validateChaincodeProposalMessage -> DEBU b21 validateChaincodeProposalMessage info: header extension references chaincode name:"mycc" 
2018-07-03 05:22:44.641 UTC [endorser] preProcess -> DEBU b22 [mychannel][ced12bdc] processing txid: ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8
2018-07-03 05:22:44.641 UTC [fsblkstorage] retrieveTransactionByID -> DEBU b23 retrieveTransactionByID() - txId = [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:44.641 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU b24 constructing new tx simulator
2018-07-03 05:22:44.641 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU b25 constructing new tx simulator txid = [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:44.641 UTC [endorser] simulateProposal -> DEBU b26 [mychannel][ced12bdc] Entry chaincode: name:"mycc" 
2018-07-03 05:22:44.641 UTC [ccprovider] NewCCContext -> DEBU b27 NewCCCC (chain=mychannel,chaincode=lscc,version=1.1.1-snapshot-ff5e861,txid=ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8,syscc=true,proposal=0xc4233324b0,canname=lscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.641 UTC [chaincode] Launch -> DEBU b28 chaincode is running(no need to launch) : lscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.641 UTC [chaincode] Execute -> DEBU b29 Entry
2018-07-03 05:22:44.641 UTC [chaincode] Execute -> DEBU b2a chaincode canonical name: lscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.642 UTC [chaincode] sendExecuteMessage -> DEBU b2b [ced12bdc]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 05:22:44.642 UTC [chaincode] setChaincodeProposal -> DEBU b2c Setting chaincode proposal context...
2018-07-03 05:22:44.642 UTC [chaincode] setChaincodeProposal -> DEBU b2d Proposal different from nil. Creating chaincode proposal context...
2018-07-03 05:22:44.642 UTC [chaincode] sendExecuteMessage -> DEBU b2e [ced12bdc]sendExecuteMsg trigger event TRANSACTION
2018-07-03 05:22:44.642 UTC [chaincode] processStream -> DEBU b2f [ced12bdc]Move state message TRANSACTION
2018-07-03 05:22:44.642 UTC [chaincode] handleMessage -> DEBU b30 [ced12bdc]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 05:22:44.642 UTC [chaincode] filterError -> DEBU b31 Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.642 UTC [chaincode] processStream -> DEBU b32 [ced12bdc]sending state message TRANSACTION
2018-07-03 05:22:44.642 UTC [shim] func1 -> DEBU b33 [ced12bdc]Received message TRANSACTION from shim
2018-07-03 05:22:44.642 UTC [shim] handleMessage -> DEBU b34 [ced12bdc]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 05:22:44.642 UTC [shim] beforeTransaction -> DEBU b35 [ced12bdc]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 05:22:44.642 UTC [shim] handleGetState -> DEBU b36 [ced12bdc]Sending GET_STATE
2018-07-03 05:22:44.642 UTC [chaincode] processStream -> DEBU b37 [ced12bdc]Received message GET_STATE from shim
2018-07-03 05:22:44.642 UTC [chaincode] handleMessage -> DEBU b38 [ced12bdc]Fabric side Handling ChaincodeMessage of type: GET_STATE in state ready
2018-07-03 05:22:44.642 UTC [chaincode] afterGetState -> DEBU b39 [ced12bdc]Received GET_STATE, invoking get state from ledger
2018-07-03 05:22:44.642 UTC [chaincode] filterError -> DEBU b3a Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.642 UTC [chaincode] func1 -> DEBU b3b [ced12bdc] getting state for chaincode lscc, key mycc, channel mychannel
2018-07-03 05:22:44.643 UTC [stateleveldb] GetState -> DEBU b3c GetState(). ns=lscc, key=mycc
2018-07-03 05:22:44.643 UTC [chaincode] func1 -> DEBU b3d [ced12bdc]Got state. Sending RESPONSE
2018-07-03 05:22:44.643 UTC [chaincode] 1 -> DEBU b3e [ced12bdc]handleGetState serial send RESPONSE
2018-07-03 05:22:44.643 UTC [shim] func1 -> DEBU b3f [ced12bdc]Received message RESPONSE from shim
2018-07-03 05:22:44.643 UTC [shim] handleMessage -> DEBU b40 [ced12bdc]Handling ChaincodeMessage of type: RESPONSE(state:ready)
2018-07-03 05:22:44.643 UTC [shim] sendChannel -> DEBU b41 [ced12bdc]before send
2018-07-03 05:22:44.643 UTC [shim] sendChannel -> DEBU b42 [ced12bdc]after send
2018-07-03 05:22:44.643 UTC [shim] afterResponse -> DEBU b43 [ced12bdc]Received RESPONSE, communicated (state:ready)
2018-07-03 05:22:44.643 UTC [shim] handleGetState -> DEBU b44 [ced12bdc]GetState received payload RESPONSE
2018-07-03 05:22:44.643 UTC [shim] func1 -> DEBU b45 [ced12bdc]Transaction completed. Sending COMPLETED
2018-07-03 05:22:44.643 UTC [shim] func1 -> DEBU b46 [ced12bdc]Move state message COMPLETED
2018-07-03 05:22:44.643 UTC [shim] handleMessage -> DEBU b47 [ced12bdc]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 05:22:44.643 UTC [shim] func1 -> DEBU b48 [ced12bdc]send state message COMPLETED
2018-07-03 05:22:44.643 UTC [chaincode] processStream -> DEBU b49 [ced12bdc]Received message COMPLETED from shim
2018-07-03 05:22:44.643 UTC [chaincode] handleMessage -> DEBU b4a [ced12bdc]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 05:22:44.643 UTC [chaincode] handleMessage -> DEBU b4b [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]HandleMessage- COMPLETED. Notify
2018-07-03 05:22:44.643 UTC [chaincode] notify -> DEBU b4c notifying Txid:ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8, channelID:mychannel
2018-07-03 05:22:44.643 UTC [chaincode] Execute -> DEBU b4d Exit
2018-07-03 05:22:44.643 UTC [ccprovider] GetChaincodeData -> DEBU b4e Getting chaincode data for <mycc, 1.0> from cache
2018-07-03 05:22:44.643 UTC [endorser] callChaincode -> DEBU b4f [mychannel][ced12bdc] Entry chaincode: name:"mycc"  version: 1.0
2018-07-03 05:22:44.643 UTC [ccprovider] NewCCContext -> DEBU b50 NewCCCC (chain=mychannel,chaincode=mycc,version=1.0,txid=ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8,syscc=false,proposal=0xc4233324b0,canname=mycc:1.0
2018-07-03 05:22:44.643 UTC [chaincode] Launch -> DEBU b51 chaincode is running(no need to launch) : mycc:1.0
2018-07-03 05:22:44.644 UTC [chaincode] Execute -> DEBU b52 Entry
2018-07-03 05:22:44.644 UTC [chaincode] Execute -> DEBU b53 chaincode canonical name: mycc:1.0
2018-07-03 05:22:44.644 UTC [chaincode] sendExecuteMessage -> DEBU b54 [ced12bdc]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 05:22:44.644 UTC [chaincode] setChaincodeProposal -> DEBU b55 Setting chaincode proposal context...
2018-07-03 05:22:44.644 UTC [chaincode] setChaincodeProposal -> DEBU b56 Proposal different from nil. Creating chaincode proposal context...
2018-07-03 05:22:44.644 UTC [chaincode] sendExecuteMessage -> DEBU b57 [ced12bdc]sendExecuteMsg trigger event TRANSACTION
2018-07-03 05:22:44.644 UTC [chaincode] processStream -> DEBU b58 [ced12bdc]Move state message TRANSACTION
2018-07-03 05:22:44.644 UTC [chaincode] handleMessage -> DEBU b59 [ced12bdc]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 05:22:44.644 UTC [chaincode] filterError -> DEBU b5a Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.645 UTC [chaincode] processStream -> DEBU b5b [ced12bdc]sending state message TRANSACTION
2018-07-03 05:22:44.650 UTC [chaincode] processStream -> DEBU b5c [ced12bdc]Received message GET_STATE from shim
2018-07-03 05:22:44.650 UTC [chaincode] handleMessage -> DEBU b5d [ced12bdc]Fabric side Handling ChaincodeMessage of type: GET_STATE in state ready
2018-07-03 05:22:44.650 UTC [chaincode] afterGetState -> DEBU b5e [ced12bdc]Received GET_STATE, invoking get state from ledger
2018-07-03 05:22:44.650 UTC [chaincode] filterError -> DEBU b5f Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.650 UTC [chaincode] func1 -> DEBU b60 [ced12bdc] getting state for chaincode mycc, key a, channel mychannel
2018-07-03 05:22:44.650 UTC [stateleveldb] GetState -> DEBU b61 GetState(). ns=mycc, key=a
2018-07-03 05:22:44.650 UTC [chaincode] func1 -> DEBU b62 [ced12bdc]Got state. Sending RESPONSE
2018-07-03 05:22:44.650 UTC [chaincode] 1 -> DEBU b63 [ced12bdc]handleGetState serial send RESPONSE
2018-07-03 05:22:44.650 UTC [chaincode] processStream -> DEBU b64 [ced12bdc]Received message GET_STATE from shim
2018-07-03 05:22:44.650 UTC [chaincode] handleMessage -> DEBU b65 [ced12bdc]Fabric side Handling ChaincodeMessage of type: GET_STATE in state ready
2018-07-03 05:22:44.650 UTC [chaincode] afterGetState -> DEBU b66 [ced12bdc]Received GET_STATE, invoking get state from ledger
2018-07-03 05:22:44.650 UTC [chaincode] filterError -> DEBU b67 Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.651 UTC [chaincode] func1 -> DEBU b68 [ced12bdc] getting state for chaincode mycc, key b, channel mychannel
2018-07-03 05:22:44.651 UTC [stateleveldb] GetState -> DEBU b69 GetState(). ns=mycc, key=b
2018-07-03 05:22:44.651 UTC [chaincode] func1 -> DEBU b6a [ced12bdc]Got state. Sending RESPONSE
2018-07-03 05:22:44.651 UTC [chaincode] 1 -> DEBU b6b [ced12bdc]handleGetState serial send RESPONSE
2018-07-03 05:22:44.651 UTC [chaincode] processStream -> DEBU b6c [ced12bdc]Received message PUT_STATE from shim
2018-07-03 05:22:44.651 UTC [chaincode] handleMessage -> DEBU b6d [ced12bdc]Fabric side Handling ChaincodeMessage of type: PUT_STATE in state ready
2018-07-03 05:22:44.651 UTC [chaincode] filterError -> DEBU b6e Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.651 UTC [chaincode] func1 -> DEBU b6f [ced12bdc]state is ready
2018-07-03 05:22:44.651 UTC [chaincode] func1 -> DEBU b70 [ced12bdc]Completed PUT_STATE. Sending RESPONSE
2018-07-03 05:22:44.651 UTC [chaincode] 1 -> DEBU b71 [ced12bdc]enterBusyState trigger event RESPONSE
2018-07-03 05:22:44.651 UTC [chaincode] processStream -> DEBU b72 [ced12bdc]Move state message RESPONSE
2018-07-03 05:22:44.651 UTC [chaincode] handleMessage -> DEBU b73 [ced12bdc]Fabric side Handling ChaincodeMessage of type: RESPONSE in state ready
2018-07-03 05:22:44.651 UTC [chaincode] filterError -> DEBU b74 Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.651 UTC [chaincode] processStream -> DEBU b75 [ced12bdc]sending state message RESPONSE
2018-07-03 05:22:44.651 UTC [chaincode] processStream -> DEBU b76 [ced12bdc]Received message PUT_STATE from shim
2018-07-03 05:22:44.651 UTC [chaincode] handleMessage -> DEBU b77 [ced12bdc]Fabric side Handling ChaincodeMessage of type: PUT_STATE in state ready
2018-07-03 05:22:44.651 UTC [chaincode] filterError -> DEBU b78 Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.652 UTC [chaincode] func1 -> DEBU b79 [ced12bdc]state is ready
2018-07-03 05:22:44.652 UTC [chaincode] func1 -> DEBU b7a [ced12bdc]Completed PUT_STATE. Sending RESPONSE
2018-07-03 05:22:44.652 UTC [chaincode] 1 -> DEBU b7b [ced12bdc]enterBusyState trigger event RESPONSE
2018-07-03 05:22:44.652 UTC [chaincode] processStream -> DEBU b7c [ced12bdc]Move state message RESPONSE
2018-07-03 05:22:44.652 UTC [chaincode] handleMessage -> DEBU b7d [ced12bdc]Fabric side Handling ChaincodeMessage of type: RESPONSE in state ready
2018-07-03 05:22:44.652 UTC [chaincode] filterError -> DEBU b7e Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.652 UTC [chaincode] processStream -> DEBU b7f [ced12bdc]sending state message RESPONSE
2018-07-03 05:22:44.652 UTC [chaincode] processStream -> DEBU b80 [ced12bdc]Received message COMPLETED from shim
2018-07-03 05:22:44.652 UTC [chaincode] handleMessage -> DEBU b81 [ced12bdc]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 05:22:44.652 UTC [chaincode] handleMessage -> DEBU b82 [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]HandleMessage- COMPLETED. Notify
2018-07-03 05:22:44.652 UTC [chaincode] notify -> DEBU b83 notifying Txid:ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8, channelID:mychannel
2018-07-03 05:22:44.652 UTC [chaincode] Execute -> DEBU b84 Exit
2018-07-03 05:22:44.652 UTC [endorser] callChaincode -> DEBU b85 [mychannel][ced12bdc] Exit
2018-07-03 05:22:44.652 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU b86 Simulation completed, getting simulation results
2018-07-03 05:22:44.652 UTC [lockbasedtxmgr] Done -> DEBU b87 Done with transaction simulation / query execution [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:44.652 UTC [endorser] simulateProposal -> DEBU b88 [mychannel][ced12bdc] Exit
2018-07-03 05:22:44.653 UTC [endorser] endorseProposal -> DEBU b89 [mychannel][ced12bdc] Entry chaincode: name:"mycc" 
2018-07-03 05:22:44.653 UTC [endorser] endorseProposal -> DEBU b8a [mychannel][ced12bdc] escc for chaincode name:"mycc"  is escc
2018-07-03 05:22:44.653 UTC [endorser] callChaincode -> DEBU b8b [mychannel][ced12bdc] Entry chaincode: name:"escc"  version: 1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.653 UTC [ccprovider] NewCCContext -> DEBU b8c NewCCCC (chain=mychannel,chaincode=escc,version=1.1.1-snapshot-ff5e861,txid=ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8,syscc=true,proposal=0xc4233324b0,canname=escc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.653 UTC [chaincode] Launch -> DEBU b8d chaincode is running(no need to launch) : escc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.653 UTC [chaincode] Execute -> DEBU b8e Entry
2018-07-03 05:22:44.653 UTC [chaincode] Execute -> DEBU b8f chaincode canonical name: escc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:44.653 UTC [chaincode] sendExecuteMessage -> DEBU b90 [ced12bdc]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 05:22:44.653 UTC [chaincode] setChaincodeProposal -> DEBU b91 Setting chaincode proposal context...
2018-07-03 05:22:44.653 UTC [chaincode] setChaincodeProposal -> DEBU b92 Proposal different from nil. Creating chaincode proposal context...
2018-07-03 05:22:44.653 UTC [chaincode] sendExecuteMessage -> DEBU b93 [ced12bdc]sendExecuteMsg trigger event TRANSACTION
2018-07-03 05:22:44.653 UTC [chaincode] processStream -> DEBU b94 [ced12bdc]Move state message TRANSACTION
2018-07-03 05:22:44.653 UTC [chaincode] handleMessage -> DEBU b95 [ced12bdc]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 05:22:44.653 UTC [chaincode] filterError -> DEBU b96 Ignoring NoTransitionError: no transition
2018-07-03 05:22:44.653 UTC [chaincode] processStream -> DEBU b97 [ced12bdc]sending state message TRANSACTION
2018-07-03 05:22:44.653 UTC [shim] func1 -> DEBU b98 [ced12bdc]Received message TRANSACTION from shim
2018-07-03 05:22:44.653 UTC [shim] handleMessage -> DEBU b99 [ced12bdc]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 05:22:44.653 UTC [shim] beforeTransaction -> DEBU b9a [ced12bdc]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 05:22:44.653 UTC [escc] Invoke -> DEBU b9b ESCC starts: 8 args
2018-07-03 05:22:44.653 UTC [escc] Invoke -> DEBU b9c ESCC exits successfully
2018-07-03 05:22:44.653 UTC [shim] func1 -> DEBU b9d [ced12bdc]Transaction completed. Sending COMPLETED
2018-07-03 05:22:44.653 UTC [shim] func1 -> DEBU b9e [ced12bdc]Move state message COMPLETED
2018-07-03 05:22:44.653 UTC [shim] handleMessage -> DEBU b9f [ced12bdc]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 05:22:44.653 UTC [shim] func1 -> DEBU ba0 [ced12bdc]send state message COMPLETED
2018-07-03 05:22:44.653 UTC [chaincode] processStream -> DEBU ba1 [ced12bdc]Received message COMPLETED from shim
2018-07-03 05:22:44.653 UTC [chaincode] handleMessage -> DEBU ba2 [ced12bdc]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 05:22:44.653 UTC [chaincode] handleMessage -> DEBU ba3 [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]HandleMessage- COMPLETED. Notify
2018-07-03 05:22:44.653 UTC [chaincode] notify -> DEBU ba4 notifying Txid:ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8, channelID:mychannel
2018-07-03 05:22:44.653 UTC [chaincode] Execute -> DEBU ba5 Exit
2018-07-03 05:22:44.653 UTC [endorser] callChaincode -> DEBU ba6 [mychannel][ced12bdc] Exit
2018-07-03 05:22:44.653 UTC [endorser] endorseProposal -> DEBU ba7 [mychannel][ced12bdc] Exit
2018-07-03 05:22:44.653 UTC [lockbasedtxmgr] Done -> DEBU ba8 Done with transaction simulation / query execution [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:44.653 UTC [endorser] ProcessProposal -> DEBU ba9 Exit: request from%!(EXTRA string=172.18.0.7:45720)

