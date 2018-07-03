2018-07-03 02:16:31.364 UTC [blocksProvider] DeliverBlocks -> DEBU 35b [mychannel] Adding payload locally, buffer seqNum = [1], peers number [1]
2018-07-03 02:16:31.365 UTC [blocksProvider] DeliverBlocks -> DEBU 35c [mychannel] Gossiping block [1], peers number [1]
2018-07-03 02:16:31.365 UTC [committer/txvalidator] Validate -> DEBU 35d START Block Validation
2018-07-03 02:16:31.365 UTC [committer/txvalidator] Validate -> DEBU 35e expecting 1 block validation responses
2018-07-03 02:16:31.365 UTC [committer/txvalidator] validateTx -> DEBU 35f validateTx starts for block 0xc422c9b6e0 env 0xc422281020 txn 0
2018-07-03 02:16:31.365 UTC [protoutils] ValidateTransaction -> DEBU 360 ValidateTransactionEnvelope starts for envelope 0xc422281020
2018-07-03 02:16:31.365 UTC [protoutils] ValidateTransaction -> DEBU 361 Header is channel_header:"\010\001\032\006\010\377\270\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030\240\207\201hQ\352\201\237\235K\264\024\016U\335]P\311\372^\267^\241}" 
2018-07-03 02:16:31.365 UTC [protoutils] validateChannelHeader -> DEBU 362 validateChannelHeader info: header type 1
2018-07-03 02:16:31.365 UTC [protoutils] checkSignatureFromCreator -> DEBU 363 begin
2018-07-03 02:16:31.365 UTC [protoutils] checkSignatureFromCreator -> DEBU 364 creator is &{OrdererMSP db39cb7220c50c0deea1ae60f6dd1d682369376b27b7a2ba8628646877fd38ea}
2018-07-03 02:16:31.365 UTC [protoutils] checkSignatureFromCreator -> DEBU 365 creator is valid
2018-07-03 02:16:31.365 UTC [protoutils] checkSignatureFromCreator -> DEBU 366 exits successfully
2018-07-03 02:16:31.365 UTC [protoutils] validateConfigTransaction -> DEBU 367 validateConfigTransaction starts for data 0xc421f1c000, header channel_header:"\010\001\032\006\010\377\270\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030\240\207\201hQ\352\201\237\235K\264\024\016U\335]P\311\372^\267^\241}" 
2018-07-03 02:16:31.365 UTC [committer/txvalidator] validateTx -> DEBU 368 Transaction is for channel mychannel
2018-07-03 02:16:31.365 UTC [common/configtx] addToMap -> DEBU 369 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.365 UTC [common/configtx] addToMap -> DEBU 36a Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.365 UTC [common/configtx] addToMap -> DEBU 36b Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 36c Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 36d Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 36e Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 36f Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 370 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 371 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 372 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 373 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 374 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 375 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 376 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.366 UTC [common/configtx] addToMap -> DEBU 377 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.366 UTC [common/configtx] verifyDeltaSet -> DEBU 378 Processing change to key: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.366 UTC [common/configtx] policyForItem -> DEBU 379 Getting policy for item Org1MSP with mod_policy Admins
2018-07-03 02:16:31.366 UTC [common/configtx] verifyDeltaSet -> DEBU 37a Processing change to key: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 37b Setting policy for key Admins to 
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 37c Setting policy for key Readers to 
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 37d Setting policy for key Writers to 
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 37e Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 37f Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 380 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.366 UTC [common/configtx] recurseConfigMap -> DEBU 381 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 382 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 383 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 384 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 385 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 386 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 387 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 388 Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 389 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 38a Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 38b Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 38c Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/configtx] recurseConfigMap -> DEBU 38d Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.367 UTC [common/channelconfig] NewStandardValues -> DEBU 38e Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 38f Processing field: HashingAlgorithm
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 390 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 391 Processing field: OrdererAddresses
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 392 Processing field: Consortium
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 393 Processing field: Capabilities
2018-07-03 02:16:31.367 UTC [common/channelconfig] NewStandardValues -> DEBU 394 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 395 Processing field: ConsensusType
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 396 Processing field: BatchSize
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 397 Processing field: BatchTimeout
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 398 Processing field: KafkaBrokers
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 399 Processing field: ChannelRestrictions
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39a Processing field: Capabilities
2018-07-03 02:16:31.367 UTC [common/channelconfig] NewStandardValues -> DEBU 39b Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.367 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39c Processing field: MSP
2018-07-03 02:16:31.367 UTC [common/channelconfig] validateMSP -> DEBU 39d Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.368 UTC [common/channelconfig] NewStandardValues -> DEBU 39e Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39f Processing field: Capabilities
2018-07-03 02:16:31.368 UTC [common/channelconfig] NewStandardValues -> DEBU 3a0 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a1 Processing field: AnchorPeers
2018-07-03 02:16:31.368 UTC [common/channelconfig] NewStandardValues -> DEBU 3a2 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a3 Processing field: MSP
2018-07-03 02:16:31.368 UTC [common/channelconfig] Validate -> DEBU 3a4 Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.368 UTC [common/channelconfig] validateMSP -> DEBU 3a5 Setting up MSP for org Org2MSP
2018-07-03 02:16:31.380 UTC [common/channelconfig] NewStandardValues -> DEBU 3a6 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.380 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a7 Processing field: AnchorPeers
2018-07-03 02:16:31.380 UTC [common/channelconfig] NewStandardValues -> DEBU 3a8 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.380 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a9 Processing field: MSP
2018-07-03 02:16:31.380 UTC [common/channelconfig] Validate -> DEBU 3aa Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.380 UTC [common/channelconfig] validateMSP -> DEBU 3ab Setting up MSP for org Org1MSP
2018-07-03 02:16:31.381 UTC [common/configtx] addToMap -> DEBU 3ac Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.381 UTC [common/configtx] addToMap -> DEBU 3ad Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.381 UTC [common/configtx] addToMap -> DEBU 3ae Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.382 UTC [common/configtx] addToMap -> DEBU 3af Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.382 UTC [common/configtx] addToMap -> DEBU 3b0 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.382 UTC [common/configtx] addToMap -> DEBU 3b1 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.382 UTC [common/configtx] addToMap -> DEBU 3b2 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b3 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b4 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b5 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b6 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b7 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b8 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3b9 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3ba Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3bb Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3bc Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3bd Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.391 UTC [common/configtx] addToMap -> DEBU 3be Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3bf Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c0 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c1 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c2 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c3 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c4 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c5 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c6 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c7 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c8 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3c9 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3ca Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3cb Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3cc Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3cd Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3ce Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3cf Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3d0 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3d1 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3d2 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3d3 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.392 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d4 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:31.392 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d5 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:31.392 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d6 As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:31.392 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d7 As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:31.392 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d8 As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:31.392 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d9 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:31.392 UTC [common/capabilities] Supported -> DEBU 3da Application capability V1_1 is supported and is enabled
2018-07-03 02:16:31.392 UTC [common/capabilities] Supported -> DEBU 3db Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:31.392 UTC [common/configtx] addToMap -> DEBU 3dc Adding to config map: [Group]  /Resources
2018-07-03 02:16:31.393 UTC [peer] updateTrustedRoots -> DEBU 3dd Updating trusted root authorities for channel mychannel
2018-07-03 02:16:31.393 UTC [peer] buildTrustedRootsForChain -> DEBU 3de updating root CAs for channel [mychannel]
2018-07-03 02:16:31.393 UTC [peer] buildTrustedRootsForChain -> DEBU 3df adding app root CAs for MSP [Org1MSP]
2018-07-03 02:16:31.393 UTC [peer] buildTrustedRootsForChain -> DEBU 3e0 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:16:31.393 UTC [peer] buildTrustedRootsForChain -> DEBU 3e1 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:16:31.393 UTC [committer/txvalidator] validateTx -> DEBU 3e2 config transaction received for chain mychannel
2018-07-03 02:16:31.393 UTC [committer/txvalidator] validateTx -> DEBU 3e3 validateTx completes for block 0xc422c9b6e0 env 0xc422281020 txn 0
2018-07-03 02:16:31.393 UTC [committer/txvalidator] Validate -> DEBU 3e4 got result for idx 0, code 0
2018-07-03 02:16:31.393 UTC [committer/txvalidator] Validate -> DEBU 3e5 END Block Validation
2018-07-03 02:16:31.394 UTC [committer] preCommit -> DEBU 3e6 Received configuration update, calling CSCC ConfigUpdate
2018-07-03 02:16:31.394 UTC [kvledger] CommitWithPvtData -> DEBU 3e7 Channel [mychannel]: Validating state for block [1]
2018-07-03 02:16:31.394 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 3e8 Validating new block with num trans = [1]
2018-07-03 02:16:31.394 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 3e9 ValidateAndPrepareBatch() for block number = [1]
2018-07-03 02:16:31.394 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 3ea preprocessing ProtoBlock...
2018-07-03 02:16:31.394 UTC [valimpl] preprocessProtoBlock -> DEBU 3eb txType=CONFIG
2018-07-03 02:16:31.394 UTC [valimpl] processNonEndorserTx -> DEBU 3ec Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:16:31.394 UTC [valimpl] processNonEndorserTx -> DEBU 3ed Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:16:31.394 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 3ee constructing new tx simulator
2018-07-03 02:16:31.394 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 3ef constructing new tx simulator txid = []
2018-07-03 02:16:31.394 UTC [peer] GenerateSimulationResults -> DEBU 3f0 Processing CONFIG
2018-07-03 02:16:31.394 UTC [peer] processChannelConfigTx -> DEBU 3f1 channelConfig=sequence:2 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org1.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:16:31.395 UTC [common/channelconfig] NewStandardValues -> DEBU 3f2 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f3 Processing field: HashingAlgorithm
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f4 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f5 Processing field: OrdererAddresses
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f6 Processing field: Consortium
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f7 Processing field: Capabilities
2018-07-03 02:16:31.395 UTC [common/channelconfig] NewStandardValues -> DEBU 3f8 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f9 Processing field: Capabilities
2018-07-03 02:16:31.395 UTC [common/channelconfig] NewStandardValues -> DEBU 3fa Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3fb Processing field: AnchorPeers
2018-07-03 02:16:31.395 UTC [common/channelconfig] NewStandardValues -> DEBU 3fc Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.395 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3fd Processing field: MSP
2018-07-03 02:16:31.395 UTC [common/channelconfig] Validate -> DEBU 3fe Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.395 UTC [common/channelconfig] validateMSP -> DEBU 3ff Setting up MSP for org Org2MSP
2018-07-03 02:16:31.399 UTC [common/channelconfig] NewStandardValues -> DEBU 400 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 401 Processing field: AnchorPeers
2018-07-03 02:16:31.399 UTC [common/channelconfig] NewStandardValues -> DEBU 402 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 403 Processing field: MSP
2018-07-03 02:16:31.399 UTC [common/channelconfig] Validate -> DEBU 404 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.399 UTC [common/channelconfig] validateMSP -> DEBU 405 Setting up MSP for org Org1MSP
2018-07-03 02:16:31.399 UTC [common/channelconfig] NewStandardValues -> DEBU 406 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 407 Processing field: ConsensusType
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 408 Processing field: BatchSize
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 409 Processing field: BatchTimeout
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40a Processing field: KafkaBrokers
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40b Processing field: ChannelRestrictions
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40c Processing field: Capabilities
2018-07-03 02:16:31.399 UTC [common/channelconfig] NewStandardValues -> DEBU 40d Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.399 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40e Processing field: MSP
2018-07-03 02:16:31.399 UTC [common/channelconfig] validateMSP -> DEBU 40f Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 410 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 411 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 412 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 413 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 414 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 415 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 416 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 417 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 418 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 419 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 41a Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 41b Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 41c Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 41d Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 41e Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 41f Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 420 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 421 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 422 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 423 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 424 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 425 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 426 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 427 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 428 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 429 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 42a Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 42b Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 42c Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 42d Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 42e Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.400 UTC [common/configtx] addToMap -> DEBU 42f Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 430 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 431 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 432 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 433 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 434 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 435 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 436 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.401 UTC [common/configtx] addToMap -> DEBU 437 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.403 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 438 Simulation completed, getting simulation results
2018-07-03 02:16:31.403 UTC [lockbasedtxmgr] Done -> DEBU 439 Done with transaction simulation / query execution []
2018-07-03 02:16:31.403 UTC [lockbasedtxmgr] Done -> DEBU 43a Done with transaction simulation / query execution []
2018-07-03 02:16:31.403 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 43b Block [1] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:16:31.403 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 43c validating rwset...
2018-07-03 02:16:31.403 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 43d postprocessing ProtoBlock...
2018-07-03 02:16:31.403 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 43e ValidateAndPrepareBatch() complete
2018-07-03 02:16:31.403 UTC [kvledger] CommitWithPvtData -> DEBU 43f Channel [mychannel]: Committing block [1] to storage
2018-07-03 02:16:31.405 UTC [pvtdatastorage] Prepare -> DEBU 440 Saved 0 private data write sets for block [1]
2018-07-03 02:16:31.406 UTC [fsblkstorage] indexBlock -> DEBU 441 Indexing block [blockNum=1, blockHash=[]byte{0xba, 0xb0, 0xc4, 0xd9, 0x17, 0xd9, 0x32, 0xdd, 0x7c, 0x12, 0x95, 0x81, 0x1c, 0xb4, 0x7e, 0xbe, 0xe1, 0x3e, 0xaf, 0x98, 0x43, 0x2, 0x9b, 0x37, 0xe6, 0xfd, 0x26, 0xd2, 0x95, 0x9d, 0x3e, 0xd7} txOffsets=
txId= locPointer=offset=71, bytesLength=15610
]
2018-07-03 02:16:31.406 UTC [fsblkstorage] indexBlock -> DEBU 442 Adding txLoc [fileSuffixNum=0, offset=15721, bytesLength=15610] for tx ID: [] to index
2018-07-03 02:16:31.406 UTC [fsblkstorage] indexBlock -> DEBU 443 Adding txLoc [fileSuffixNum=0, offset=15721, bytesLength=15610] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:16:31.407 UTC [fsblkstorage] updateCheckpoint -> DEBU 444 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[33127], isChainEmpty=[false], lastBlockNumber=[1]
2018-07-03 02:16:31.407 UTC [pvtdatastorage] Commit -> DEBU 445 Committing private data for block [1]
2018-07-03 02:16:31.408 UTC [pvtdatastorage] Commit -> DEBU 446 Committed private data for block [1]
2018-07-03 02:16:31.408 UTC [kvledger] CommitWithPvtData -> INFO 447 Channel [mychannel]: Committed block [1] with 1 transaction(s)
2018-07-03 02:16:31.408 UTC [kvledger] CommitWithPvtData -> DEBU 448 Channel [mychannel]: Committing block [1] transactions to state database
2018-07-03 02:16:31.408 UTC [lockbasedtxmgr] Commit -> DEBU 449 Committing updates to state database
2018-07-03 02:16:31.408 UTC [lockbasedtxmgr] Commit -> DEBU 44a Write lock acquired for committing updates to state database
2018-07-03 02:16:31.408 UTC [stateleveldb] ApplyUpdates -> DEBU 44b Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:16:31.409 UTC [lockbasedtxmgr] Commit -> DEBU 44c Updates committed to state database
2018-07-03 02:16:31.409 UTC [kvledger] CommitWithPvtData -> DEBU 44d Channel [mychannel]: Committing block [1] transactions to history database
2018-07-03 02:16:31.409 UTC [historyleveldb] Commit -> DEBU 44e Channel [mychannel]: Updating history database for blockNo [1] with [1] transactions
2018-07-03 02:16:31.409 UTC [historyleveldb] Commit -> DEBU 44f Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:16:31.411 UTC [historyleveldb] Commit -> DEBU 450 Channel [mychannel]: Updates committed to history database for blockNo [1]
2018-07-03 02:16:31.411 UTC [eventhub_producer] CreateBlockEvents -> DEBU 451 Entry
2018-07-03 02:16:31.411 UTC [eventhub_producer] CreateBlockEvents -> DEBU 452 Exit
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 453 Entry
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 454 Event processor timeout > 0
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 455 Event sent successfully
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 456 Exit
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 457 Entry
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 458 Event processor timeout > 0
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 459 Event sent successfully
2018-07-03 02:16:31.411 UTC [eventhub_producer] Send -> DEBU 45a Exit
2018-07-03 02:16:34.510 UTC [blocksProvider] DeliverBlocks -> DEBU 45b [mychannel] Adding payload locally, buffer seqNum = [2], peers number [3]
2018-07-03 02:16:34.511 UTC [blocksProvider] DeliverBlocks -> DEBU 45c [mychannel] Gossiping block [2], peers number [3]
2018-07-03 02:16:34.511 UTC [committer/txvalidator] Validate -> DEBU 45d START Block Validation
2018-07-03 02:16:34.511 UTC [committer/txvalidator] Validate -> DEBU 45e expecting 1 block validation responses
2018-07-03 02:16:34.511 UTC [committer/txvalidator] validateTx -> DEBU 45f validateTx starts for block 0xc4236d1300 env 0xc421a5de90 txn 0
2018-07-03 02:16:34.511 UTC [protoutils] ValidateTransaction -> DEBU 460 ValidateTransactionEnvelope starts for envelope 0xc421a5de90
2018-07-03 02:16:34.511 UTC [protoutils] ValidateTransaction -> DEBU 461 Header is channel_header:"\010\001\032\006\010\202\271\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030O\347\311\342\252\030\364\325C\224\026\305\212M4&J\215\t(U\277\334P" 
2018-07-03 02:16:34.511 UTC [protoutils] validateChannelHeader -> DEBU 462 validateChannelHeader info: header type 1
2018-07-03 02:16:34.511 UTC [protoutils] checkSignatureFromCreator -> DEBU 463 begin
2018-07-03 02:16:34.511 UTC [protoutils] checkSignatureFromCreator -> DEBU 464 creator is &{OrdererMSP db39cb7220c50c0deea1ae60f6dd1d682369376b27b7a2ba8628646877fd38ea}
2018-07-03 02:16:34.511 UTC [protoutils] checkSignatureFromCreator -> DEBU 465 creator is valid
2018-07-03 02:16:34.511 UTC [protoutils] checkSignatureFromCreator -> DEBU 466 exits successfully
2018-07-03 02:16:34.511 UTC [protoutils] validateConfigTransaction -> DEBU 467 validateConfigTransaction starts for data 0xc422a04000, header channel_header:"\010\001\032\006\010\202\271\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030O\347\311\342\252\030\364\325C\224\026\305\212M4&J\215\t(U\277\334P" 
2018-07-03 02:16:34.511 UTC [committer/txvalidator] validateTx -> DEBU 468 Transaction is for channel mychannel
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 469 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 46a Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 46b Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 46c Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 46d Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 46e Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 46f Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 470 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 471 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 472 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 473 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 474 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 475 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 476 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.511 UTC [common/configtx] addToMap -> DEBU 477 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.511 UTC [common/configtx] verifyDeltaSet -> DEBU 478 Processing change to key: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.511 UTC [common/configtx] policyForItem -> DEBU 479 Getting policy for item Org2MSP with mod_policy Admins
2018-07-03 02:16:34.512 UTC [common/configtx] verifyDeltaSet -> DEBU 47a Processing change to key: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 47b Setting policy for key Admins to 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 47c Setting policy for key Readers to 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 47d Setting policy for key Writers to 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 47e Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 47f Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 480 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 481 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 482 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 483 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 484 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 485 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 486 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 487 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 488 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 489 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 48a Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 48b Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 48c Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/configtx] recurseConfigMap -> DEBU 48d Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.516 UTC [common/channelconfig] NewStandardValues -> DEBU 48e Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 48f Processing field: HashingAlgorithm
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 490 Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 491 Processing field: OrdererAddresses
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 492 Processing field: Consortium
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 493 Processing field: Capabilities
2018-07-03 02:16:34.516 UTC [common/channelconfig] NewStandardValues -> DEBU 494 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 495 Processing field: Capabilities
2018-07-03 02:16:34.516 UTC [common/channelconfig] NewStandardValues -> DEBU 496 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 497 Processing field: AnchorPeers
2018-07-03 02:16:34.516 UTC [common/channelconfig] NewStandardValues -> DEBU 498 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.516 UTC [common/channelconfig] initializeProtosStruct -> DEBU 499 Processing field: MSP
2018-07-03 02:16:34.516 UTC [common/channelconfig] Validate -> DEBU 49a Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.516 UTC [common/channelconfig] validateMSP -> DEBU 49b Setting up MSP for org Org2MSP
2018-07-03 02:16:34.517 UTC [common/channelconfig] NewStandardValues -> DEBU 49c Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.517 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49d Processing field: AnchorPeers
2018-07-03 02:16:34.517 UTC [common/channelconfig] NewStandardValues -> DEBU 49e Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.517 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49f Processing field: MSP
2018-07-03 02:16:34.517 UTC [common/channelconfig] Validate -> DEBU 4a0 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.517 UTC [common/channelconfig] validateMSP -> DEBU 4a1 Setting up MSP for org Org1MSP
2018-07-03 02:16:34.526 UTC [common/channelconfig] NewStandardValues -> DEBU 4a2 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a3 Processing field: ConsensusType
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a4 Processing field: BatchSize
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a5 Processing field: BatchTimeout
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a6 Processing field: KafkaBrokers
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a7 Processing field: ChannelRestrictions
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a8 Processing field: Capabilities
2018-07-03 02:16:34.526 UTC [common/channelconfig] NewStandardValues -> DEBU 4a9 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.526 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4aa Processing field: MSP
2018-07-03 02:16:34.526 UTC [common/channelconfig] validateMSP -> DEBU 4ab Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4ac Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4ad Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4ae Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4af Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b0 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b1 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b2 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b3 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b4 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b5 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b6 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b7 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b8 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4b9 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4ba Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4bb Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4bc Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4bd Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.527 UTC [common/configtx] addToMap -> DEBU 4be Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4bf Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c0 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c1 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c2 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c3 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c4 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c5 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c6 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c7 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c8 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4c9 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4ca Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4cb Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4cc Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4cd Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4ce Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4cf Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4d0 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4d1 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4d2 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4d3 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4d4 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.528 UTC [common/channelconfig] LogSanityChecks -> DEBU 4d5 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:34.528 UTC [common/channelconfig] LogSanityChecks -> DEBU 4d6 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:34.528 UTC [common/channelconfig] LogSanityChecks -> DEBU 4d7 As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:34.528 UTC [common/channelconfig] LogSanityChecks -> DEBU 4d8 As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:34.528 UTC [common/channelconfig] LogSanityChecks -> DEBU 4d9 As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:34.528 UTC [common/channelconfig] LogSanityChecks -> DEBU 4da As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:34.528 UTC [common/capabilities] Supported -> DEBU 4db Application capability V1_1 is supported and is enabled
2018-07-03 02:16:34.528 UTC [common/capabilities] Supported -> DEBU 4dc Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:34.528 UTC [common/configtx] addToMap -> DEBU 4dd Adding to config map: [Group]  /Resources
2018-07-03 02:16:34.537 UTC [peer] updateTrustedRoots -> DEBU 4de Updating trusted root authorities for channel mychannel
2018-07-03 02:16:34.542 UTC [peer] buildTrustedRootsForChain -> DEBU 4df updating root CAs for channel [mychannel]
2018-07-03 02:16:34.542 UTC [peer] buildTrustedRootsForChain -> DEBU 4e0 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:16:34.543 UTC [peer] buildTrustedRootsForChain -> DEBU 4e1 adding app root CAs for MSP [Org1MSP]
2018-07-03 02:16:34.543 UTC [peer] buildTrustedRootsForChain -> DEBU 4e2 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:16:34.543 UTC [committer/txvalidator] validateTx -> DEBU 4e3 config transaction received for chain mychannel
2018-07-03 02:16:34.543 UTC [committer/txvalidator] validateTx -> DEBU 4e4 validateTx completes for block 0xc4236d1300 env 0xc421a5de90 txn 0
2018-07-03 02:16:34.543 UTC [committer/txvalidator] Validate -> DEBU 4e5 got result for idx 0, code 0
2018-07-03 02:16:34.543 UTC [committer/txvalidator] Validate -> DEBU 4e6 END Block Validation
2018-07-03 02:16:34.543 UTC [committer] preCommit -> DEBU 4e7 Received configuration update, calling CSCC ConfigUpdate
2018-07-03 02:16:34.543 UTC [kvledger] CommitWithPvtData -> DEBU 4e8 Channel [mychannel]: Validating state for block [2]
2018-07-03 02:16:34.543 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 4e9 Validating new block with num trans = [1]
2018-07-03 02:16:34.543 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 4ea ValidateAndPrepareBatch() for block number = [2]
2018-07-03 02:16:34.543 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 4eb preprocessing ProtoBlock...
2018-07-03 02:16:34.543 UTC [valimpl] preprocessProtoBlock -> DEBU 4ec txType=CONFIG
2018-07-03 02:16:34.543 UTC [valimpl] processNonEndorserTx -> DEBU 4ed Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:16:34.543 UTC [valimpl] processNonEndorserTx -> DEBU 4ee Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:16:34.543 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 4ef constructing new tx simulator
2018-07-03 02:16:34.543 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 4f0 constructing new tx simulator txid = []
2018-07-03 02:16:34.543 UTC [peer] GenerateSimulationResults -> DEBU 4f1 Processing CONFIG
2018-07-03 02:16:34.544 UTC [peer] processChannelConfigTx -> DEBU 4f2 channelConfig=sequence:3 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org1.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org2.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:16:34.580 UTC [common/channelconfig] NewStandardValues -> DEBU 4f3 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f4 Processing field: HashingAlgorithm
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f5 Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f6 Processing field: OrdererAddresses
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f7 Processing field: Consortium
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f8 Processing field: Capabilities
2018-07-03 02:16:34.580 UTC [common/channelconfig] NewStandardValues -> DEBU 4f9 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4fa Processing field: ConsensusType
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4fb Processing field: BatchSize
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4fc Processing field: BatchTimeout
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4fd Processing field: KafkaBrokers
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4fe Processing field: ChannelRestrictions
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ff Processing field: Capabilities
2018-07-03 02:16:34.580 UTC [common/channelconfig] NewStandardValues -> DEBU 500 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.580 UTC [common/channelconfig] initializeProtosStruct -> DEBU 501 Processing field: MSP
2018-07-03 02:16:34.580 UTC [common/channelconfig] validateMSP -> DEBU 502 Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.581 UTC [common/channelconfig] NewStandardValues -> DEBU 503 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.581 UTC [common/channelconfig] initializeProtosStruct -> DEBU 504 Processing field: Capabilities
2018-07-03 02:16:34.581 UTC [common/channelconfig] NewStandardValues -> DEBU 505 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.581 UTC [common/channelconfig] initializeProtosStruct -> DEBU 506 Processing field: AnchorPeers
2018-07-03 02:16:34.581 UTC [common/channelconfig] NewStandardValues -> DEBU 507 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.581 UTC [common/channelconfig] initializeProtosStruct -> DEBU 508 Processing field: MSP
2018-07-03 02:16:34.581 UTC [common/channelconfig] Validate -> DEBU 509 Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.581 UTC [common/channelconfig] validateMSP -> DEBU 50a Setting up MSP for org Org2MSP
2018-07-03 02:16:34.583 UTC [common/channelconfig] NewStandardValues -> DEBU 50b Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.583 UTC [common/channelconfig] initializeProtosStruct -> DEBU 50c Processing field: AnchorPeers
2018-07-03 02:16:34.583 UTC [common/channelconfig] NewStandardValues -> DEBU 50d Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.583 UTC [common/channelconfig] initializeProtosStruct -> DEBU 50e Processing field: MSP
2018-07-03 02:16:34.583 UTC [common/channelconfig] Validate -> DEBU 50f Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.583 UTC [common/channelconfig] validateMSP -> DEBU 510 Setting up MSP for org Org1MSP
2018-07-03 02:16:34.584 UTC [common/configtx] addToMap -> DEBU 511 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.584 UTC [common/configtx] addToMap -> DEBU 512 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 513 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 514 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 515 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 516 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 517 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 518 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 519 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 51a Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 51b Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 51c Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 51d Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 51e Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 51f Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 520 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 521 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 522 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 523 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 524 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 525 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 526 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 527 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 528 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 529 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 52a Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 52b Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 52c Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 52d Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 52e Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 52f Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 530 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 531 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 532 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 533 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 534 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 535 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 536 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 537 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 538 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.585 UTC [common/configtx] addToMap -> DEBU 539 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.586 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 53a Simulation completed, getting simulation results
2018-07-03 02:16:34.586 UTC [lockbasedtxmgr] Done -> DEBU 53b Done with transaction simulation / query execution []
2018-07-03 02:16:34.586 UTC [lockbasedtxmgr] Done -> DEBU 53c Done with transaction simulation / query execution []
2018-07-03 02:16:34.586 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 53d Block [2] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:16:34.586 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 53e validating rwset...
2018-07-03 02:16:34.586 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 53f postprocessing ProtoBlock...
2018-07-03 02:16:34.586 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 540 ValidateAndPrepareBatch() complete
2018-07-03 02:16:34.586 UTC [kvledger] CommitWithPvtData -> DEBU 541 Channel [mychannel]: Committing block [2] to storage
2018-07-03 02:16:34.587 UTC [pvtdatastorage] Prepare -> DEBU 542 Saved 0 private data write sets for block [2]
2018-07-03 02:16:34.588 UTC [fsblkstorage] indexBlock -> DEBU 543 Indexing block [blockNum=2, blockHash=[]byte{0x22, 0x8d, 0x20, 0xe, 0xe2, 0x5c, 0xa0, 0x3c, 0xd0, 0x74, 0xe9, 0x2d, 0x10, 0x62, 0xf4, 0xb8, 0x5c, 0x9, 0x54, 0xb6, 0x3d, 0xb0, 0x60, 0x23, 0x3b, 0xa0, 0xe3, 0x9b, 0x27, 0xfa, 0xf6, 0xa8} txOffsets=
txId= locPointer=offset=71, bytesLength=15669
]
2018-07-03 02:16:34.588 UTC [fsblkstorage] indexBlock -> DEBU 544 Adding txLoc [fileSuffixNum=0, offset=33198, bytesLength=15669] for tx ID: [] to index
2018-07-03 02:16:34.588 UTC [fsblkstorage] indexBlock -> DEBU 545 Adding txLoc [fileSuffixNum=0, offset=33198, bytesLength=15669] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:16:34.592 UTC [fsblkstorage] updateCheckpoint -> DEBU 546 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[50661], isChainEmpty=[false], lastBlockNumber=[2]
2018-07-03 02:16:34.592 UTC [pvtdatastorage] Commit -> DEBU 547 Committing private data for block [2]
2018-07-03 02:16:34.593 UTC [pvtdatastorage] Commit -> DEBU 548 Committed private data for block [2]
2018-07-03 02:16:34.593 UTC [kvledger] CommitWithPvtData -> INFO 549 Channel [mychannel]: Committed block [2] with 1 transaction(s)
2018-07-03 02:16:34.593 UTC [kvledger] CommitWithPvtData -> DEBU 54a Channel [mychannel]: Committing block [2] transactions to state database
2018-07-03 02:16:34.594 UTC [lockbasedtxmgr] Commit -> DEBU 54b Committing updates to state database
2018-07-03 02:16:34.594 UTC [lockbasedtxmgr] Commit -> DEBU 54c Write lock acquired for committing updates to state database
2018-07-03 02:16:34.594 UTC [stateleveldb] ApplyUpdates -> DEBU 54d Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:16:34.596 UTC [lockbasedtxmgr] Commit -> DEBU 54e Updates committed to state database
2018-07-03 02:16:34.597 UTC [kvledger] CommitWithPvtData -> DEBU 54f Channel [mychannel]: Committing block [2] transactions to history database
2018-07-03 02:16:34.597 UTC [historyleveldb] Commit -> DEBU 550 Channel [mychannel]: Updating history database for blockNo [2] with [1] transactions
2018-07-03 02:16:34.597 UTC [historyleveldb] Commit -> DEBU 551 Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:16:34.598 UTC [historyleveldb] Commit -> DEBU 552 Channel [mychannel]: Updates committed to history database for blockNo [2]
2018-07-03 02:16:34.598 UTC [eventhub_producer] CreateBlockEvents -> DEBU 553 Entry
2018-07-03 02:16:34.598 UTC [eventhub_producer] CreateBlockEvents -> DEBU 554 Exit
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 555 Entry
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 556 Event processor timeout > 0
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 557 Event sent successfully
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 558 Exit
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 559 Entry
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 55a Event processor timeout > 0
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 55b Event sent successfully
2018-07-03 02:16:34.598 UTC [eventhub_producer] Send -> DEBU 55c Exit


