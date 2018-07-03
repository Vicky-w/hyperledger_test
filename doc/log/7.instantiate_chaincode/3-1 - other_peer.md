2018-07-03 02:34:19.754 UTC [committer/txvalidator] Validate -> DEBU 55c START Block Validation
2018-07-03 02:34:19.755 UTC [committer/txvalidator] Validate -> DEBU 55d expecting 1 block validation responses
2018-07-03 02:34:19.755 UTC [committer/txvalidator] validateTx -> DEBU 55e validateTx starts for block 0xc422868ac0 env 0xc422162480 txn 0
2018-07-03 02:34:19.755 UTC [protoutils] ValidateTransaction -> DEBU 55f ValidateTransactionEnvelope starts for envelope 0xc422162480
2018-07-03 02:34:19.759 UTC [protoutils] ValidateTransaction -> DEBU 560 Header is channel_header:"\010\003\032\014\010\240\301\353\331\005\020\272\267\241\324\001\"\tmychannel*@3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c:\010\022\006\022\004lscc" signature_header:"\n\266\006\n\007Org2MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\n\022\030\007\336\036\002\232I\007\350\372\370MW\017$\375M\332\0376\020\346X\337m" 
2018-07-03 02:34:19.763 UTC [protoutils] validateChannelHeader -> DEBU 561 validateChannelHeader info: header type 3
2018-07-03 02:34:19.763 UTC [protoutils] checkSignatureFromCreator -> DEBU 562 begin
2018-07-03 02:34:19.764 UTC [protoutils] checkSignatureFromCreator -> DEBU 563 creator is &{Org2MSP f1f73cc30a2def8068a36dae53ea9655fffea3e6b7aa128a1ae3b9ba1ed344b9}
2018-07-03 02:34:19.764 UTC [protoutils] checkSignatureFromCreator -> DEBU 564 creator is valid
2018-07-03 02:34:19.764 UTC [protoutils] checkSignatureFromCreator -> DEBU 565 exits successfully
2018-07-03 02:34:19.764 UTC [protoutils] validateEndorserTransaction -> DEBU 566 validateEndorserTransaction starts for data 0xc420308a80, header channel_header:"\010\003\032\014\010\240\301\353\331\005\020\272\267\241\324\001\"\tmychannel*@3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c:\010\022\006\022\004lscc" signature_header:"\n\266\006\n\007Org2MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\n\022\030\007\336\036\002\232I\007\350\372\370MW\017$\375M\332\0376\020\346X\337m" 
2018-07-03 02:34:19.765 UTC [protoutils] validateEndorserTransaction -> DEBU 567 validateEndorserTransaction info: there are 1 actions
2018-07-03 02:34:19.765 UTC [protoutils] validateEndorserTransaction -> DEBU 568 validateEndorserTransaction info: signature header is valid
2018-07-03 02:34:19.766 UTC [protoutils] ValidateTransaction -> DEBU 569 ValidateTransactionEnvelope returns err %!s(<nil>)
2018-07-03 02:34:19.766 UTC [committer/txvalidator] validateTx -> DEBU 56a Transaction is for channel mychannel
2018-07-03 02:34:19.767 UTC [fsblkstorage] retrieveTransactionByID -> DEBU 56b retrieveTransactionByID() - txId = [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:19.767 UTC [committer/txvalidator] validateTx -> DEBU 56c Validating transaction vscc tx validate
2018-07-03 02:34:19.767 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 56d VSCCValidateTx starts for env 0xc422162480 envbytes 0xc42286a000
2018-07-03 02:34:19.768 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 56e VSCCValidateTxForCC starts for envbytes 0xc42286a000
2018-07-03 02:34:19.768 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 56f constructing new tx simulator
2018-07-03 02:34:19.768 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 570 constructing new tx simulator txid = [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:19.768 UTC [ccprovider] NewCCContext -> DEBU 571 NewCCCC (chain=mychannel,chaincode=vscc,version=1.1.1-snapshot-ff5e861,txid=fa99d32a-f755-417d-8e3c-bcde094a4f80,syscc=true,proposal=0x0,canname=vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:19.768 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 572 Invoking VSCC txid 3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c chaindID mychannel
2018-07-03 02:34:19.768 UTC [chaincode] Launch -> DEBU 573 chaincode is running(no need to launch) : vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:19.768 UTC [chaincode] Execute -> DEBU 574 Entry
2018-07-03 02:34:19.768 UTC [chaincode] Execute -> DEBU 575 chaincode canonical name: vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:19.769 UTC [chaincode] sendExecuteMessage -> DEBU 576 [fa99d32a]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 02:34:19.770 UTC [chaincode] setChaincodeProposal -> DEBU 577 Setting chaincode proposal context...
2018-07-03 02:34:19.770 UTC [chaincode] sendExecuteMessage -> DEBU 578 [fa99d32a]sendExecuteMsg trigger event TRANSACTION
2018-07-03 02:34:19.770 UTC [chaincode] processStream -> DEBU 579 [fa99d32a]Move state message TRANSACTION
2018-07-03 02:34:19.770 UTC [chaincode] handleMessage -> DEBU 57a [fa99d32a]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 02:34:19.770 UTC [chaincode] filterError -> DEBU 57b Ignoring NoTransitionError: no transition
2018-07-03 02:34:19.770 UTC [chaincode] processStream -> DEBU 57c [fa99d32a]sending state message TRANSACTION
2018-07-03 02:34:19.771 UTC [shim] func1 -> DEBU 57d [fa99d32a]Received message TRANSACTION from shim
2018-07-03 02:34:19.771 UTC [shim] handleMessage -> DEBU 57e [fa99d32a]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 02:34:19.771 UTC [shim] beforeTransaction -> DEBU 57f [fa99d32a]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 02:34:19.771 UTC [vscc] Invoke -> DEBU 580 VSCC invoked
2018-07-03 02:34:19.771 UTC [vscc] deduplicateIdentity -> DEBU 581 Signature set is of size 1 out of 1 endorsement(s)
2018-07-03 02:34:19.772 UTC [vscc] Invoke -> DEBU 582 VSCC info: doing special validation for LSCC
2018-07-03 02:34:19.772 UTC [vscc] ValidateLSCCInvocation -> DEBU 583 VSCC info: ValidateLSCCInvocation acting on deploy [][]uint8{[]uint8{0x6d, 0x79, 0x63, 0x68, 0x61, 0x6e, 0x6e, 0x65, 0x6c}, []uint8{0xa, 0x27, 0x8, 0x1, 0x12, 0xb, 0x12, 0x4, 0x6d, 0x79, 0x63, 0x63, 0x1a, 0x3, 0x31, 0x2e, 0x30, 0x1a, 0x16, 0xa, 0x4, 0x69, 0x6e, 0x69, 0x74, 0xa, 0x1, 0x61, 0xa, 0x3, 0x31, 0x30, 0x30, 0xa, 0x1, 0x62, 0xa, 0x3, 0x32, 0x30, 0x30}, []uint8{0x12, 0xc, 0x12, 0xa, 0x8, 0x1, 0x12, 0x2, 0x8, 0x0, 0x12, 0x2, 0x8, 0x1, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x31, 0x4d, 0x53, 0x50, 0x10, 0x3, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x32, 0x4d, 0x53, 0x50, 0x10, 0x3}, []uint8{0x65, 0x73, 0x63, 0x63}, []uint8{0x76, 0x73, 0x63, 0x63}}
2018-07-03 02:34:19.772 UTC [vscc] ValidateLSCCInvocation -> DEBU 584 VSCC info: validating invocation of lscc function deploy on arguments [][]uint8{[]uint8{0x6d, 0x79, 0x63, 0x68, 0x61, 0x6e, 0x6e, 0x65, 0x6c}, []uint8{0xa, 0x27, 0x8, 0x1, 0x12, 0xb, 0x12, 0x4, 0x6d, 0x79, 0x63, 0x63, 0x1a, 0x3, 0x31, 0x2e, 0x30, 0x1a, 0x16, 0xa, 0x4, 0x69, 0x6e, 0x69, 0x74, 0xa, 0x1, 0x61, 0xa, 0x3, 0x31, 0x30, 0x30, 0xa, 0x1, 0x62, 0xa, 0x3, 0x32, 0x30, 0x30}, []uint8{0x12, 0xc, 0x12, 0xa, 0x8, 0x1, 0x12, 0x2, 0x8, 0x0, 0x12, 0x2, 0x8, 0x1, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x31, 0x4d, 0x53, 0x50, 0x10, 0x3, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x32, 0x4d, 0x53, 0x50, 0x10, 0x3}, []uint8{0x65, 0x73, 0x63, 0x63}, []uint8{0x76, 0x73, 0x63, 0x63}}
2018-07-03 02:34:19.772 UTC [vscc] ValidateLSCCInvocation -> DEBU 585 Namespace lscc
2018-07-03 02:34:19.772 UTC [lockbasedtxmgr] newQueryExecutor -> DEBU 586 constructing new query executor txid = [32bc14b6-e8d2-4264-b875-3099cbc9ccf3]
2018-07-03 02:34:19.774 UTC [stateleveldb] GetState -> DEBU 587 GetState(). ns=lscc, key=mycc
2018-07-03 02:34:19.774 UTC [lockbasedtxmgr] Done -> DEBU 588 Done with transaction simulation / query execution [32bc14b6-e8d2-4264-b875-3099cbc9ccf3]
2018-07-03 02:34:19.774 UTC [vscc] ValidateLSCCInvocation -> DEBU 589 Validating deploy for cc mycc version 1.0
2018-07-03 02:34:19.774 UTC [vscc] checkInstantiationPolicy -> DEBU 58a VSCC info: checkInstantiationPolicy starts, policy is &cauthdsl.policy{evaluator:(func([]*common.SignedData, []bool) bool)(0x988790), deserializer:(*mgmt.mspMgmtMgr)(0xc421b49660)}
2018-07-03 02:34:19.774 UTC [vscc] Invoke -> DEBU 58b VSCC exists successfully
2018-07-03 02:34:19.774 UTC [shim] func1 -> DEBU 58c [fa99d32a]Transaction completed. Sending COMPLETED
2018-07-03 02:34:19.774 UTC [shim] func1 -> DEBU 58d [fa99d32a]Move state message COMPLETED
2018-07-03 02:34:19.774 UTC [shim] handleMessage -> DEBU 58e [fa99d32a]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:34:19.774 UTC [shim] func1 -> DEBU 58f [fa99d32a]send state message COMPLETED
2018-07-03 02:34:19.774 UTC [chaincode] processStream -> DEBU 590 [fa99d32a]Received message COMPLETED from shim
2018-07-03 02:34:19.774 UTC [chaincode] handleMessage -> DEBU 591 [fa99d32a]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:34:19.774 UTC [chaincode] handleMessage -> DEBU 592 [fa99d32a-f755-417d-8e3c-bcde094a4f80]HandleMessage- COMPLETED. Notify
2018-07-03 02:34:19.775 UTC [chaincode] notify -> DEBU 593 notifying Txid:fa99d32a-f755-417d-8e3c-bcde094a4f80, channelID:mychannel
2018-07-03 02:34:19.775 UTC [chaincode] Execute -> DEBU 594 Exit
2018-07-03 02:34:19.775 UTC [lockbasedtxmgr] Done -> DEBU 595 Done with transaction simulation / query execution [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:19.775 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 596 VSCCValidateTxForCC completes for envbytes 0xc42286a000
2018-07-03 02:34:19.776 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 597 VSCCValidateTx completes for env 0xc422162480 envbytes 0xc42286a000
2018-07-03 02:34:19.776 UTC [committer/txvalidator] validateTx -> DEBU 598 validateTx completes for block 0xc422868ac0 env 0xc422162480 txn 0
2018-07-03 02:34:19.776 UTC [committer/txvalidator] Validate -> DEBU 599 got result for idx 0, code 0
2018-07-03 02:34:19.776 UTC [committer/txvalidator] Validate -> DEBU 59a END Block Validation
2018-07-03 02:34:19.777 UTC [kvledger] CommitWithPvtData -> DEBU 59b Channel [mychannel]: Validating state for block [3]
2018-07-03 02:34:19.777 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 59c Validating new block with num trans = [1]
2018-07-03 02:34:19.777 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 59d ValidateAndPrepareBatch() for block number = [3]
2018-07-03 02:34:19.777 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 59e preprocessing ProtoBlock...
2018-07-03 02:34:19.777 UTC [valimpl] preprocessProtoBlock -> DEBU 59f txType=ENDORSER_TRANSACTION
2018-07-03 02:34:19.777 UTC [stateleveldb] GetState -> DEBU 5a0 GetState(). ns=lscc, key=mycc
2018-07-03 02:34:19.777 UTC [statebasedval] validateKVRead -> DEBU 5a1 Comparing versions for key [mycc]: committed version=(*version.Height)(nil) and read version=(*version.Height)(nil)
2018-07-03 02:34:19.777 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 5a2 Block [3] Transaction index [0] TxId [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c] marked as valid by state validator
2018-07-03 02:34:19.777 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 5a3 validating rwset...
2018-07-03 02:34:19.777 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 5a4 postprocessing ProtoBlock...
2018-07-03 02:34:19.777 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 5a5 ValidateAndPrepareBatch() complete
2018-07-03 02:34:19.777 UTC [lockbasedtxmgr] invokeNamespaceListeners -> DEBU 5a6 Invoking listener for state changes over namespace:lscc
2018-07-03 02:34:19.777 UTC [cceventmgmt] HandleStateUpdates -> DEBU 5a7 Channel [mychannel]: Handling state updates in LSCC namespace - stateUpdates=[]*kvrwset.KVWrite{(*kvrwset.KVWrite)(0xc421e02780)}
2018-07-03 02:34:19.777 UTC [cceventmgmt] HandleStateUpdates -> INFO 5a8 Channel [mychannel]: Handling LSCC state update for chaincode [mycc]
2018-07-03 02:34:19.777 UTC [cceventmgmt] HandleChaincodeDeploy -> DEBU 5a9 Channel [mychannel]: Handling chaincode deploy event for chaincode [[Name=mycc, Version=1.0, Hash=[]byte{0x47, 0x6f, 0xca, 0x1a, 0x94, 0x92, 0x74, 0x0, 0x19, 0x71, 0xf1, 0xec, 0x28, 0x36, 0xcb, 0x9, 0x32, 0x1f, 0xb, 0x71, 0x26, 0x8b, 0x37, 0x62, 0xd6, 0x89, 0x31, 0xc9, 0x3f, 0x21, 0x81, 0x34}]]
2018-07-03 02:34:19.778 UTC [ccprovider] ExtractStatedbArtifactsForChaincode -> INFO 5aa Error while loading installation package for ccname=%s, ccversion=%s. Err=%s mycc 1.0 open /var/hyperledger/production/chaincodes/mycc.1.0: no such file or directory
2018-07-03 02:34:19.778 UTC [cceventmgmt] HandleChaincodeDeploy -> INFO 5ab Channel [mychannel]: Chaincode [Name=mycc, Version=1.0, Hash=[]byte{0x47, 0x6f, 0xca, 0x1a, 0x94, 0x92, 0x74, 0x0, 0x19, 0x71, 0xf1, 0xec, 0x28, 0x36, 0xcb, 0x9, 0x32, 0x1f, 0xb, 0x71, 0x26, 0x8b, 0x37, 0x62, 0xd6, 0x89, 0x31, 0xc9, 0x3f, 0x21, 0x81, 0x34}] is not installed hence no need to create chaincode artifacts for endorsement
2018-07-03 02:34:19.780 UTC [kvledger] CommitWithPvtData -> DEBU 5ac Channel [mychannel]: Committing block [3] to storage
2018-07-03 02:34:19.782 UTC [pvtdatastorage] Prepare -> DEBU 5ad Saved 0 private data write sets for block [3]
2018-07-03 02:34:19.787 UTC [fsblkstorage] indexBlock -> DEBU 5ae Indexing block [blockNum=3, blockHash=[]byte{0x1f, 0x6f, 0xfe, 0x4d, 0x3d, 0x11, 0x9f, 0xa0, 0x86, 0x6b, 0xf3, 0x64, 0x19, 0x4d, 0x16, 0x44, 0x9c, 0x9e, 0x43, 0xa4, 0xc4, 0x70, 0xde, 0xef, 0x8, 0x60, 0xcb, 0xa2, 0x3e, 0xac, 0xb7, 0x96} txOffsets=
txId=3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c locPointer=offset=70, bytesLength=3526
]
2018-07-03 02:34:19.787 UTC [fsblkstorage] indexBlock -> DEBU 5af Adding txLoc [fileSuffixNum=0, offset=50731, bytesLength=3526] for tx ID: [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c] to index
2018-07-03 02:34:19.787 UTC [fsblkstorage] indexBlock -> DEBU 5b0 Adding txLoc [fileSuffixNum=0, offset=50731, bytesLength=3526] for tx number:[0] ID: [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c] to blockNumTranNum index
2018-07-03 02:34:19.789 UTC [fsblkstorage] updateCheckpoint -> DEBU 5b1 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[56051], isChainEmpty=[false], lastBlockNumber=[3]
2018-07-03 02:34:19.789 UTC [pvtdatastorage] Commit -> DEBU 5b2 Committing private data for block [3]
2018-07-03 02:34:19.792 UTC [pvtdatastorage] Commit -> DEBU 5b3 Committed private data for block [3]
2018-07-03 02:34:19.792 UTC [kvledger] CommitWithPvtData -> INFO 5b4 Channel [mychannel]: Committed block [3] with 1 transaction(s)
2018-07-03 02:34:19.792 UTC [kvledger] CommitWithPvtData -> DEBU 5b5 Channel [mychannel]: Committing block [3] transactions to state database
2018-07-03 02:34:19.792 UTC [lockbasedtxmgr] Commit -> DEBU 5b6 Committing updates to state database
2018-07-03 02:34:19.792 UTC [lockbasedtxmgr] Commit -> DEBU 5b7 Write lock acquired for committing updates to state database
2018-07-03 02:34:19.792 UTC [stateleveldb] ApplyUpdates -> DEBU 5b8 Channel [mychannel]: Applying key(string)=[lsccmycc] key(bytes)=[[]byte{0x6c, 0x73, 0x63, 0x63, 0x0, 0x6d, 0x79, 0x63, 0x63}]
2018-07-03 02:34:19.792 UTC [stateleveldb] ApplyUpdates -> DEBU 5b9 Channel [mychannel]: Applying key(string)=[mycca] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x61}]
2018-07-03 02:34:19.792 UTC [stateleveldb] ApplyUpdates -> DEBU 5ba Channel [mychannel]: Applying key(string)=[myccb] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x62}]
2018-07-03 02:34:19.793 UTC [lockbasedtxmgr] Commit -> DEBU 5bb Updates committed to state database
2018-07-03 02:34:19.794 UTC [kvledger] CommitWithPvtData -> DEBU 5bc Channel [mychannel]: Committing block [3] transactions to history database
2018-07-03 02:34:19.794 UTC [historyleveldb] Commit -> DEBU 5bd Channel [mychannel]: Updating history database for blockNo [3] with [1] transactions
2018-07-03 02:34:19.797 UTC [historyleveldb] Commit -> DEBU 5be Channel [mychannel]: Updates committed to history database for blockNo [3]
2018-07-03 02:34:19.797 UTC [eventhub_producer] CreateBlockEvents -> DEBU 5bf Entry
2018-07-03 02:34:19.797 UTC [eventhub_producer] CreateBlockEvents -> DEBU 5c0 Channel [mychannel]: Block event for block number [3] contains transaction id: 3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c
2018-07-03 02:34:19.797 UTC [eventhub_producer] CreateBlockEvents -> DEBU 5c1 Exit
2018-07-03 02:34:19.797 UTC [eventhub_producer] Send -> DEBU 5c2 Entry
2018-07-03 02:34:19.797 UTC [eventhub_producer] Send -> DEBU 5c3 Event processor timeout > 0
2018-07-03 02:34:19.797 UTC [eventhub_producer] Send -> DEBU 5c4 Event sent successfully
2018-07-03 02:34:19.797 UTC [eventhub_producer] Send -> DEBU 5c5 Exit
2018-07-03 02:34:19.797 UTC [eventhub_producer] Send -> DEBU 5c6 Entry
2018-07-03 02:34:19.797 UTC [eventhub_producer] Send -> DEBU 5c7 Event processor timeout > 0
2018-07-03 02:34:19.798 UTC [eventhub_producer] Send -> DEBU 5c8 Event sent successfully
2018-07-03 02:34:19.798 UTC [eventhub_producer] Send -> DEBU 5c9 Exit

