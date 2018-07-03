2018-07-03 05:22:46.689 UTC [committer/txvalidator] Validate -> DEBU 762 START Block Validation
2018-07-03 05:22:46.689 UTC [committer/txvalidator] Validate -> DEBU 763 expecting 1 block validation responses
2018-07-03 05:22:46.689 UTC [committer/txvalidator] validateTx -> DEBU 764 validateTx starts for block 0xc42267e960 env 0xc421a96f30 txn 0
2018-07-03 05:22:46.689 UTC [protoutils] ValidateTransaction -> DEBU 765 ValidateTransactionEnvelope starts for envelope 0xc421a96f30
2018-07-03 05:22:46.689 UTC [protoutils] ValidateTransaction -> DEBU 766 Header is channel_header:"\010\003\032\014\010\244\220\354\331\005\020\236\232\206\261\002\"\tmychannel*@ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8:\010\022\006\022\004mycc" signature_header:"\n\266\006\n\007Org1MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\n\022\030r'\036\204Ie \277\235\032\306I\237\230 \345H/\267\333\236\312\023\336" 
2018-07-03 05:22:46.689 UTC [protoutils] validateChannelHeader -> DEBU 767 validateChannelHeader info: header type 3
2018-07-03 05:22:46.689 UTC [protoutils] checkSignatureFromCreator -> DEBU 768 begin
2018-07-03 05:22:46.689 UTC [protoutils] checkSignatureFromCreator -> DEBU 769 creator is &{Org1MSP ac67b3a157128c9f7eaf4b0c38e09cef3b66e6664863161de2c42f7549ab5ffb}
2018-07-03 05:22:46.689 UTC [protoutils] checkSignatureFromCreator -> DEBU 76a creator is valid
2018-07-03 05:22:46.689 UTC [protoutils] checkSignatureFromCreator -> DEBU 76b exits successfully
2018-07-03 05:22:46.689 UTC [protoutils] validateEndorserTransaction -> DEBU 76c validateEndorserTransaction starts for data 0xc422d91000, header channel_header:"\010\003\032\014\010\244\220\354\331\005\020\236\232\206\261\002\"\tmychannel*@ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8:\010\022\006\022\004mycc" signature_header:"\n\266\006\n\007Org1MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\n\022\030r'\036\204Ie \277\235\032\306I\237\230 \345H/\267\333\236\312\023\336" 
2018-07-03 05:22:46.689 UTC [protoutils] validateEndorserTransaction -> DEBU 76d validateEndorserTransaction info: there are 1 actions
2018-07-03 05:22:46.689 UTC [protoutils] validateEndorserTransaction -> DEBU 76e validateEndorserTransaction info: signature header is valid
2018-07-03 05:22:46.690 UTC [protoutils] ValidateTransaction -> DEBU 76f ValidateTransactionEnvelope returns err %!s(<nil>)
2018-07-03 05:22:46.690 UTC [committer/txvalidator] validateTx -> DEBU 770 Transaction is for channel mychannel
2018-07-03 05:22:46.690 UTC [fsblkstorage] retrieveTransactionByID -> DEBU 771 retrieveTransactionByID() - txId = [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:46.690 UTC [committer/txvalidator] validateTx -> DEBU 772 Validating transaction vscc tx validate
2018-07-03 05:22:46.690 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 773 VSCCValidateTx starts for env 0xc421a96f30 envbytes 0xc422b04400
2018-07-03 05:22:46.690 UTC [lockbasedtxmgr] newQueryExecutor -> DEBU 774 constructing new query executor txid = [b41f2201-f34e-4160-9791-fc0784652b65]
2018-07-03 05:22:46.690 UTC [stateleveldb] GetState -> DEBU 775 GetState(). ns=lscc, key=mycc
2018-07-03 05:22:46.690 UTC [lockbasedtxmgr] Done -> DEBU 776 Done with transaction simulation / query execution [b41f2201-f34e-4160-9791-fc0784652b65]
2018-07-03 05:22:46.690 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 777 VSCCValidateTxForCC starts for envbytes 0xc422b04400
2018-07-03 05:22:46.690 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 778 constructing new tx simulator
2018-07-03 05:22:46.690 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 779 constructing new tx simulator txid = [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:46.690 UTC [ccprovider] NewCCContext -> DEBU 77a NewCCCC (chain=mychannel,chaincode=vscc,version=1.1.1-snapshot-ff5e861,txid=f758ac70-e1f7-40c4-9d70-73039a724f2c,syscc=true,proposal=0x0,canname=vscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:46.690 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 77b Invoking VSCC txid ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8 chaindID mychannel
2018-07-03 05:22:46.690 UTC [chaincode] Launch -> DEBU 77c chaincode is running(no need to launch) : vscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:46.690 UTC [chaincode] Execute -> DEBU 77d Entry
2018-07-03 05:22:46.690 UTC [chaincode] Execute -> DEBU 77e chaincode canonical name: vscc:1.1.1-snapshot-ff5e861
2018-07-03 05:22:46.690 UTC [chaincode] sendExecuteMessage -> DEBU 77f [f758ac70]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 05:22:46.690 UTC [chaincode] setChaincodeProposal -> DEBU 780 Setting chaincode proposal context...
2018-07-03 05:22:46.690 UTC [chaincode] sendExecuteMessage -> DEBU 781 [f758ac70]sendExecuteMsg trigger event TRANSACTION
2018-07-03 05:22:46.690 UTC [chaincode] processStream -> DEBU 782 [f758ac70]Move state message TRANSACTION
2018-07-03 05:22:46.690 UTC [chaincode] handleMessage -> DEBU 783 [f758ac70]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 05:22:46.690 UTC [chaincode] filterError -> DEBU 784 Ignoring NoTransitionError: no transition
2018-07-03 05:22:46.690 UTC [chaincode] processStream -> DEBU 785 [f758ac70]sending state message TRANSACTION
2018-07-03 05:22:46.690 UTC [shim] func1 -> DEBU 786 [f758ac70]Received message TRANSACTION from shim
2018-07-03 05:22:46.690 UTC [shim] handleMessage -> DEBU 787 [f758ac70]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 05:22:46.690 UTC [shim] beforeTransaction -> DEBU 788 [f758ac70]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 05:22:46.690 UTC [vscc] Invoke -> DEBU 789 VSCC invoked
2018-07-03 05:22:46.690 UTC [vscc] deduplicateIdentity -> DEBU 78a Signature set is of size 1 out of 1 endorsement(s)
2018-07-03 05:22:46.690 UTC [vscc] Invoke -> DEBU 78b VSCC exists successfully
2018-07-03 05:22:46.690 UTC [shim] func1 -> DEBU 78c [f758ac70]Transaction completed. Sending COMPLETED
2018-07-03 05:22:46.690 UTC [shim] func1 -> DEBU 78d [f758ac70]Move state message COMPLETED
2018-07-03 05:22:46.690 UTC [shim] handleMessage -> DEBU 78e [f758ac70]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 05:22:46.690 UTC [shim] func1 -> DEBU 78f [f758ac70]send state message COMPLETED
2018-07-03 05:22:46.690 UTC [chaincode] processStream -> DEBU 790 [f758ac70]Received message COMPLETED from shim
2018-07-03 05:22:46.690 UTC [chaincode] handleMessage -> DEBU 791 [f758ac70]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 05:22:46.690 UTC [chaincode] handleMessage -> DEBU 792 [f758ac70-e1f7-40c4-9d70-73039a724f2c]HandleMessage- COMPLETED. Notify
2018-07-03 05:22:46.690 UTC [chaincode] notify -> DEBU 793 notifying Txid:f758ac70-e1f7-40c4-9d70-73039a724f2c, channelID:mychannel
2018-07-03 05:22:46.690 UTC [chaincode] Execute -> DEBU 794 Exit
2018-07-03 05:22:46.691 UTC [lockbasedtxmgr] Done -> DEBU 795 Done with transaction simulation / query execution [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8]
2018-07-03 05:22:46.691 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 796 VSCCValidateTxForCC completes for envbytes 0xc422b04400
2018-07-03 05:22:46.691 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 797 VSCCValidateTx completes for env 0xc421a96f30 envbytes 0xc422b04400
2018-07-03 05:22:46.691 UTC [committer/txvalidator] validateTx -> DEBU 798 validateTx completes for block 0xc42267e960 env 0xc421a96f30 txn 0
2018-07-03 05:22:46.691 UTC [committer/txvalidator] Validate -> DEBU 799 got result for idx 0, code 0
2018-07-03 05:22:46.691 UTC [committer/txvalidator] Validate -> DEBU 79a END Block Validation
2018-07-03 05:22:46.691 UTC [kvledger] CommitWithPvtData -> DEBU 79b Channel [mychannel]: Validating state for block [8]
2018-07-03 05:22:46.691 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 79c Validating new block with num trans = [1]
2018-07-03 05:22:46.691 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 79d ValidateAndPrepareBatch() for block number = [8]
2018-07-03 05:22:46.691 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 79e preprocessing ProtoBlock...
2018-07-03 05:22:46.691 UTC [valimpl] preprocessProtoBlock -> DEBU 79f txType=ENDORSER_TRANSACTION
2018-07-03 05:22:46.691 UTC [stateleveldb] GetState -> DEBU 7a0 GetState(). ns=lscc, key=mycc
2018-07-03 05:22:46.691 UTC [statebasedval] validateKVRead -> DEBU 7a1 Comparing versions for key [mycc]: committed version=&version.Height{BlockNum:0x3, TxNum:0x0} and read version=&version.Height{BlockNum:0x3, TxNum:0x0}
2018-07-03 05:22:46.691 UTC [stateleveldb] GetState -> DEBU 7a2 GetState(). ns=mycc, key=a
2018-07-03 05:22:46.691 UTC [statebasedval] validateKVRead -> DEBU 7a3 Comparing versions for key [a]: committed version=&version.Height{BlockNum:0x7, TxNum:0x0} and read version=&version.Height{BlockNum:0x7, TxNum:0x0}
2018-07-03 05:22:46.691 UTC [stateleveldb] GetState -> DEBU 7a4 GetState(). ns=mycc, key=b
2018-07-03 05:22:46.691 UTC [statebasedval] validateKVRead -> DEBU 7a5 Comparing versions for key [b]: committed version=&version.Height{BlockNum:0x7, TxNum:0x0} and read version=&version.Height{BlockNum:0x7, TxNum:0x0}
2018-07-03 05:22:46.691 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 7a6 Block [8] Transaction index [0] TxId [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8] marked as valid by state validator
2018-07-03 05:22:46.691 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 7a7 validating rwset...
2018-07-03 05:22:46.691 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 7a8 postprocessing ProtoBlock...
2018-07-03 05:22:46.691 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 7a9 ValidateAndPrepareBatch() complete
2018-07-03 05:22:46.691 UTC [kvledger] CommitWithPvtData -> DEBU 7aa Channel [mychannel]: Committing block [8] to storage
2018-07-03 05:22:46.692 UTC [pvtdatastorage] Prepare -> DEBU 7ab Saved 0 private data write sets for block [8]
2018-07-03 05:22:46.695 UTC [fsblkstorage] indexBlock -> DEBU 7ac Indexing block [blockNum=8, blockHash=[]byte{0xc1, 0x4, 0xfa, 0x6b, 0xb0, 0x49, 0x57, 0xab, 0xb9, 0x47, 0xde, 0x91, 0xc3, 0x11, 0xe5, 0x9, 0x8d, 0x8c, 0xdc, 0x2a, 0x83, 0xd2, 0xca, 0x9d, 0x55, 0x78, 0x10, 0x47, 0x59, 0xd, 0x1d, 0xaa} txOffsets=
txId=ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8 locPointer=offset=70, bytesLength=2968
]
2018-07-03 05:22:46.695 UTC [fsblkstorage] indexBlock -> DEBU 7ad Adding txLoc [fileSuffixNum=0, offset=75452, bytesLength=2968] for tx ID: [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8] to index
2018-07-03 05:22:46.695 UTC [fsblkstorage] indexBlock -> DEBU 7ae Adding txLoc [fileSuffixNum=0, offset=75452, bytesLength=2968] for tx number:[0] ID: [ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8] to blockNumTranNum index
2018-07-03 05:22:46.700 UTC [fsblkstorage] updateCheckpoint -> DEBU 7af Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[80215], isChainEmpty=[false], lastBlockNumber=[8]
2018-07-03 05:22:46.701 UTC [pvtdatastorage] Commit -> DEBU 7b0 Committing private data for block [8]
2018-07-03 05:22:46.702 UTC [pvtdatastorage] Commit -> DEBU 7b1 Committed private data for block [8]
2018-07-03 05:22:46.702 UTC [kvledger] CommitWithPvtData -> INFO 7b2 Channel [mychannel]: Committed block [8] with 1 transaction(s)
2018-07-03 05:22:46.702 UTC [kvledger] CommitWithPvtData -> DEBU 7b3 Channel [mychannel]: Committing block [8] transactions to state database
2018-07-03 05:22:46.702 UTC [lockbasedtxmgr] Commit -> DEBU 7b4 Committing updates to state database
2018-07-03 05:22:46.702 UTC [lockbasedtxmgr] Commit -> DEBU 7b5 Write lock acquired for committing updates to state database
2018-07-03 05:22:46.702 UTC [stateleveldb] ApplyUpdates -> DEBU 7b6 Channel [mychannel]: Applying key(string)=[myccb] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x62}]
2018-07-03 05:22:46.702 UTC [stateleveldb] ApplyUpdates -> DEBU 7b7 Channel [mychannel]: Applying key(string)=[mycca] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x61}]
2018-07-03 05:22:46.702 UTC [lockbasedtxmgr] Commit -> DEBU 7b8 Updates committed to state database
2018-07-03 05:22:46.703 UTC [kvledger] CommitWithPvtData -> DEBU 7b9 Channel [mychannel]: Committing block [8] transactions to history database
2018-07-03 05:22:46.703 UTC [historyleveldb] Commit -> DEBU 7ba Channel [mychannel]: Updating history database for blockNo [8] with [1] transactions
2018-07-03 05:22:46.703 UTC [historyleveldb] Commit -> DEBU 7bb Channel [mychannel]: Updates committed to history database for blockNo [8]
2018-07-03 05:22:46.703 UTC [eventhub_producer] CreateBlockEvents -> DEBU 7bc Entry
2018-07-03 05:22:46.704 UTC [eventhub_producer] CreateBlockEvents -> DEBU 7bd Channel [mychannel]: Block event for block number [8] contains transaction id: ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8
2018-07-03 05:22:46.704 UTC [eventhub_producer] CreateBlockEvents -> DEBU 7be Exit
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7bf Entry
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c0 Event processor timeout > 0
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c1 Event sent successfully
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c2 Exit
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c3 Entry
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c4 Event processor timeout > 0
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c5 Event sent successfully
2018-07-03 05:22:46.704 UTC [eventhub_producer] Send -> DEBU 7c6 Exit

