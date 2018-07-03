2018-07-03 02:34:17.074 UTC [dockercontroller] deployImage -> DEBU 5fe Created image: dev-peer0.org2.example.com-mycc-1.0-15b571b3ce849066b7ec74497da3b27e54e0df1345daff3951b94245ce09c42b
2018-07-03 02:34:17.076 UTC [dockercontroller] Start -> DEBU 5ff start-recreated image successfully
2018-07-03 02:34:17.077 UTC [dockercontroller] createContainer -> DEBU 600 Create container: dev-peer0.org2.example.com-mycc-1.0
2018-07-03 02:34:17.141 UTC [dockercontroller] createContainer -> DEBU 601 Created container: dev-peer0.org2.example.com-mycc-1.0-15b571b3ce849066b7ec74497da3b27e54e0df1345daff3951b94245ce09c42b
2018-07-03 02:34:17.617 UTC [dockercontroller] Start -> DEBU 602 Started container dev-peer0.org2.example.com-mycc-1.0
2018-07-03 02:34:17.618 UTC [container] unlockContainer -> DEBU 603 container lock deleted(dev-peer0.org2.example.com-mycc-1.0)
2018-07-03 02:34:17.660 UTC [accessControl] authenticate -> DEBU 604 Chaincode mycc:1.0 's authentication is authorized
2018-07-03 02:34:17.660 UTC [chaincode] HandleChaincodeStream -> DEBU 605 Current context deadline = 0001-01-01 00:00:00 +0000 UTC, ok = false
2018-07-03 02:34:17.661 UTC [chaincode] processStream -> DEBU 606 []Received message REGISTER from shim
2018-07-03 02:34:17.661 UTC [chaincode] handleMessage -> DEBU 607 []Fabric side Handling ChaincodeMessage of type: REGISTER in state created
2018-07-03 02:34:17.662 UTC [chaincode] beforeRegisterEvent -> DEBU 608 Received REGISTER in state created
2018-07-03 02:34:17.662 UTC [chaincode] registerHandler -> DEBU 609 registered handler complete for chaincode mycc:1.0
2018-07-03 02:34:17.662 UTC [chaincode] beforeRegisterEvent -> DEBU 60a Got REGISTER for chaincodeID = name:"mycc:1.0" , sending back REGISTERED
2018-07-03 02:34:17.663 UTC [chaincode] notifyDuringStartup -> DEBU 60b Notifying during startup
2018-07-03 02:34:17.663 UTC [chaincode] func1 -> DEBU 60c chaincode mycc:1.0 launch seq completed
2018-07-03 02:34:17.663 UTC [chaincode] ready -> DEBU 60d sending READY
2018-07-03 02:34:17.663 UTC [chaincode] setChaincodeProposal -> DEBU 60e Setting chaincode proposal context...
2018-07-03 02:34:17.663 UTC [chaincode] setChaincodeProposal -> DEBU 60f Proposal different from nil. Creating chaincode proposal context...
2018-07-03 02:34:17.663 UTC [chaincode] processStream -> DEBU 610 [3c7ea620]Move state message READY
2018-07-03 02:34:17.663 UTC [chaincode] handleMessage -> DEBU 611 [3c7ea620]Fabric side Handling ChaincodeMessage of type: READY in state established
2018-07-03 02:34:17.663 UTC [chaincode] enterReadyState -> DEBU 612 [3c7ea620]Entered state ready
2018-07-03 02:34:17.663 UTC [chaincode] notify -> DEBU 613 notifying Txid:3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c, channelID:mychannel
2018-07-03 02:34:17.663 UTC [chaincode] processStream -> DEBU 614 [3c7ea620]sending state message READY
2018-07-03 02:34:17.663 UTC [chaincode] Launch -> DEBU 615 sending init completed
2018-07-03 02:34:17.663 UTC [chaincode] Launch -> DEBU 616 LaunchChaincode complete
2018-07-03 02:34:17.663 UTC [chaincode] Execute -> DEBU 617 Entry
2018-07-03 02:34:17.663 UTC [chaincode] Execute -> DEBU 618 chaincode canonical name: mycc:1.0
2018-07-03 02:34:17.663 UTC [chaincode] sendExecuteMessage -> DEBU 619 [3c7ea620]Inside sendExecuteMessage. Message INIT
2018-07-03 02:34:17.663 UTC [chaincode] setChaincodeProposal -> DEBU 61a Setting chaincode proposal context...
2018-07-03 02:34:17.663 UTC [chaincode] setChaincodeProposal -> DEBU 61b Proposal different from nil. Creating chaincode proposal context...
2018-07-03 02:34:17.663 UTC [chaincode] sendExecuteMessage -> DEBU 61c [3c7ea620]sendExecuteMsg trigger event INIT
2018-07-03 02:34:17.663 UTC [chaincode] processStream -> DEBU 61d [3c7ea620]Move state message INIT
2018-07-03 02:34:17.663 UTC [chaincode] handleMessage -> DEBU 61e [3c7ea620]Fabric side Handling ChaincodeMessage of type: INIT in state ready
2018-07-03 02:34:17.663 UTC [chaincode] filterError -> DEBU 61f Ignoring NoTransitionError: no transition
2018-07-03 02:34:17.663 UTC [chaincode] processStream -> DEBU 620 [3c7ea620]sending state message INIT
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 621 [3c7ea620]Received message PUT_STATE from shim
2018-07-03 02:34:17.664 UTC [chaincode] handleMessage -> DEBU 622 [3c7ea620]Fabric side Handling ChaincodeMessage of type: PUT_STATE in state ready
2018-07-03 02:34:17.664 UTC [chaincode] filterError -> DEBU 623 Ignoring NoTransitionError: no transition
2018-07-03 02:34:17.664 UTC [chaincode] func1 -> DEBU 624 [3c7ea620]state is ready
2018-07-03 02:34:17.664 UTC [chaincode] func1 -> DEBU 625 [3c7ea620]Completed PUT_STATE. Sending RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] 1 -> DEBU 626 [3c7ea620]enterBusyState trigger event RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 627 [3c7ea620]Move state message RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] handleMessage -> DEBU 628 [3c7ea620]Fabric side Handling ChaincodeMessage of type: RESPONSE in state ready
2018-07-03 02:34:17.664 UTC [chaincode] filterError -> DEBU 629 Ignoring NoTransitionError: no transition
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 62a [3c7ea620]sending state message RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 62b [3c7ea620]Received message PUT_STATE from shim
2018-07-03 02:34:17.664 UTC [chaincode] handleMessage -> DEBU 62c [3c7ea620]Fabric side Handling ChaincodeMessage of type: PUT_STATE in state ready
2018-07-03 02:34:17.664 UTC [chaincode] filterError -> DEBU 62d Ignoring NoTransitionError: no transition
2018-07-03 02:34:17.664 UTC [chaincode] func1 -> DEBU 62e [3c7ea620]state is ready
2018-07-03 02:34:17.664 UTC [chaincode] func1 -> DEBU 62f [3c7ea620]Completed PUT_STATE. Sending RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] 1 -> DEBU 630 [3c7ea620]enterBusyState trigger event RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 631 [3c7ea620]Move state message RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] handleMessage -> DEBU 632 [3c7ea620]Fabric side Handling ChaincodeMessage of type: RESPONSE in state ready
2018-07-03 02:34:17.664 UTC [chaincode] filterError -> DEBU 633 Ignoring NoTransitionError: no transition
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 634 [3c7ea620]sending state message RESPONSE
2018-07-03 02:34:17.664 UTC [chaincode] processStream -> DEBU 635 [3c7ea620]Received message COMPLETED from shim
2018-07-03 02:34:17.664 UTC [chaincode] handleMessage -> DEBU 636 [3c7ea620]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:34:17.664 UTC [chaincode] handleMessage -> DEBU 637 [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]HandleMessage- COMPLETED. Notify
2018-07-03 02:34:17.664 UTC [chaincode] notify -> DEBU 638 notifying Txid:3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c, channelID:mychannel
2018-07-03 02:34:17.665 UTC [chaincode] Execute -> DEBU 639 Exit
2018-07-03 02:34:17.665 UTC [endorser] callChaincode -> DEBU 63a [mychannel][3c7ea620] Exit
2018-07-03 02:34:17.665 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 63b Simulation completed, getting simulation results
2018-07-03 02:34:17.665 UTC [lockbasedtxmgr] Done -> DEBU 63c Done with transaction simulation / query execution [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:17.666 UTC [endorser] simulateProposal -> DEBU 63d [mychannel][3c7ea620] Exit
2018-07-03 02:34:17.666 UTC [endorser] endorseProposal -> DEBU 63e [mychannel][3c7ea620] Entry chaincode: name:"lscc" 
2018-07-03 02:34:17.666 UTC [endorser] endorseProposal -> DEBU 63f [mychannel][3c7ea620] escc for chaincode name:"lscc"  is escc
2018-07-03 02:34:17.666 UTC [endorser] callChaincode -> DEBU 640 [mychannel][3c7ea620] Entry chaincode: name:"escc"  version: 1.1.1-snapshot-ff5e861
2018-07-03 02:34:17.666 UTC [ccprovider] NewCCContext -> DEBU 641 NewCCCC (chain=mychannel,chaincode=escc,version=1.1.1-snapshot-ff5e861,txid=3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c,syscc=true,proposal=0xc4235cd9a0,canname=escc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:17.667 UTC [chaincode] Launch -> DEBU 642 chaincode is running(no need to launch) : escc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:17.667 UTC [chaincode] Execute -> DEBU 643 Entry
2018-07-03 02:34:17.667 UTC [chaincode] Execute -> DEBU 644 chaincode canonical name: escc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:17.667 UTC [chaincode] sendExecuteMessage -> DEBU 645 [3c7ea620]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 02:34:17.667 UTC [chaincode] setChaincodeProposal -> DEBU 646 Setting chaincode proposal context...
2018-07-03 02:34:17.667 UTC [chaincode] setChaincodeProposal -> DEBU 647 Proposal different from nil. Creating chaincode proposal context...
2018-07-03 02:34:17.667 UTC [chaincode] sendExecuteMessage -> DEBU 648 [3c7ea620]sendExecuteMsg trigger event TRANSACTION
2018-07-03 02:34:17.667 UTC [chaincode] processStream -> DEBU 649 [3c7ea620]Move state message TRANSACTION
2018-07-03 02:34:17.667 UTC [chaincode] handleMessage -> DEBU 64a [3c7ea620]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 02:34:17.667 UTC [chaincode] filterError -> DEBU 64b Ignoring NoTransitionError: no transition
2018-07-03 02:34:17.667 UTC [chaincode] processStream -> DEBU 64c [3c7ea620]sending state message TRANSACTION
2018-07-03 02:34:17.667 UTC [shim] func1 -> DEBU 64d [3c7ea620]Received message TRANSACTION from shim
2018-07-03 02:34:17.667 UTC [shim] handleMessage -> DEBU 64e [3c7ea620]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 02:34:17.667 UTC [shim] beforeTransaction -> DEBU 64f [3c7ea620]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 02:34:17.667 UTC [escc] Invoke -> DEBU 650 ESCC starts: 8 args
2018-07-03 02:34:17.668 UTC [escc] Invoke -> DEBU 651 ESCC exits successfully
2018-07-03 02:34:17.668 UTC [shim] func1 -> DEBU 652 [3c7ea620]Transaction completed. Sending COMPLETED
2018-07-03 02:34:17.668 UTC [shim] func1 -> DEBU 653 [3c7ea620]Move state message COMPLETED
2018-07-03 02:34:17.668 UTC [shim] handleMessage -> DEBU 654 [3c7ea620]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:34:17.668 UTC [shim] func1 -> DEBU 655 [3c7ea620]send state message COMPLETED
2018-07-03 02:34:17.668 UTC [chaincode] processStream -> DEBU 656 [3c7ea620]Received message COMPLETED from shim
2018-07-03 02:34:17.668 UTC [chaincode] handleMessage -> DEBU 657 [3c7ea620]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:34:17.668 UTC [chaincode] handleMessage -> DEBU 658 [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]HandleMessage- COMPLETED. Notify
2018-07-03 02:34:17.668 UTC [chaincode] notify -> DEBU 659 notifying Txid:3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c, channelID:mychannel
2018-07-03 02:34:17.668 UTC [chaincode] Execute -> DEBU 65a Exit
2018-07-03 02:34:17.668 UTC [endorser] callChaincode -> DEBU 65b [mychannel][3c7ea620] Exit
2018-07-03 02:34:17.668 UTC [endorser] endorseProposal -> DEBU 65c [mychannel][3c7ea620] Exit
2018-07-03 02:34:17.668 UTC [lockbasedtxmgr] Done -> DEBU 65d Done with transaction simulation / query execution [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:17.668 UTC [endorser] ProcessProposal -> DEBU 65e Exit: request from%!(EXTRA string=172.18.0.7:55314)
2018-07-03 02:34:19.738 UTC [blocksProvider] DeliverBlocks -> DEBU 65f [mychannel] Adding payload locally, buffer seqNum = [3], peers number [3]
2018-07-03 02:34:19.739 UTC [blocksProvider] DeliverBlocks -> DEBU 660 [mychannel] Gossiping block [3], peers number [3]
2018-07-03 02:34:19.739 UTC [committer/txvalidator] Validate -> DEBU 661 START Block Validation
2018-07-03 02:34:19.740 UTC [committer/txvalidator] Validate -> DEBU 662 expecting 1 block validation responses
2018-07-03 02:34:19.740 UTC [committer/txvalidator] validateTx -> DEBU 663 validateTx starts for block 0xc421d75560 env 0xc4226a9d10 txn 0
2018-07-03 02:34:19.740 UTC [protoutils] ValidateTransaction -> DEBU 664 ValidateTransactionEnvelope starts for envelope 0xc4226a9d10
2018-07-03 02:34:19.740 UTC [protoutils] ValidateTransaction -> DEBU 665 Header is channel_header:"\010\003\032\014\010\240\301\353\331\005\020\272\267\241\324\001\"\tmychannel*@3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c:\010\022\006\022\004lscc" signature_header:"\n\266\006\n\007Org2MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\n\022\030\007\336\036\002\232I\007\350\372\370MW\017$\375M\332\0376\020\346X\337m" 
2018-07-03 02:34:19.740 UTC [protoutils] validateChannelHeader -> DEBU 666 validateChannelHeader info: header type 3
2018-07-03 02:34:19.740 UTC [protoutils] checkSignatureFromCreator -> DEBU 667 begin
2018-07-03 02:34:19.740 UTC [protoutils] checkSignatureFromCreator -> DEBU 668 creator is &{Org2MSP f1f73cc30a2def8068a36dae53ea9655fffea3e6b7aa128a1ae3b9ba1ed344b9}
2018-07-03 02:34:19.741 UTC [protoutils] checkSignatureFromCreator -> DEBU 669 creator is valid
2018-07-03 02:34:19.741 UTC [protoutils] checkSignatureFromCreator -> DEBU 66a exits successfully
2018-07-03 02:34:19.741 UTC [protoutils] validateEndorserTransaction -> DEBU 66b validateEndorserTransaction starts for data 0xc421ae9500, header channel_header:"\010\003\032\014\010\240\301\353\331\005\020\272\267\241\324\001\"\tmychannel*@3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c:\010\022\006\022\004lscc" signature_header:"\n\266\006\n\007Org2MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\n\022\030\007\336\036\002\232I\007\350\372\370MW\017$\375M\332\0376\020\346X\337m" 
2018-07-03 02:34:19.741 UTC [protoutils] validateEndorserTransaction -> DEBU 66c validateEndorserTransaction info: there are 1 actions
2018-07-03 02:34:19.741 UTC [protoutils] validateEndorserTransaction -> DEBU 66d validateEndorserTransaction info: signature header is valid
2018-07-03 02:34:19.741 UTC [protoutils] ValidateTransaction -> DEBU 66e ValidateTransactionEnvelope returns err %!s(<nil>)
2018-07-03 02:34:19.743 UTC [committer/txvalidator] validateTx -> DEBU 66f Transaction is for channel mychannel
2018-07-03 02:34:19.744 UTC [fsblkstorage] retrieveTransactionByID -> DEBU 670 retrieveTransactionByID() - txId = [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:19.748 UTC [committer/txvalidator] validateTx -> DEBU 671 Validating transaction vscc tx validate
2018-07-03 02:34:19.748 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 672 VSCCValidateTx starts for env 0xc4226a9d10 envbytes 0xc422c90000
2018-07-03 02:34:19.749 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 673 VSCCValidateTxForCC starts for envbytes 0xc422c90000
2018-07-03 02:34:19.749 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 674 constructing new tx simulator
2018-07-03 02:34:19.749 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 675 constructing new tx simulator txid = [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:19.751 UTC [ccprovider] NewCCContext -> DEBU 676 NewCCCC (chain=mychannel,chaincode=vscc,version=1.1.1-snapshot-ff5e861,txid=ad46c68a-e43d-46bb-81ee-9b7a7d58a925,syscc=true,proposal=0x0,canname=vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:19.751 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 677 Invoking VSCC txid 3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c chaindID mychannel
2018-07-03 02:34:19.751 UTC [chaincode] Launch -> DEBU 678 chaincode is running(no need to launch) : vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:19.751 UTC [chaincode] Execute -> DEBU 679 Entry
2018-07-03 02:34:19.751 UTC [chaincode] Execute -> DEBU 67a chaincode canonical name: vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:34:19.751 UTC [chaincode] sendExecuteMessage -> DEBU 67b [ad46c68a]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 02:34:19.751 UTC [chaincode] setChaincodeProposal -> DEBU 67c Setting chaincode proposal context...
2018-07-03 02:34:19.751 UTC [chaincode] sendExecuteMessage -> DEBU 67d [ad46c68a]sendExecuteMsg trigger event TRANSACTION
2018-07-03 02:34:19.751 UTC [chaincode] processStream -> DEBU 67e [ad46c68a]Move state message TRANSACTION
2018-07-03 02:34:19.751 UTC [chaincode] handleMessage -> DEBU 67f [ad46c68a]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 02:34:19.751 UTC [chaincode] filterError -> DEBU 680 Ignoring NoTransitionError: no transition
2018-07-03 02:34:19.751 UTC [chaincode] processStream -> DEBU 681 [ad46c68a]sending state message TRANSACTION
2018-07-03 02:34:19.751 UTC [shim] func1 -> DEBU 682 [ad46c68a]Received message TRANSACTION from shim
2018-07-03 02:34:19.751 UTC [shim] handleMessage -> DEBU 683 [ad46c68a]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 02:34:19.751 UTC [shim] beforeTransaction -> DEBU 684 [ad46c68a]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 02:34:19.751 UTC [vscc] Invoke -> DEBU 685 VSCC invoked
2018-07-03 02:34:19.752 UTC [vscc] deduplicateIdentity -> DEBU 686 Signature set is of size 1 out of 1 endorsement(s)
2018-07-03 02:34:19.760 UTC [vscc] Invoke -> DEBU 687 VSCC info: doing special validation for LSCC
2018-07-03 02:34:19.760 UTC [vscc] ValidateLSCCInvocation -> DEBU 688 VSCC info: ValidateLSCCInvocation acting on deploy [][]uint8{[]uint8{0x6d, 0x79, 0x63, 0x68, 0x61, 0x6e, 0x6e, 0x65, 0x6c}, []uint8{0xa, 0x27, 0x8, 0x1, 0x12, 0xb, 0x12, 0x4, 0x6d, 0x79, 0x63, 0x63, 0x1a, 0x3, 0x31, 0x2e, 0x30, 0x1a, 0x16, 0xa, 0x4, 0x69, 0x6e, 0x69, 0x74, 0xa, 0x1, 0x61, 0xa, 0x3, 0x31, 0x30, 0x30, 0xa, 0x1, 0x62, 0xa, 0x3, 0x32, 0x30, 0x30}, []uint8{0x12, 0xc, 0x12, 0xa, 0x8, 0x1, 0x12, 0x2, 0x8, 0x0, 0x12, 0x2, 0x8, 0x1, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x31, 0x4d, 0x53, 0x50, 0x10, 0x3, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x32, 0x4d, 0x53, 0x50, 0x10, 0x3}, []uint8{0x65, 0x73, 0x63, 0x63}, []uint8{0x76, 0x73, 0x63, 0x63}}
2018-07-03 02:34:19.761 UTC [vscc] ValidateLSCCInvocation -> DEBU 689 VSCC info: validating invocation of lscc function deploy on arguments [][]uint8{[]uint8{0x6d, 0x79, 0x63, 0x68, 0x61, 0x6e, 0x6e, 0x65, 0x6c}, []uint8{0xa, 0x27, 0x8, 0x1, 0x12, 0xb, 0x12, 0x4, 0x6d, 0x79, 0x63, 0x63, 0x1a, 0x3, 0x31, 0x2e, 0x30, 0x1a, 0x16, 0xa, 0x4, 0x69, 0x6e, 0x69, 0x74, 0xa, 0x1, 0x61, 0xa, 0x3, 0x31, 0x30, 0x30, 0xa, 0x1, 0x62, 0xa, 0x3, 0x32, 0x30, 0x30}, []uint8{0x12, 0xc, 0x12, 0xa, 0x8, 0x1, 0x12, 0x2, 0x8, 0x0, 0x12, 0x2, 0x8, 0x1, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x31, 0x4d, 0x53, 0x50, 0x10, 0x3, 0x1a, 0xd, 0x12, 0xb, 0xa, 0x7, 0x4f, 0x72, 0x67, 0x32, 0x4d, 0x53, 0x50, 0x10, 0x3}, []uint8{0x65, 0x73, 0x63, 0x63}, []uint8{0x76, 0x73, 0x63, 0x63}}
2018-07-03 02:34:19.761 UTC [vscc] ValidateLSCCInvocation -> DEBU 68a Namespace lscc
2018-07-03 02:34:19.761 UTC [lockbasedtxmgr] newQueryExecutor -> DEBU 68b constructing new query executor txid = [4dc78d93-5d18-46e4-8671-0f5b445570c2]
2018-07-03 02:34:19.761 UTC [stateleveldb] GetState -> DEBU 68c GetState(). ns=lscc, key=mycc
2018-07-03 02:34:19.761 UTC [lockbasedtxmgr] Done -> DEBU 68d Done with transaction simulation / query execution [4dc78d93-5d18-46e4-8671-0f5b445570c2]
2018-07-03 02:34:19.761 UTC [vscc] ValidateLSCCInvocation -> DEBU 68e Validating deploy for cc mycc version 1.0
2018-07-03 02:34:19.761 UTC [vscc] checkInstantiationPolicy -> DEBU 68f VSCC info: checkInstantiationPolicy starts, policy is &cauthdsl.policy{evaluator:(func([]*common.SignedData, []bool) bool)(0x988790), deserializer:(*mgmt.mspMgmtMgr)(0xc421a27620)}
2018-07-03 02:34:19.762 UTC [vscc] Invoke -> DEBU 690 VSCC exists successfully
2018-07-03 02:34:19.762 UTC [shim] func1 -> DEBU 691 [ad46c68a]Transaction completed. Sending COMPLETED
2018-07-03 02:34:19.762 UTC [shim] func1 -> DEBU 692 [ad46c68a]Move state message COMPLETED
2018-07-03 02:34:19.762 UTC [shim] handleMessage -> DEBU 693 [ad46c68a]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:34:19.762 UTC [shim] func1 -> DEBU 694 [ad46c68a]send state message COMPLETED
2018-07-03 02:34:19.762 UTC [chaincode] processStream -> DEBU 695 [ad46c68a]Received message COMPLETED from shim
2018-07-03 02:34:19.762 UTC [chaincode] handleMessage -> DEBU 696 [ad46c68a]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:34:19.762 UTC [chaincode] handleMessage -> DEBU 697 [ad46c68a-e43d-46bb-81ee-9b7a7d58a925]HandleMessage- COMPLETED. Notify
2018-07-03 02:34:19.762 UTC [chaincode] notify -> DEBU 698 notifying Txid:ad46c68a-e43d-46bb-81ee-9b7a7d58a925, channelID:mychannel
2018-07-03 02:34:19.762 UTC [chaincode] Execute -> DEBU 699 Exit
2018-07-03 02:34:19.762 UTC [lockbasedtxmgr] Done -> DEBU 69a Done with transaction simulation / query execution [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c]
2018-07-03 02:34:19.762 UTC [committer/txvalidator] VSCCValidateTxForCC -> DEBU 69b VSCCValidateTxForCC completes for envbytes 0xc422c90000
2018-07-03 02:34:19.762 UTC [committer/txvalidator] VSCCValidateTx -> DEBU 69c VSCCValidateTx completes for env 0xc4226a9d10 envbytes 0xc422c90000
2018-07-03 02:34:19.762 UTC [committer/txvalidator] validateTx -> DEBU 69d validateTx completes for block 0xc421d75560 env 0xc4226a9d10 txn 0
2018-07-03 02:34:19.762 UTC [committer/txvalidator] Validate -> DEBU 69e got result for idx 0, code 0
2018-07-03 02:34:19.762 UTC [committer/txvalidator] Validate -> DEBU 69f END Block Validation
2018-07-03 02:34:19.763 UTC [kvledger] CommitWithPvtData -> DEBU 6a0 Channel [mychannel]: Validating state for block [3]
2018-07-03 02:34:19.765 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 6a1 Validating new block with num trans = [1]
2018-07-03 02:34:19.765 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 6a2 ValidateAndPrepareBatch() for block number = [3]
2018-07-03 02:34:19.765 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 6a3 preprocessing ProtoBlock...
2018-07-03 02:34:19.765 UTC [valimpl] preprocessProtoBlock -> DEBU 6a4 txType=ENDORSER_TRANSACTION
2018-07-03 02:34:19.765 UTC [stateleveldb] GetState -> DEBU 6a5 GetState(). ns=lscc, key=mycc
2018-07-03 02:34:19.765 UTC [statebasedval] validateKVRead -> DEBU 6a6 Comparing versions for key [mycc]: committed version=(*version.Height)(nil) and read version=(*version.Height)(nil)
2018-07-03 02:34:19.765 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 6a7 Block [3] Transaction index [0] TxId [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c] marked as valid by state validator
2018-07-03 02:34:19.765 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 6a8 validating rwset...
2018-07-03 02:34:19.765 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 6a9 postprocessing ProtoBlock...
2018-07-03 02:34:19.765 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 6aa ValidateAndPrepareBatch() complete
2018-07-03 02:34:19.765 UTC [lockbasedtxmgr] invokeNamespaceListeners -> DEBU 6ab Invoking listener for state changes over namespace:lscc
2018-07-03 02:34:19.765 UTC [cceventmgmt] HandleStateUpdates -> DEBU 6ac Channel [mychannel]: Handling state updates in LSCC namespace - stateUpdates=[]*kvrwset.KVWrite{(*kvrwset.KVWrite)(0xc421b73f80)}
2018-07-03 02:34:19.765 UTC [cceventmgmt] HandleStateUpdates -> INFO 6ad Channel [mychannel]: Handling LSCC state update for chaincode [mycc]
2018-07-03 02:34:19.765 UTC [cceventmgmt] HandleChaincodeDeploy -> DEBU 6ae Channel [mychannel]: Handling chaincode deploy event for chaincode [[Name=mycc, Version=1.0, Hash=[]byte{0x47, 0x6f, 0xca, 0x1a, 0x94, 0x92, 0x74, 0x0, 0x19, 0x71, 0xf1, 0xec, 0x28, 0x36, 0xcb, 0x9, 0x32, 0x1f, 0xb, 0x71, 0x26, 0x8b, 0x37, 0x62, 0xd6, 0x89, 0x31, 0xc9, 0x3f, 0x21, 0x81, 0x34}]]
2018-07-03 02:34:19.765 UTC [ccprovider] ExtractStatedbArtifactsFromCCPackage -> DEBU 6af header.Name = src/github.com/chaincode/chaincode_example02/go/chaincode_example02.go
2018-07-03 02:34:19.766 UTC [ccprovider] ExtractStatedbArtifactsFromCCPackage -> DEBU 6b0 Created statedb artifact tar
2018-07-03 02:34:19.766 UTC [cceventmgmt] HandleChaincodeDeploy -> DEBU 6b1 Channel [mychannel]: Handled chaincode deploy event for chaincode [[Name=mycc, Version=1.0, Hash=[]byte{0x47, 0x6f, 0xca, 0x1a, 0x94, 0x92, 0x74, 0x0, 0x19, 0x71, 0xf1, 0xec, 0x28, 0x36, 0xcb, 0x9, 0x32, 0x1f, 0xb, 0x71, 0x26, 0x8b, 0x37, 0x62, 0xd6, 0x89, 0x31, 0xc9, 0x3f, 0x21, 0x81, 0x34}]]
2018-07-03 02:34:19.766 UTC [kvledger] CommitWithPvtData -> DEBU 6b2 Channel [mychannel]: Committing block [3] to storage
2018-07-03 02:34:19.767 UTC [pvtdatastorage] Prepare -> DEBU 6b3 Saved 0 private data write sets for block [3]
2018-07-03 02:34:19.774 UTC [fsblkstorage] indexBlock -> DEBU 6b4 Indexing block [blockNum=3, blockHash=[]byte{0x1f, 0x6f, 0xfe, 0x4d, 0x3d, 0x11, 0x9f, 0xa0, 0x86, 0x6b, 0xf3, 0x64, 0x19, 0x4d, 0x16, 0x44, 0x9c, 0x9e, 0x43, 0xa4, 0xc4, 0x70, 0xde, 0xef, 0x8, 0x60, 0xcb, 0xa2, 0x3e, 0xac, 0xb7, 0x96} txOffsets=
txId=3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c locPointer=offset=70, bytesLength=3526
]
2018-07-03 02:34:19.774 UTC [fsblkstorage] indexBlock -> DEBU 6b5 Adding txLoc [fileSuffixNum=0, offset=50731, bytesLength=3526] for tx ID: [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c] to index
2018-07-03 02:34:19.774 UTC [fsblkstorage] indexBlock -> DEBU 6b6 Adding txLoc [fileSuffixNum=0, offset=50731, bytesLength=3526] for tx number:[0] ID: [3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c] to blockNumTranNum index
2018-07-03 02:34:19.775 UTC [fsblkstorage] updateCheckpoint -> DEBU 6b7 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[56051], isChainEmpty=[false], lastBlockNumber=[3]
2018-07-03 02:34:19.775 UTC [pvtdatastorage] Commit -> DEBU 6b8 Committing private data for block [3]
2018-07-03 02:34:19.775 UTC [pvtdatastorage] Commit -> DEBU 6b9 Committed private data for block [3]
2018-07-03 02:34:19.775 UTC [kvledger] CommitWithPvtData -> INFO 6ba Channel [mychannel]: Committed block [3] with 1 transaction(s)
2018-07-03 02:34:19.775 UTC [kvledger] CommitWithPvtData -> DEBU 6bb Channel [mychannel]: Committing block [3] transactions to state database
2018-07-03 02:34:19.775 UTC [lockbasedtxmgr] Commit -> DEBU 6bc Committing updates to state database
2018-07-03 02:34:19.775 UTC [lockbasedtxmgr] Commit -> DEBU 6bd Write lock acquired for committing updates to state database
2018-07-03 02:34:19.776 UTC [stateleveldb] ApplyUpdates -> DEBU 6be Channel [mychannel]: Applying key(string)=[lsccmycc] key(bytes)=[[]byte{0x6c, 0x73, 0x63, 0x63, 0x0, 0x6d, 0x79, 0x63, 0x63}]
2018-07-03 02:34:19.776 UTC [stateleveldb] ApplyUpdates -> DEBU 6bf Channel [mychannel]: Applying key(string)=[mycca] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x61}]
2018-07-03 02:34:19.776 UTC [stateleveldb] ApplyUpdates -> DEBU 6c0 Channel [mychannel]: Applying key(string)=[myccb] key(bytes)=[[]byte{0x6d, 0x79, 0x63, 0x63, 0x0, 0x62}]
2018-07-03 02:34:19.777 UTC [lockbasedtxmgr] Commit -> DEBU 6c1 Updates committed to state database
2018-07-03 02:34:19.777 UTC [kvledger] CommitWithPvtData -> DEBU 6c2 Channel [mychannel]: Committing block [3] transactions to history database
2018-07-03 02:34:19.777 UTC [historyleveldb] Commit -> DEBU 6c3 Channel [mychannel]: Updating history database for blockNo [3] with [1] transactions
2018-07-03 02:34:19.778 UTC [historyleveldb] Commit -> DEBU 6c4 Channel [mychannel]: Updates committed to history database for blockNo [3]
2018-07-03 02:34:19.778 UTC [eventhub_producer] CreateBlockEvents -> DEBU 6c5 Entry
2018-07-03 02:34:19.778 UTC [eventhub_producer] CreateBlockEvents -> DEBU 6c6 Channel [mychannel]: Block event for block number [3] contains transaction id: 3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c
2018-07-03 02:34:19.778 UTC [eventhub_producer] CreateBlockEvents -> DEBU 6c7 Exit
2018-07-03 02:34:19.778 UTC [eventhub_producer] Send -> DEBU 6c8 Entry
2018-07-03 02:34:19.778 UTC [eventhub_producer] Send -> DEBU 6c9 Event processor timeout > 0
2018-07-03 02:34:19.778 UTC [eventhub_producer] Send -> DEBU 6ca Event sent successfully
2018-07-03 02:34:19.779 UTC [eventhub_producer] Send -> DEBU 6cb Exit
2018-07-03 02:34:19.779 UTC [eventhub_producer] Send -> DEBU 6cc Entry
2018-07-03 02:34:19.779 UTC [eventhub_producer] Send -> DEBU 6cd Event processor timeout > 0
2018-07-03 02:34:19.779 UTC [eventhub_producer] Send -> DEBU 6ce Event sent successfully
2018-07-03 02:34:19.779 UTC [eventhub_producer] Send -> DEBU 6cf Exit

