2018-07-03 05:22:46.675 UTC [blocksProvider] DeliverBlocks -> DEBU 86c [mychannel] Adding payload locally, buffer seqNum = [8], peers number [3]
2018-07-03 05:22:46.675 UTC [blocksProvider] DeliverBlocks -> DEBU 86d [mychannel] Gossiping block [8], peers number [3]
2018-07-03 05:22:46.675 UTC [committer/txvalidator] Validate -> DEBU 86e START Block Validation
2018-07-03 05:22:46.675 UTC [committer/txvalidator] Validate -> DEBU 86f expecting 1 block validation responses
2018-07-03 05:22:46.675 UTC [committer/txvalidator] validateTx -> DEBU 870 validateTx starts for block 0xc4237f2300 env 0xc4232c5380 txn 0
2018-07-03 05:22:46.675 UTC [protoutils] ValidateTransaction -> DEBU 871 ValidateTransactionEnvelope starts for envelope 0xc4232c5380
2018-07-03 05:22:46.675 UTC [protoutils] ValidateTransaction -> DEBU 872 Header is channel_header:"\010\003\032\014\010\244\220\354\331\005\020\236\232\206\261\002\"\tmychannel*@ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8:\010\022\006\022\004mycc" signature_header:"\n\266\006\n\007Org1MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\n\022\030r'\036\204Ie \277\235\032\306I\237\230 \345H/\267\333\236\312\023\336" 
2018-07-03 05:22:46.675 UTC [protoutils] validateChannelHeader -> DEBU 873 validateChannelHeader info: header type 3
2018-07-03 05:22:46.675 UTC [protoutils] checkSignatureFromCreator -> DEBU 874 begin
2018-07-03 05:22:46.675 UTC [protoutils] checkSignatureFromCreator -> DEBU 875 creator is &{Org1MSP ac67b3a157128c9f7eaf4b0c38e09cef3b66e6664863161de2c42f7549ab5ffb}
2018-07-03 05:22:46.676 UTC [protoutils] checkSignatureFromCreator -> DEBU 876 creator is valid
2018-07-03 05:22:46.676 UTC [protoutils] checkSignatureFromCreator -> DEBU 877 exits successfully
2018-07-03 05:22:46.676 UTC [protoutils] validateEndorserTransaction -> DEBU 878 validateEndorserTransaction starts for data 0xc4237f5000, header channel_header:"\010\003\032\014\010\244\220\354\331\005\020\236\232\206\261\002\"\tmychannel*@ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8:\010\022\006\022\004mycc" signature_header:"\n\266\006\n\007Org1MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\n\022\030r'\036\204Ie \277\235\032\306I\237\230 \345H/\267\333\236\312\023\336" 
2018-07-03 05:22:46.676 UTC [protoutils] validateEndorserTransaction -> DEBU 879 validateEndorserTransaction info: there are 1 actions
2018-07-03 05:22:46.676 UTC [protoutils] validateEndorserTransaction -> DEBU 87a validateEndorserTransaction info: signature header is valid
2018-07-03 05:22:46.676 UTC [protoutils] ValidateTransaction -> DEBU 87b ValidateTransactionEnvelope returns err %!s(<nil>)
2018-07-03 05:22:46.676 UTC [committer/txvalidator] validateTx -> DEBU 87c Transaction is for channel mychannel
2018-07-03 05:22:46.676 UTC [fsblkstorage] retrieveTransactionByID -> DEBU 87d retrieveTransactionByID() - txId = [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:46.676 UTC [committer/txvalidator] validateTx -> DEBU 87e Validating transaction vscc tx validate
2018-07-03 05:22:46.676 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 87f VSCCValidateTx starts for env 0xc4232c5380 envbytes 0xc422525c00
2018-07-03 05:22:46.676 UTC [lockbasedtxmgr] newQueryExecutor -> DEBU 880 constructing new query executor txid = [eb2fa297-fd0d-4e4a-a34c-71498beac70b]
2018-07-03 05:22:46.676 UTC [stateleveldb] GetState -> DEBU 881 GetState(). ns=lscc, key=mycc
2018-07-03 05:22:46.677 UTC [lockbasedtxmgr] Done -> DEBU 882 Done with transaction simulation / query execution [eb2fa297-fd0d-4e4a-a34c-71498beac70b]
2018-07-03 05:22:46.677 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 883 VSCCValidateTxForCC starts for envbytes 0xc422525c00
2018-07-03 05:22:46.677 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 884 constructing new tx simulator
2018-07-03 05:22:46.677 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 885 constructing new tx simulator txid = [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:46.677 UTC [ccprovider] NewCCContext -> DEBU 886 NewCCCC (chain=mychannel,chaincode=vscc,version=1.1.1-snapshot-ff5e861,txid=92e90c3f-6b58-437a-bdfa-2d7b18448358,syscc=true,proposal=0x0,canname=vscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:46.677 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 887 Invoking VSCC txid ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8 chaindID mychannel
2018-07-03 05:22:46.677 UTC [chaincode] Launch -> DEBU 888 chaincode is running(no need to launch) : vscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:46.677 UTC [chaincode] Execute -> DEBU 889 Entry
2018-07-03 05:22:46.677 UTC [chaincode] Execute -> DEBU 88a chaincode canonical name: vscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:46.677 UTC [chaincode] sendExecuteMessage -> DEBU 88b [92e90c3f]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 05:22:46.677 UTC [chaincode] setChaincodeProposal -> DEBU 88c Setting chaincode proposal context...
2018-07-03 05:22:46.677 UTC [chaincode] sendExecuteMessage -> DEBU 88d [92e90c3f]sendExecuteMsg trigger event TRANSACTION
2018-07-03 05:22:46.677 UTC [chaincode] processStream -> DEBU 88e [92e90c3f]Move state message TRANSACTION
2018-07-03 05:22:46.677 UTC [chaincode] handleMessage -> DEBU 88f [92e90c3f]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 05:22:46.677 UTC [chaincode] filterError -> DEBU 890 Ignoring NoTransitionError: no transition
2018-07-03 05:22:46.677 UTC [chaincode] processStream -> DEBU 891 [92e90c3f]sending state message TRANSACTION
2018-07-03 05:22:46.677 UTC [shim] func1 -> DEBU 892 [92e90c3f]Received message TRANSACTION from shim
2018-07-03 05:22:46.677 UTC [shim] handleMessage -> DEBU 893 [92e90c3f]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 05:22:46.677 UTC [shim] beforeTransaction -> DEBU 894 [92e90c3f]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 05:22:46.677 UTC [vscc] Invoke -> DEBU 895 VSCC invoked
2018-07-03 05:22:46.677 UTC [vscc] deduplicateIdentity -> DEBU 896 Signature set is of size 1 out of 1 endorsement(s)
2018-07-03 05:22:46.678 UTC [vscc] Invoke -> DEBU 897 VSCC exists successfully
2018-07-03 05:22:46.678 UTC [shim] func1 -> DEBU 898 [92e90c3f]Transaction completed. Sending COMPLETED
2018-07-03 05:22:46.678 UTC [shim] func1 -> DEBU 899 [92e90c3f]Move state message COMPLETED
2018-07-03 05:22:46.678 UTC [shim] handleMessage -> DEBU 89a [92e90c3f]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 05:22:46.678 UTC [shim] func1 -> DEBU 89b [92e90c3f]send state message COMPLETED
2018-07-03 05:22:46.678 UTC [chaincode] processStream -> DEBU 89c [92e90c3f]Received message COMPLETED from shim
2018-07-03 05:22:46.678 UTC [chaincode] handleMessage -> DEBU 89d [92e90c3f]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 05:22:46.678 UTC [chaincode] handleMessage -> DEBU 89e [92e90c3f-6b58-437a-bdfa-2d7b18448358]HandleMessage- COMPLETED. Notify
2018-07-03 05:22:46.678 UTC [chaincode] notify -> DEBU 89f notifying Txid:92e90c3f-6b58-437a-bdfa-2d7b18448358, channelID:mychannel
2018-07-03 05:22:46.678 UTC [chaincode] Execute -> DEBU 8a0 Exit
2018-07-03 05:22:46.678 UTC [lockbasedtxmgr] Done -> DEBU 8a1 Done with transaction simulation / query execution [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:46.678 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 8a2 VSCCValidateTxForCC completes for envbytes 0xc422525c00
2018-07-03 05:22:46.678 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 8a3 VSCCValidateTx completes for env 0xc4232c5380 envbytes 0xc422525c00
2018-07-03 05:22:46.678 UTC [committer/txvalidator] validateTx -> DEBU 8a4 validateTx completes for block 0xc4237f2300 env 0xc4232c5380 txn 0
2018-07-03 05:22:46.678 UTC [committer/txvalidator] Validate -> DEBU 8a5 got result for idx 0, code 0
2018-07-03 05:22:46.678 UTC [committer/txvalidator] Validate -> DEBU 8a6 END Block Validation
2018-07-03 05:22:46.678 UTC [kvledger] CommitWithPvtData -> DEBU 8a7 Channel [mychannel]: Validating state for block [8]
2018-07-03 05:22:46.678 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 8a8 Validating new block with num trans = [1]
2018-07-03 05:22:46.678 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 8a9 ValidateAndPrepareBatch() for block number = [8]
2018-07-03 05:22:46.678 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 8aa preprocessing ProtoBlock...
2018-07-03 05:22:46.678 UTC [valimpl] preprocessProtoBlock -> DEBU 8ab txType=ENDORSER_TRANSACTION
2018-07-03 05:22:46.678 UTC [stateleveldb] GetState -> DEBU 8ac GetState(). ns=lscc, key=mycc
2018-07-03 05:22:46.678 UTC [statebasedval] validateKVRead -> DEBU 8ad Comparing versions for key [mycc]: committed version=&version.Height{BlockNum:0x3, TxNum:0x0} and read version=&version.Height{BlockNum:0x3, TxNum:0x0}
2018-07-03 05:22:46.678 UTC [stateleveldb] GetState -> DEBU 8ae GetState(). ns=mycc, key=a
2018-07-03 05:22:46.678 UTC [statebasedval] validateKVRead -> DEBU 8af Comparing versions for key [a]: committed version=&version.Height{BlockNum:0x7, TxNum:0x0} and read version=&version.Height{BlockNum:0x7, TxNum:0x0}
2018-07-03 05:22:46.678 UTC [stateleveldb] GetState -> DEBU 8b0 GetState(). ns=mycc, key=b
2018-07-03 05:22:46.679 UTC [statebasedval] validateKVRead -> DEBU 8b1 Comparing versions for key [b]: committed version=&version.Height{BlockNum:0x7, TxNum:0x0} and read version=&version.Height{BlockNum:0x7, TxNum:0x0}
2018-07-03 05:22:46.679 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 8b2 Block [8] Transaction index [0] TxId [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8] marked as valid by state validator
2018-07-03 05:22:46.679 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 8b3 validating rwset...
2018-07-03 05:22:46.679 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 8b4 postprocessing ProtoBlock...
2018-07-03 05:22:46.679 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 8b5 ValidateAndPrepareBatch() complete
2018-07-03 05:22:46.679 UTC [kvledger] CommitWithPvtData -> DEBU 8b6 Channel [mychannel]: Committing block [8] to storage
2018-07-03 05:22:46.682 UTC [pvtdatastorage] Prepare -> DEBU 8b7 Saved 0 private data write sets for block [8]
2018-07-03 05:22:46.684 UTC [fsblkstorage] indexBlock -> DEBU 8b8 Indexing block [blockNum=8, blockHash=[]byte{0xc1, 0x4, 0xfa, 0x6b, 0xb0, 0x49, 0x57, 0xab, 0xb9, 0x47, 0xde, 0x91, 0xc3, 0x11, 0xe5, 0x9, 0x8d, 0x8c, 0xdc, 0x2a, 0x83, 0xd2, 0xca, 0x9d, 0x55, 0x78, 0x10, 0x47, 0x59, 0xd, 0x1d, 0xaa} txOffsets=
txId=ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8 locPointer=offset=70, bytesLength=2968
]
2018-07-03 05:22:46.684 UTC [fsblkstorage] indexBlock -> DEBU 8b9 Adding txLoc [fileSuffixNum=0, offset=75452, bytesLength=2968] for tx ID: [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8] to index
2018-07-03 05:22:46.684 UTC [fsblkstorage] indexBlock -> DEBU 8ba Adding txLoc [fileSuffixNum=0, offset=75452, bytesLength=2968] for tx number:[0] ID: [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8] to blockNumTranNum index
2018-07-03 05:22:46.685 UTC [fsblkstorage] updateCheckpoint -> DEBU 8bb Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[80215], isChainEmpty=[false], lastBlockNumber=[8]
2018-07-03 05:22:46.686 UTC [pvtdatastorage] Commit -> DEBU 8bc Committing private data for block [8]
2018-07-03 05:22:46.686 UTC [pvtdatastorage] Commit -> DEBU 8bd Committed private data for block [8]
2018-07-03 05:22:46.686 UTC [kvledger] CommitWithPvtData -> INFO 8be Channel [mychannel]: Committed block [8] with 1 transaction(s)
2018-07-03 05:22:46.686 UTC [kvledger] CommitWithPvtData -> DEBU 8bf Channel [mychannel]: Committing block [8] transactions to state database
2018-07-03 05:22:46.686 UTC [lockbasedtxmgr] Commit -> DEBU 8c0 Committing updates to state database
2018-07-03 05:22:46.686 UTC [lockbasedtxmgr] Commit -> DEBU 8c1 Write lock acquired for committing updates to state database
2018-07-03 05:22:46.686 UTC [stateleveldb] ApplyUpdates -> DEBU 8c2 Channel [mychannel]: Applying key(string)=[mycca] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x61}]
2018-07-03 05:22:46.686 UTC [stateleveldb] ApplyUpdates -> DEBU 8c3 Channel [mychannel]: Applying key(string)=[myccb] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x62}]
2018-07-03 05:22:46.687 UTC [lockbasedtxmgr] Commit -> DEBU 8c4 Updates committed to state database
2018-07-03 05:22:46.687 UTC [kvledger] CommitWithPvtData -> DEBU 8c5 Channel [mychannel]: Committing block [8] transactions to history database
2018-07-03 05:22:46.687 UTC [historyleveldb] Commit -> DEBU 8c6 Channel [mychannel]: Updating history database for blockNo [8] with [1] transactions
2018-07-03 05:22:46.688 UTC [historyleveldb] Commit -> DEBU 8c7 Channel [mychannel]: Updates committed to history database for blockNo [8]
2018-07-03 05:22:46.688 UTC [eventhub_producer] CreateBlockEvents -> DEBU 8c8 Entry
2018-07-03 05:22:46.688 UTC [eventhub_producer] CreateBlockEvents -> DEBU 8c9 Channel [mychannel]: Block event for block number [8] contains transaction id: ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8
2018-07-03 05:22:46.688 UTC [eventhub_producer] CreateBlockEvents -> DEBU 8ca Exit
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8cb Entry
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8cc Event processor timeout > 0
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8cd Event sent successfully
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8ce Exit
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8cf Entry
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8d0 Event processor timeout > 0
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8d1 Event sent successfully
2018-07-03 05:22:46.688 UTC [eventhub_producer] Send -> DEBU 8d2 Exit

