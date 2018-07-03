2018-07-03 02:09:42.649 UTC [endorser] ProcessProposal -> DEBU 1bc Entering: Got request from 172.18.0.7:52576
2018-07-03 02:09:42.649 UTC [protoutils] ValidateProposalMessage -> DEBU 1bd ValidateProposalMessage starts for signed proposal 0xc421e16780
2018-07-03 02:09:42.649 UTC [protoutils] validateChannelHeader -> DEBU 1be validateChannelHeader info: header type 1
2018-07-03 02:09:42.649 UTC [protoutils] checkSignatureFromCreator -> DEBU 1bf begin
2018-07-03 02:09:42.650 UTC [protoutils] checkSignatureFromCreator -> DEBU 1c0 creator is &{Org2MSP f1f73cc30a2def8068a36dae53ea9655fffea3e6b7aa128a1ae3b9ba1ed344b9}
2018-07-03 02:09:42.650 UTC [protoutils] checkSignatureFromCreator -> DEBU 1c1 creator is valid
2018-07-03 02:09:42.650 UTC [protoutils] checkSignatureFromCreator -> DEBU 1c2 exits successfully
2018-07-03 02:09:42.650 UTC [protoutils] validateChaincodeProposalMessage -> DEBU 1c3 validateChaincodeProposalMessage starts for proposal 0xc421df9450, header 0xc421e16bd0
2018-07-03 02:09:42.650 UTC [protoutils] validateChaincodeProposalMessage -> DEBU 1c4 validateChaincodeProposalMessage info: header extension references chaincode name:"cscc" 
2018-07-03 02:09:42.650 UTC [endorser] preProcess -> DEBU 1c5 [][7417df5c] processing txid: 7417df5c32ce8743d48cf4a2dc69b97d8144543231d60271a180cbf50373e948
2018-07-03 02:09:42.650 UTC [endorser] simulateProposal -> DEBU 1c6 [][7417df5c] Entry chaincode: name:"cscc" 
2018-07-03 02:09:42.650 UTC [endorser] callChaincode -> DEBU 1c7 [][7417df5c] Entry chaincode: name:"cscc"  version: 1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.650 UTC [ccprovider] NewCCContext -> DEBU 1c8 NewCCCC (chain=,chaincode=cscc,version=1.1.1-snapshot-ff5e861,txid=7417df5c32ce8743d48cf4a2dc69b97d8144543231d60271a180cbf50373e948,syscc=true,proposal=0xc421df9450,canname=cscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.650 UTC [chaincode] Launch -> DEBU 1c9 chaincode is running(no need to launch) : cscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.650 UTC [chaincode] Execute -> DEBU 1ca Entry
2018-07-03 02:09:42.650 UTC [chaincode] Execute -> DEBU 1cb chaincode canonical name: cscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.650 UTC [chaincode] sendExecuteMessage -> DEBU 1cc [7417df5c]Inside sendExecuteMessage. Message TRANSACTION
2018-07-03 02:09:42.650 UTC [chaincode] setChaincodeProposal -> DEBU 1cd Setting chaincode proposal context...
2018-07-03 02:09:42.650 UTC [chaincode] setChaincodeProposal -> DEBU 1ce Proposal different from nil. Creating chaincode proposal context...
2018-07-03 02:09:42.650 UTC [chaincode] sendExecuteMessage -> DEBU 1cf [7417df5c]sendExecuteMsg trigger event TRANSACTION
2018-07-03 02:09:42.650 UTC [chaincode] processStream -> DEBU 1d0 [7417df5c]Move state message TRANSACTION
2018-07-03 02:09:42.650 UTC [chaincode] handleMessage -> DEBU 1d1 [7417df5c]Fabric side Handling ChaincodeMessage of type: TRANSACTION in state ready
2018-07-03 02:09:42.651 UTC [chaincode] filterError -> DEBU 1d2 Ignoring NoTransitionError: no transition
2018-07-03 02:09:42.651 UTC [chaincode] processStream -> DEBU 1d3 [7417df5c]sending state message TRANSACTION
2018-07-03 02:09:42.651 UTC [shim] func1 -> DEBU 1d4 [7417df5c]Received message TRANSACTION from shim
2018-07-03 02:09:42.651 UTC [shim] handleMessage -> DEBU 1d5 [7417df5c]Handling ChaincodeMessage of type: TRANSACTION(state:ready)
2018-07-03 02:09:42.651 UTC [shim] beforeTransaction -> DEBU 1d6 [7417df5c]Received TRANSACTION, invoking transaction on chaincode(Src:ready, Dst:ready)
2018-07-03 02:09:42.651 UTC [cscc] Invoke -> DEBU 1d7 Invoke function: JoinChain
2018-07-03 02:09:42.651 UTC [ledgermgmt] CreateLedger -> INFO 1d8 Creating ledger [mychannel] with genesis block
2018-07-03 02:09:42.653 UTC [fsblkstorage] newBlockfileMgr -> DEBU 1d9 newBlockfileMgr() initializing file-based block storage for ledger: mychannel 
2018-07-03 02:09:42.653 UTC [kvledger.util] CreateDirIfMissing -> DEBU 1da CreateDirIfMissing [/var/hyperledger/production/ledgersData/chains/chains/mychannel/]
2018-07-03 02:09:42.653 UTC [kvledger.util] logDirStatus -> DEBU 1db Before creating dir - [/var/hyperledger/production/ledgersData/chains/chains/mychannel/] does not exist
2018-07-03 02:09:42.653 UTC [kvledger.util] logDirStatus -> DEBU 1dc After creating dir - [/var/hyperledger/production/ledgersData/chains/chains/mychannel/] exists
2018-07-03 02:09:42.653 UTC [fsblkstorage] newBlockfileMgr -> INFO 1dd Getting block information from block storage
2018-07-03 02:09:42.653 UTC [fsblkstorage] constructCheckpointInfoFromBlockFiles -> DEBU 1de Retrieving checkpoint info from block files
2018-07-03 02:09:42.653 UTC [fsblkstorage] retrieveLastFileSuffix -> DEBU 1df retrieveLastFileSuffix()
2018-07-03 02:09:42.653 UTC [fsblkstorage] retrieveLastFileSuffix -> DEBU 1e0 retrieveLastFileSuffix() - biggestFileNum = -1
2018-07-03 02:09:42.653 UTC [fsblkstorage] constructCheckpointInfoFromBlockFiles -> DEBU 1e1 Last file number found = -1
2018-07-03 02:09:42.653 UTC [fsblkstorage] constructCheckpointInfoFromBlockFiles -> DEBU 1e2 No block file found
2018-07-03 02:09:42.653 UTC [fsblkstorage] newBlockfileMgr -> DEBU 1e3 Info constructed by scanning the blocks dir = (*fsblkstorage.checkpointInfo)(0xc42244c4e0)(latestFileChunkSuffixNum=[0], latestFileChunksize=[0], isChainEmpty=[true], lastBlockNumber=[0])
2018-07-03 02:09:42.655 UTC [fsblkstorage] newBlockIndex -> DEBU 1e4 newBlockIndex() - indexItems:[[BlockHash BlockNum TxID BlockNumTranNum BlockTxID TxValidationCode]]
2018-07-03 02:09:42.655 UTC [kvledger] newKVLedger -> DEBU 1e5 Creating KVLedger ledgerID=mychannel: 
2018-07-03 02:09:42.655 UTC [kvledger] newKVLedger -> DEBU 1e6 Register state db for chaincode lifecycle events: false
2018-07-03 02:09:42.655 UTC [kvledger] recoverDBs -> DEBU 1e7 Entering recoverDB()
2018-07-03 02:09:42.655 UTC [kvledger] recoverDBs -> DEBU 1e8 Block storage is empty.
2018-07-03 02:09:42.655 UTC [kvledger] CommitWithPvtData -> DEBU 1e9 Channel [mychannel]: Validating state for block [0]
2018-07-03 02:09:42.655 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 1ea Validating new block with num trans = [1]
2018-07-03 02:09:42.655 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 1eb ValidateAndPrepareBatch() for block number = [0]
2018-07-03 02:09:42.655 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 1ec preprocessing ProtoBlock...
2018-07-03 02:09:42.655 UTC [valimpl] preprocessProtoBlock -> DEBU 1ed txType=CONFIG
2018-07-03 02:09:42.655 UTC [valimpl] processNonEndorserTx -> DEBU 1ee Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:09:42.655 UTC [valimpl] processNonEndorserTx -> DEBU 1ef Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:09:42.655 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 1f0 constructing new tx simulator
2018-07-03 02:09:42.655 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 1f1 constructing new tx simulator txid = []
2018-07-03 02:09:42.655 UTC [peer] GenerateSimulationResults -> DEBU 1f2 Processing CONFIG
2018-07-03 02:09:42.655 UTC [peer] processChannelConfigTx -> DEBU 1f3 channelConfig=sequence:1 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:09:42.655 UTC [common/channelconfig] NewStandardValues -> DEBU 1f4 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1f5 Processing field: HashingAlgorithm
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1f6 Processing field: BlockDataHashingStructure
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1f7 Processing field: OrdererAddresses
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1f8 Processing field: Consortium
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1f9 Processing field: Capabilities
2018-07-03 02:09:42.655 UTC [common/channelconfig] NewStandardValues -> DEBU 1fa Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1fb Processing field: ConsensusType
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1fc Processing field: BatchSize
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1fd Processing field: BatchTimeout
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1fe Processing field: KafkaBrokers
2018-07-03 02:09:42.655 UTC [common/channelconfig] initializeProtosStruct -> DEBU 1ff Processing field: ChannelRestrictions
2018-07-03 02:09:42.656 UTC [common/channelconfig] initializeProtosStruct -> DEBU 200 Processing field: Capabilities
2018-07-03 02:09:42.656 UTC [common/channelconfig] NewStandardValues -> DEBU 201 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:09:42.656 UTC [common/channelconfig] initializeProtosStruct -> DEBU 202 Processing field: MSP
2018-07-03 02:09:42.656 UTC [common/channelconfig] validateMSP -> DEBU 203 Setting up MSP for org OrdererOrg
2018-07-03 02:09:42.656 UTC [common/channelconfig] NewStandardValues -> DEBU 204 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:09:42.657 UTC [common/channelconfig] initializeProtosStruct -> DEBU 205 Processing field: Capabilities
2018-07-03 02:09:42.657 UTC [common/channelconfig] NewStandardValues -> DEBU 206 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:09:42.657 UTC [common/channelconfig] initializeProtosStruct -> DEBU 207 Processing field: AnchorPeers
2018-07-03 02:09:42.657 UTC [common/channelconfig] NewStandardValues -> DEBU 208 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:09:42.657 UTC [common/channelconfig] initializeProtosStruct -> DEBU 209 Processing field: MSP
2018-07-03 02:09:42.657 UTC [common/channelconfig] Validate -> DEBU 20a Anchor peers for org Org2MSP are 
2018-07-03 02:09:42.657 UTC [common/channelconfig] validateMSP -> DEBU 20b Setting up MSP for org Org2MSP
2018-07-03 02:09:42.657 UTC [common/channelconfig] NewStandardValues -> DEBU 20c Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:09:42.657 UTC [common/channelconfig] initializeProtosStruct -> DEBU 20d Processing field: AnchorPeers
2018-07-03 02:09:42.657 UTC [common/channelconfig] NewStandardValues -> DEBU 20e Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:09:42.657 UTC [common/channelconfig] initializeProtosStruct -> DEBU 20f Processing field: MSP
2018-07-03 02:09:42.657 UTC [common/channelconfig] Validate -> DEBU 210 Anchor peers for org Org1MSP are 
2018-07-03 02:09:42.657 UTC [common/channelconfig] validateMSP -> DEBU 211 Setting up MSP for org Org1MSP
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 212 Adding to config map: [Group]  /Channel
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 213 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 214 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 215 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 216 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 217 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 218 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 219 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 21a Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 21b Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 21c Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 21d Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 21e Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 21f Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 220 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 221 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 222 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 223 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 224 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:09:42.658 UTC [common/configtx] addToMap -> DEBU 225 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 226 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 227 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 228 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 229 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 22a Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 22b Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 22c Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 22d Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 22e Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 22f Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 230 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 231 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 232 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 233 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 234 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 235 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 236 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 237 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:09:42.659 UTC [common/configtx] addToMap -> DEBU 238 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:09:42.659 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 239 Simulation completed, getting simulation results
2018-07-03 02:09:42.659 UTC [lockbasedtxmgr] Done -> DEBU 23a Done with transaction simulation / query execution []
2018-07-03 02:09:42.659 UTC [lockbasedtxmgr] Done -> DEBU 23b Done with transaction simulation / query execution []
2018-07-03 02:09:42.659 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 23c Block [0] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:09:42.659 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 23d validating rwset...
2018-07-03 02:09:42.659 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 23e postprocessing ProtoBlock...
2018-07-03 02:09:42.659 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 23f ValidateAndPrepareBatch() complete
2018-07-03 02:09:42.659 UTC [kvledger] CommitWithPvtData -> DEBU 240 Channel [mychannel]: Committing block [0] to storage
2018-07-03 02:09:42.660 UTC [pvtdatastorage] Prepare -> DEBU 241 Saved 0 private data write sets for block [0]
2018-07-03 02:09:42.661 UTC [fsblkstorage] indexBlock -> DEBU 242 Indexing block [blockNum=0, blockHash=[]byte{0x62, 0xc0, 0x2e, 0x6b, 0xcc, 0x92, 0x26, 0x2f, 0x2f, 0xfe, 0x54, 0xee, 0x9f, 0x3, 0x7c, 0xa, 0x54, 0xd9, 0xc3, 0x6b, 0xa9, 0x78, 0x8f, 0xaf, 0x47, 0xf1, 0x18, 0x23, 0x4b, 0x90, 0xfa, 0x91} txOffsets=
txId= locPointer=offset=38, bytesLength=15606
]
2018-07-03 02:09:42.661 UTC [fsblkstorage] indexBlock -> DEBU 243 Adding txLoc [fileSuffixNum=0, offset=38, bytesLength=15606] for tx ID: [] to index
2018-07-03 02:09:42.661 UTC [fsblkstorage] indexBlock -> DEBU 244 Adding txLoc [fileSuffixNum=0, offset=38, bytesLength=15606] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:09:42.662 UTC [fsblkstorage] updateCheckpoint -> DEBU 245 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[15650], isChainEmpty=[false], lastBlockNumber=[0]
2018-07-03 02:09:42.662 UTC [pvtdatastorage] Commit -> DEBU 246 Committing private data for block [0]
2018-07-03 02:09:42.664 UTC [pvtdatastorage] Commit -> DEBU 247 Committed private data for block [0]
2018-07-03 02:09:42.664 UTC [kvledger] CommitWithPvtData -> INFO 248 Channel [mychannel]: Committed block [0] with 1 transaction(s)
2018-07-03 02:09:42.664 UTC [kvledger] CommitWithPvtData -> DEBU 249 Channel [mychannel]: Committing block [0] transactions to state database
2018-07-03 02:09:42.664 UTC [lockbasedtxmgr] Commit -> DEBU 24a Committing updates to state database
2018-07-03 02:09:42.664 UTC [lockbasedtxmgr] Commit -> DEBU 24b Write lock acquired for committing updates to state database
2018-07-03 02:09:42.664 UTC [stateleveldb] ApplyUpdates -> DEBU 24c Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:09:42.667 UTC [lockbasedtxmgr] Commit -> DEBU 24d Updates committed to state database
2018-07-03 02:09:42.667 UTC [kvledger] CommitWithPvtData -> DEBU 24e Channel [mychannel]: Committing block [0] transactions to history database
2018-07-03 02:09:42.667 UTC [historyleveldb] Commit -> DEBU 24f Channel [mychannel]: Updating history database for blockNo [0] with [1] transactions
2018-07-03 02:09:42.667 UTC [historyleveldb] Commit -> DEBU 250 Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:09:42.669 UTC [historyleveldb] Commit -> DEBU 251 Channel [mychannel]: Updates committed to history database for blockNo [0]
2018-07-03 02:09:42.671 UTC [ledgermgmt] CreateLedger -> INFO 252 Created ledger [mychannel] with genesis block
2018-07-03 02:09:42.671 UTC [lockbasedtxmgr] newQueryExecutor -> DEBU 253 constructing new query executor txid = [cb45e435-940a-4e05-9ec9-4c1db217bf35]
2018-07-03 02:09:42.671 UTC [stateleveldb] GetState -> DEBU 254 GetState(). ns=, key=resourcesconfigtx.CHANNEL_CONFIG_KEY
2018-07-03 02:09:42.671 UTC [lockbasedtxmgr] Done -> DEBU 255 Done with transaction simulation / query execution [cb45e435-940a-4e05-9ec9-4c1db217bf35]
2018-07-03 02:09:42.671 UTC [common/channelconfig] NewStandardValues -> DEBU 256 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 257 Processing field: HashingAlgorithm
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 258 Processing field: BlockDataHashingStructure
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 259 Processing field: OrdererAddresses
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 25a Processing field: Consortium
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 25b Processing field: Capabilities
2018-07-03 02:09:42.671 UTC [common/channelconfig] NewStandardValues -> DEBU 25c Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 25d Processing field: Capabilities
2018-07-03 02:09:42.671 UTC [common/channelconfig] NewStandardValues -> DEBU 25e Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 25f Processing field: AnchorPeers
2018-07-03 02:09:42.671 UTC [common/channelconfig] NewStandardValues -> DEBU 260 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:09:42.671 UTC [common/channelconfig] initializeProtosStruct -> DEBU 261 Processing field: MSP
2018-07-03 02:09:42.671 UTC [common/channelconfig] Validate -> DEBU 262 Anchor peers for org Org2MSP are 
2018-07-03 02:09:42.671 UTC [common/channelconfig] validateMSP -> DEBU 263 Setting up MSP for org Org2MSP
2018-07-03 02:09:42.672 UTC [common/channelconfig] NewStandardValues -> DEBU 264 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:09:42.672 UTC [common/channelconfig] initializeProtosStruct -> DEBU 265 Processing field: AnchorPeers
2018-07-03 02:09:42.672 UTC [common/channelconfig] NewStandardValues -> DEBU 266 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:09:42.672 UTC [common/channelconfig] initializeProtosStruct -> DEBU 267 Processing field: MSP
2018-07-03 02:09:42.672 UTC [common/channelconfig] Validate -> DEBU 268 Anchor peers for org Org1MSP are 
2018-07-03 02:09:42.672 UTC [common/channelconfig] validateMSP -> DEBU 269 Setting up MSP for org Org1MSP
2018-07-03 02:09:42.674 UTC [common/channelconfig] NewStandardValues -> DEBU 26a Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 26b Processing field: ConsensusType
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 26c Processing field: BatchSize
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 26d Processing field: BatchTimeout
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 26e Processing field: KafkaBrokers
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 26f Processing field: ChannelRestrictions
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 270 Processing field: Capabilities
2018-07-03 02:09:42.674 UTC [common/channelconfig] NewStandardValues -> DEBU 271 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:09:42.674 UTC [common/channelconfig] initializeProtosStruct -> DEBU 272 Processing field: MSP
2018-07-03 02:09:42.674 UTC [common/channelconfig] validateMSP -> DEBU 273 Setting up MSP for org OrdererOrg
2018-07-03 02:09:42.674 UTC [common/configtx] addToMap -> DEBU 274 Adding to config map: [Group]  /Channel
2018-07-03 02:09:42.674 UTC [common/configtx] addToMap -> DEBU 275 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:09:42.674 UTC [common/configtx] addToMap -> DEBU 276 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:09:42.674 UTC [common/configtx] addToMap -> DEBU 277 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:09:42.674 UTC [common/configtx] addToMap -> DEBU 278 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:09:42.674 UTC [common/configtx] addToMap -> DEBU 279 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 27a Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 27b Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 27c Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 27d Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 27e Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 27f Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 280 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 281 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 282 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 283 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 284 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 285 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 286 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 287 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 288 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 289 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 28a Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 28b Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 28c Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 28d Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 28e Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 28f Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 290 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 291 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 292 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 293 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 294 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 295 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 296 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 297 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 298 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 299 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 29a Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:09:42.675 UTC [common/capabilities] Supported -> DEBU 29b Application capability V1_1 is supported and is enabled
2018-07-03 02:09:42.675 UTC [common/capabilities] Supported -> DEBU 29c Channel capability V1_1 is supported and is enabled
2018-07-03 02:09:42.675 UTC [common/channelconfig] LogSanityChecks -> DEBU 29d As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:09:42.675 UTC [common/channelconfig] LogSanityChecks -> DEBU 29e As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:09:42.675 UTC [common/channelconfig] LogSanityChecks -> DEBU 29f As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:09:42.675 UTC [common/channelconfig] LogSanityChecks -> DEBU 2a0 As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:09:42.675 UTC [common/channelconfig] LogSanityChecks -> DEBU 2a1 As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:09:42.675 UTC [common/channelconfig] LogSanityChecks -> DEBU 2a2 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:09:42.675 UTC [common/configtx] addToMap -> DEBU 2a3 Adding to config map: [Group]  /Resources
2018-07-03 02:09:42.676 UTC [peer] updateTrustedRoots -> DEBU 2a4 Updating trusted root authorities for channel mychannel
2018-07-03 02:09:42.676 UTC [peer] buildTrustedRootsForChain -> DEBU 2a5 updating root CAs for channel [mychannel]
2018-07-03 02:09:42.676 UTC [peer] buildTrustedRootsForChain -> DEBU 2a6 adding app root CAs for MSP [Org1MSP]
2018-07-03 02:09:42.676 UTC [peer] buildTrustedRootsForChain -> DEBU 2a7 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:09:42.676 UTC [peer] buildTrustedRootsForChain -> DEBU 2a8 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:09:42.677 UTC [kvledger.util] CreateDirIfMissing -> DEBU 2a9 CreateDirIfMissing [/var/hyperledger/production/transientStore/]
2018-07-03 02:09:42.677 UTC [kvledger.util] logDirStatus -> DEBU 2aa Before creating dir - [/var/hyperledger/production/transientStore/] does not exist
2018-07-03 02:09:42.677 UTC [kvledger.util] logDirStatus -> DEBU 2ab After creating dir - [/var/hyperledger/production/transientStore/] exists
2018-07-03 02:09:42.679 UTC [peer] InitChain -> DEBU 2ac Init chain mychannel
2018-07-03 02:09:42.679 UTC [nodeCmd] func4 -> DEBU 2ad Deploying system CC, for chain <mychannel>
2018-07-03 02:09:42.679 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 2ae constructing new tx simulator
2018-07-03 02:09:42.679 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 2af constructing new tx simulator txid = [51a8cbea-6545-4746-be5d-5ca86200994c]
2018-07-03 02:09:42.679 UTC [ccprovider] NewCCContext -> DEBU 2b0 NewCCCC (chain=mychannel,chaincode=cscc,version=1.1.1-snapshot-ff5e861,txid=51a8cbea-6545-4746-be5d-5ca86200994c,syscc=true,proposal=0x0,canname=cscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.679 UTC [chaincode] Launch -> DEBU 2b1 chaincode is running(no need to launch) : cscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.679 UTC [chaincode] Execute -> DEBU 2b2 Entry
2018-07-03 02:09:42.679 UTC [chaincode] Execute -> DEBU 2b3 chaincode canonical name: cscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.679 UTC [chaincode] sendExecuteMessage -> DEBU 2b4 [51a8cbea]Inside sendExecuteMessage. Message INIT
2018-07-03 02:09:42.679 UTC [chaincode] setChaincodeProposal -> DEBU 2b5 Setting chaincode proposal context...
2018-07-03 02:09:42.679 UTC [chaincode] sendExecuteMessage -> DEBU 2b6 [51a8cbea]sendExecuteMsg trigger event INIT
2018-07-03 02:09:42.679 UTC [chaincode] processStream -> DEBU 2b7 [51a8cbea]Move state message INIT
2018-07-03 02:09:42.679 UTC [chaincode] handleMessage -> DEBU 2b8 [51a8cbea]Fabric side Handling ChaincodeMessage of type: INIT in state ready
2018-07-03 02:09:42.679 UTC [chaincode] filterError -> DEBU 2b9 Ignoring NoTransitionError: no transition
2018-07-03 02:09:42.679 UTC [chaincode] processStream -> DEBU 2ba [51a8cbea]sending state message INIT
2018-07-03 02:09:42.680 UTC [shim] func1 -> DEBU 2bb [51a8cbea]Received message INIT from shim
2018-07-03 02:09:42.680 UTC [shim] handleMessage -> DEBU 2bc [51a8cbea]Handling ChaincodeMessage of type: INIT(state:ready)
2018-07-03 02:09:42.680 UTC [shim] beforeInit -> DEBU 2bd Entered state ready
2018-07-03 02:09:42.680 UTC [shim] beforeInit -> DEBU 2be [51a8cbea]Received INIT, initializing chaincode
2018-07-03 02:09:42.680 UTC [cscc] Init -> INFO 2bf Init CSCC
2018-07-03 02:09:42.680 UTC [shim] func1 -> DEBU 2c0 [51a8cbea]Init get response status: 200
2018-07-03 02:09:42.680 UTC [shim] func1 -> DEBU 2c1 [51a8cbea]Init succeeded. Sending COMPLETED
2018-07-03 02:09:42.680 UTC [shim] func1 -> DEBU 2c2 [51a8cbea]Move state message COMPLETED
2018-07-03 02:09:42.680 UTC [shim] handleMessage -> DEBU 2c3 [51a8cbea]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:09:42.680 UTC [shim] func1 -> DEBU 2c4 [51a8cbea]send state message COMPLETED
2018-07-03 02:09:42.680 UTC [chaincode] processStream -> DEBU 2c5 [51a8cbea]Received message COMPLETED from shim
2018-07-03 02:09:42.680 UTC [chaincode] handleMessage -> DEBU 2c6 [51a8cbea]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:09:42.680 UTC [chaincode] handleMessage -> DEBU 2c7 [51a8cbea-6545-4746-be5d-5ca86200994c]HandleMessage- COMPLETED. Notify
2018-07-03 02:09:42.680 UTC [chaincode] notify -> DEBU 2c8 notifying Txid:51a8cbea-6545-4746-be5d-5ca86200994c, channelID:mychannel
2018-07-03 02:09:42.680 UTC [chaincode] Execute -> DEBU 2c9 Exit
2018-07-03 02:09:42.680 UTC [sccapi] deploySysCC -> INFO 2ca system chaincode cscc/mychannel(github.com/hyperledger/fabric/core/scc/cscc) deployed
2018-07-03 02:09:42.680 UTC [lockbasedtxmgr] Done -> DEBU 2cb Done with transaction simulation / query execution [51a8cbea-6545-4746-be5d-5ca86200994c]
2018-07-03 02:09:42.680 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 2cc constructing new tx simulator
2018-07-03 02:09:42.680 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 2cd constructing new tx simulator txid = [f616ce74-2286-42ef-a793-f923b1cc4be9]
2018-07-03 02:09:42.680 UTC [ccprovider] NewCCContext -> DEBU 2ce NewCCCC (chain=mychannel,chaincode=lscc,version=1.1.1-snapshot-ff5e861,txid=f616ce74-2286-42ef-a793-f923b1cc4be9,syscc=true,proposal=0x0,canname=lscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.681 UTC [chaincode] Launch -> DEBU 2cf chaincode is running(no need to launch) : lscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.681 UTC [chaincode] Execute -> DEBU 2d0 Entry
2018-07-03 02:09:42.681 UTC [chaincode] Execute -> DEBU 2d1 chaincode canonical name: lscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.681 UTC [chaincode] sendExecuteMessage -> DEBU 2d2 [f616ce74]Inside sendExecuteMessage. Message INIT
2018-07-03 02:09:42.681 UTC [chaincode] setChaincodeProposal -> DEBU 2d3 Setting chaincode proposal context...
2018-07-03 02:09:42.681 UTC [chaincode] sendExecuteMessage -> DEBU 2d4 [f616ce74]sendExecuteMsg trigger event INIT
2018-07-03 02:09:42.681 UTC [chaincode] processStream -> DEBU 2d5 [f616ce74]Move state message INIT
2018-07-03 02:09:42.681 UTC [chaincode] handleMessage -> DEBU 2d6 [f616ce74]Fabric side Handling ChaincodeMessage of type: INIT in state ready
2018-07-03 02:09:42.681 UTC [chaincode] filterError -> DEBU 2d7 Ignoring NoTransitionError: no transition
2018-07-03 02:09:42.681 UTC [chaincode] processStream -> DEBU 2d8 [f616ce74]sending state message INIT
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2d9 [f616ce74]Received message INIT from shim
2018-07-03 02:09:42.681 UTC [shim] handleMessage -> DEBU 2da [f616ce74]Handling ChaincodeMessage of type: INIT(state:ready)
2018-07-03 02:09:42.681 UTC [shim] beforeInit -> DEBU 2db Entered state ready
2018-07-03 02:09:42.681 UTC [shim] beforeInit -> DEBU 2dc [f616ce74]Received INIT, initializing chaincode
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2dd [f616ce74]Init get response status: 200
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2de [f616ce74]Init succeeded. Sending COMPLETED
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2df [f616ce74]Move state message COMPLETED
2018-07-03 02:09:42.681 UTC [shim] handleMessage -> DEBU 2e0 [f616ce74]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2e1 [f616ce74]send state message COMPLETED
2018-07-03 02:09:42.681 UTC [chaincode] processStream -> DEBU 2e2 [f616ce74]Received message COMPLETED from shim
2018-07-03 02:09:42.681 UTC [chaincode] handleMessage -> DEBU 2e3 [f616ce74]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:09:42.681 UTC [chaincode] handleMessage -> DEBU 2e4 [f616ce74-2286-42ef-a793-f923b1cc4be9]HandleMessage- COMPLETED. Notify
2018-07-03 02:09:42.681 UTC [chaincode] notify -> DEBU 2e5 notifying Txid:f616ce74-2286-42ef-a793-f923b1cc4be9, channelID:mychannel
2018-07-03 02:09:42.681 UTC [chaincode] Execute -> DEBU 2e6 Exit
2018-07-03 02:09:42.681 UTC [sccapi] deploySysCC -> INFO 2e7 system chaincode lscc/mychannel(github.com/hyperledger/fabric/core/scc/lscc) deployed
2018-07-03 02:09:42.681 UTC [lockbasedtxmgr] Done -> DEBU 2e8 Done with transaction simulation / query execution [f616ce74-2286-42ef-a793-f923b1cc4be9]
2018-07-03 02:09:42.681 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 2e9 constructing new tx simulator
2018-07-03 02:09:42.681 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 2ea constructing new tx simulator txid = [a2fbcb6d-d54f-48ec-9571-d3074074c331]
2018-07-03 02:09:42.681 UTC [ccprovider] NewCCContext -> DEBU 2eb NewCCCC (chain=mychannel,chaincode=escc,version=1.1.1-snapshot-ff5e861,txid=a2fbcb6d-d54f-48ec-9571-d3074074c331,syscc=true,proposal=0x0,canname=escc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.681 UTC [chaincode] Launch -> DEBU 2ec chaincode is running(no need to launch) : escc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.681 UTC [chaincode] Execute -> DEBU 2ed Entry
2018-07-03 02:09:42.681 UTC [chaincode] Execute -> DEBU 2ee chaincode canonical name: escc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.681 UTC [chaincode] sendExecuteMessage -> DEBU 2ef [a2fbcb6d]Inside sendExecuteMessage. Message INIT
2018-07-03 02:09:42.681 UTC [chaincode] setChaincodeProposal -> DEBU 2f0 Setting chaincode proposal context...
2018-07-03 02:09:42.681 UTC [chaincode] sendExecuteMessage -> DEBU 2f1 [a2fbcb6d]sendExecuteMsg trigger event INIT
2018-07-03 02:09:42.681 UTC [chaincode] processStream -> DEBU 2f2 [a2fbcb6d]Move state message INIT
2018-07-03 02:09:42.681 UTC [chaincode] handleMessage -> DEBU 2f3 [a2fbcb6d]Fabric side Handling ChaincodeMessage of type: INIT in state ready
2018-07-03 02:09:42.681 UTC [chaincode] filterError -> DEBU 2f4 Ignoring NoTransitionError: no transition
2018-07-03 02:09:42.681 UTC [chaincode] processStream -> DEBU 2f5 [a2fbcb6d]sending state message INIT
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2f6 [a2fbcb6d]Received message INIT from shim
2018-07-03 02:09:42.681 UTC [shim] handleMessage -> DEBU 2f7 [a2fbcb6d]Handling ChaincodeMessage of type: INIT(state:ready)
2018-07-03 02:09:42.681 UTC [shim] beforeInit -> DEBU 2f8 Entered state ready
2018-07-03 02:09:42.681 UTC [shim] beforeInit -> DEBU 2f9 [a2fbcb6d]Received INIT, initializing chaincode
2018-07-03 02:09:42.681 UTC [escc] Init -> INFO 2fa Successfully initialized ESCC
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2fb [a2fbcb6d]Init get response status: 200
2018-07-03 02:09:42.681 UTC [shim] func1 -> DEBU 2fc [a2fbcb6d]Init succeeded. Sending COMPLETED
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 2fd [a2fbcb6d]Move state message COMPLETED
2018-07-03 02:09:42.682 UTC [shim] handleMessage -> DEBU 2fe [a2fbcb6d]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 2ff [a2fbcb6d]send state message COMPLETED
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 300 [a2fbcb6d]Received message COMPLETED from shim
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 301 [a2fbcb6d]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 302 [a2fbcb6d-d54f-48ec-9571-d3074074c331]HandleMessage- COMPLETED. Notify
2018-07-03 02:09:42.682 UTC [chaincode] notify -> DEBU 303 notifying Txid:a2fbcb6d-d54f-48ec-9571-d3074074c331, channelID:mychannel
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 304 Exit
2018-07-03 02:09:42.682 UTC [sccapi] deploySysCC -> INFO 305 system chaincode escc/mychannel(github.com/hyperledger/fabric/core/scc/escc) deployed
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] Done -> DEBU 306 Done with transaction simulation / query execution [a2fbcb6d-d54f-48ec-9571-d3074074c331]
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 307 constructing new tx simulator
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 308 constructing new tx simulator txid = [a9325251-c010-4ef0-8a8a-febd2e459f17]
2018-07-03 02:09:42.682 UTC [ccprovider] NewCCContext -> DEBU 309 NewCCCC (chain=mychannel,chaincode=vscc,version=1.1.1-snapshot-ff5e861,txid=a9325251-c010-4ef0-8a8a-febd2e459f17,syscc=true,proposal=0x0,canname=vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.682 UTC [chaincode] Launch -> DEBU 30a chaincode is running(no need to launch) : vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 30b Entry
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 30c chaincode canonical name: vscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.682 UTC [chaincode] sendExecuteMessage -> DEBU 30d [a9325251]Inside sendExecuteMessage. Message INIT
2018-07-03 02:09:42.682 UTC [chaincode] setChaincodeProposal -> DEBU 30e Setting chaincode proposal context...
2018-07-03 02:09:42.682 UTC [chaincode] sendExecuteMessage -> DEBU 30f [a9325251]sendExecuteMsg trigger event INIT
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 310 [a9325251]Move state message INIT
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 311 [a9325251]Fabric side Handling ChaincodeMessage of type: INIT in state ready
2018-07-03 02:09:42.682 UTC [chaincode] filterError -> DEBU 312 Ignoring NoTransitionError: no transition
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 313 [a9325251]sending state message INIT
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 314 [a9325251]Received message INIT from shim
2018-07-03 02:09:42.682 UTC [shim] handleMessage -> DEBU 315 [a9325251]Handling ChaincodeMessage of type: INIT(state:ready)
2018-07-03 02:09:42.682 UTC [shim] beforeInit -> DEBU 316 Entered state ready
2018-07-03 02:09:42.682 UTC [shim] beforeInit -> DEBU 317 [a9325251]Received INIT, initializing chaincode
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 318 [a9325251]Init get response status: 200
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 319 [a9325251]Init succeeded. Sending COMPLETED
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 31a [a9325251]Move state message COMPLETED
2018-07-03 02:09:42.682 UTC [shim] handleMessage -> DEBU 31b [a9325251]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 31c [a9325251]send state message COMPLETED
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 31d [a9325251]Received message COMPLETED from shim
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 31e [a9325251]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 31f [a9325251-c010-4ef0-8a8a-febd2e459f17]HandleMessage- COMPLETED. Notify
2018-07-03 02:09:42.682 UTC [chaincode] notify -> DEBU 320 notifying Txid:a9325251-c010-4ef0-8a8a-febd2e459f17, channelID:mychannel
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 321 Exit
2018-07-03 02:09:42.682 UTC [sccapi] deploySysCC -> INFO 322 system chaincode vscc/mychannel(github.com/hyperledger/fabric/core/scc/vscc) deployed
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] Done -> DEBU 323 Done with transaction simulation / query execution [a9325251-c010-4ef0-8a8a-febd2e459f17]
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 324 constructing new tx simulator
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 325 constructing new tx simulator txid = [37a5cab5-8659-44cc-85f5-1c906a0c42c3]
2018-07-03 02:09:42.682 UTC [ccprovider] NewCCContext -> DEBU 326 NewCCCC (chain=mychannel,chaincode=qscc,version=1.1.1-snapshot-ff5e861,txid=37a5cab5-8659-44cc-85f5-1c906a0c42c3,syscc=true,proposal=0x0,canname=qscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.682 UTC [chaincode] Launch -> DEBU 327 chaincode is running(no need to launch) : qscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 328 Entry
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 329 chaincode canonical name: qscc:1.1.1-snapshot-ff5e861
2018-07-03 02:09:42.682 UTC [chaincode] sendExecuteMessage -> DEBU 32a [37a5cab5]Inside sendExecuteMessage. Message INIT
2018-07-03 02:09:42.682 UTC [chaincode] setChaincodeProposal -> DEBU 32b Setting chaincode proposal context...
2018-07-03 02:09:42.682 UTC [chaincode] sendExecuteMessage -> DEBU 32c [37a5cab5]sendExecuteMsg trigger event INIT
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 32d [37a5cab5]Move state message INIT
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 32e [37a5cab5]Fabric side Handling ChaincodeMessage of type: INIT in state ready
2018-07-03 02:09:42.682 UTC [chaincode] filterError -> DEBU 32f Ignoring NoTransitionError: no transition
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 330 [37a5cab5]sending state message INIT
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 331 [37a5cab5]Received message INIT from shim
2018-07-03 02:09:42.682 UTC [shim] handleMessage -> DEBU 332 [37a5cab5]Handling ChaincodeMessage of type: INIT(state:ready)
2018-07-03 02:09:42.682 UTC [shim] beforeInit -> DEBU 333 Entered state ready
2018-07-03 02:09:42.682 UTC [shim] beforeInit -> DEBU 334 [37a5cab5]Received INIT, initializing chaincode
2018-07-03 02:09:42.682 UTC [qscc] Init -> INFO 335 Init QSCC
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 336 [37a5cab5]Init get response status: 200
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 337 [37a5cab5]Init succeeded. Sending COMPLETED
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 338 [37a5cab5]Move state message COMPLETED
2018-07-03 02:09:42.682 UTC [shim] handleMessage -> DEBU 339 [37a5cab5]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 33a [37a5cab5]send state message COMPLETED
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 33b [37a5cab5]Received message COMPLETED from shim
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 33c [37a5cab5]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 33d [37a5cab5-8659-44cc-85f5-1c906a0c42c3]HandleMessage- COMPLETED. Notify
2018-07-03 02:09:42.682 UTC [chaincode] notify -> DEBU 33e notifying Txid:37a5cab5-8659-44cc-85f5-1c906a0c42c3, channelID:mychannel
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 33f Exit
2018-07-03 02:09:42.682 UTC [sccapi] deploySysCC -> INFO 340 system chaincode qscc/mychannel(github.com/hyperledger/fabric/core/chaincode/qscc) deployed
2018-07-03 02:09:42.682 UTC [lockbasedtxmgr] Done -> DEBU 341 Done with transaction simulation / query execution [37a5cab5-8659-44cc-85f5-1c906a0c42c3]
2018-07-03 02:09:42.682 UTC [eventhub_producer] CreateBlockEvents -> DEBU 342 Entry
2018-07-03 02:09:42.682 UTC [eventhub_producer] CreateBlockEvents -> DEBU 343 Exit
2018-07-03 02:09:42.682 UTC [eventhub_producer] Send -> DEBU 344 Entry
2018-07-03 02:09:42.682 UTC [eventhub_producer] Send -> DEBU 345 Event processor timeout > 0
2018-07-03 02:09:42.682 UTC [eventhub_producer] Send -> DEBU 346 Event sent successfully
2018-07-03 02:09:42.682 UTC [eventhub_producer] Send -> DEBU 347 Exit
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 348 [7417df5c]Transaction completed. Sending COMPLETED
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 349 [7417df5c]Move state message COMPLETED
2018-07-03 02:09:42.682 UTC [shim] handleMessage -> DEBU 34a [7417df5c]Handling ChaincodeMessage of type: COMPLETED(state:ready)
2018-07-03 02:09:42.682 UTC [shim] func1 -> DEBU 34b [7417df5c]send state message COMPLETED
2018-07-03 02:09:42.682 UTC [chaincode] processStream -> DEBU 34c [7417df5c]Received message COMPLETED from shim
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 34d [7417df5c]Fabric side Handling ChaincodeMessage of type: COMPLETED in state ready
2018-07-03 02:09:42.682 UTC [chaincode] handleMessage -> DEBU 34e [7417df5c32ce8743d48cf4a2dc69b97d8144543231d60271a180cbf50373e948]HandleMessage- COMPLETED. Notify
2018-07-03 02:09:42.682 UTC [chaincode] notify -> DEBU 34f notifying Txid:7417df5c32ce8743d48cf4a2dc69b97d8144543231d60271a180cbf50373e948, channelID:
2018-07-03 02:09:42.682 UTC [chaincode] Execute -> DEBU 350 Exit
2018-07-03 02:09:42.682 UTC [endorser] callChaincode -> DEBU 351 [][7417df5c] Exit
2018-07-03 02:09:42.682 UTC [endorser] simulateProposal -> DEBU 352 [][7417df5c] Exit
2018-07-03 02:09:42.682 UTC [endorser] ProcessProposal -> DEBU 353 Exit: request from%!(EXTRA string=172.18.0.7:52576)

