2018-07-03 02:16:31.359 UTC [blocksProvider] DeliverBlocks -> DEBU 36e [mychannel] Adding payload locally, buffer seqNum = [1], peers number [1]
2018-07-03 02:16:31.360 UTC [blocksProvider] DeliverBlocks -> DEBU 36f [mychannel] Gossiping block [1], peers number [1]
2018-07-03 02:16:31.363 UTC [committer/txvalidator] Validate -> DEBU 370 START Block Validation
2018-07-03 02:16:31.363 UTC [committer/txvalidator] Validate -> DEBU 371 expecting 1 block validation responses
2018-07-03 02:16:31.363 UTC [committer/txvalidator] validateTx -> DEBU 372 validateTx starts for block 0xc421f183c0 env 0xc421d96f00 txn 0
2018-07-03 02:16:31.363 UTC [protoutils] ValidateTransaction -> DEBU 373 ValidateTransactionEnvelope starts for envelope 0xc421d96f00
2018-07-03 02:16:31.363 UTC [protoutils] ValidateTransaction -> DEBU 374 Header is channel_header:"\010\001\032\006\010\377\270\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030\240\207\201hQ\352\201\237\235K\264\024\016U\335]P\311\372^\267^\241}" 
2018-07-03 02:16:31.363 UTC [protoutils] validateChannelHeader -> DEBU 375 validateChannelHeader info: header type 1
2018-07-03 02:16:31.363 UTC [protoutils] checkSignatureFromCreator -> DEBU 376 begin
2018-07-03 02:16:31.363 UTC [protoutils] checkSignatureFromCreator -> DEBU 377 creator is &{OrdererMSP db39cb7220c50c0deea1ae60f6dd1d682369376b27b7a2ba8628646877fd38ea}
2018-07-03 02:16:31.363 UTC [protoutils] checkSignatureFromCreator -> DEBU 378 creator is valid
2018-07-03 02:16:31.363 UTC [protoutils] checkSignatureFromCreator -> DEBU 379 exits successfully
2018-07-03 02:16:31.363 UTC [protoutils] validateConfigTransaction -> DEBU 37a validateConfigTransaction starts for data 0xc422690000, header channel_header:"\010\001\032\006\010\377\270\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030\240\207\201hQ\352\201\237\235K\264\024\016U\335]P\311\372^\267^\241}" 
2018-07-03 02:16:31.363 UTC [committer/txvalidator] validateTx -> DEBU 37b Transaction is for channel mychannel
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 37c Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 37d Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 37e Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 37f Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 380 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 381 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 382 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 383 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 384 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 385 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 386 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 387 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 388 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 389 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.364 UTC [common/configtx] addToMap -> DEBU 38a Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.364 UTC [common/configtx] verifyDeltaSet -> DEBU 38b Processing change to key: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.364 UTC [common/configtx] policyForItem -> DEBU 38c Getting policy for item Org1MSP with mod_policy Admins
2018-07-03 02:16:31.364 UTC [common/configtx] verifyDeltaSet -> DEBU 38d Processing change to key: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.364 UTC [common/configtx] recurseConfigMap -> DEBU 38e Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 38f Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 390 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 391 Setting policy for key Admins to 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 392 Setting policy for key Readers to 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 393 Setting policy for key Writers to 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 394 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 395 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 396 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 397 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 398 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 399 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 39a Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 39b Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 39c Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 39d Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 39e Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 39f Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/configtx] recurseConfigMap -> DEBU 3a0 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.365 UTC [common/channelconfig] NewStandardValues -> DEBU 3a1 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a2 Processing field: HashingAlgorithm
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a3 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a4 Processing field: OrdererAddresses
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a5 Processing field: Consortium
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a6 Processing field: Capabilities
2018-07-03 02:16:31.365 UTC [common/channelconfig] NewStandardValues -> DEBU 3a7 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a8 Processing field: Capabilities
2018-07-03 02:16:31.365 UTC [common/channelconfig] NewStandardValues -> DEBU 3a9 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3aa Processing field: AnchorPeers
2018-07-03 02:16:31.365 UTC [common/channelconfig] NewStandardValues -> DEBU 3ab Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.365 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ac Processing field: MSP
2018-07-03 02:16:31.365 UTC [common/channelconfig] Validate -> DEBU 3ad Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.365 UTC [common/channelconfig] validateMSP -> DEBU 3ae Setting up MSP for org Org2MSP
2018-07-03 02:16:31.366 UTC [common/channelconfig] NewStandardValues -> DEBU 3af Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.366 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3b0 Processing field: AnchorPeers
2018-07-03 02:16:31.366 UTC [common/channelconfig] NewStandardValues -> DEBU 3b1 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.366 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3b2 Processing field: MSP
2018-07-03 02:16:31.366 UTC [common/channelconfig] Validate -> DEBU 3b3 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.366 UTC [common/channelconfig] validateMSP -> DEBU 3b4 Setting up MSP for org Org1MSP
2018-07-03 02:16:31.368 UTC [common/channelconfig] NewStandardValues -> DEBU 3b5 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3b6 Processing field: ConsensusType
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3b7 Processing field: BatchSize
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3b8 Processing field: BatchTimeout
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3b9 Processing field: KafkaBrokers
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ba Processing field: ChannelRestrictions
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3bb Processing field: Capabilities
2018-07-03 02:16:31.368 UTC [common/channelconfig] NewStandardValues -> DEBU 3bc Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.368 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3bd Processing field: MSP
2018-07-03 02:16:31.368 UTC [common/channelconfig] validateMSP -> DEBU 3be Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3bf Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c0 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c1 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c2 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c3 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c4 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c5 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c6 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c7 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.368 UTC [common/configtx] addToMap -> DEBU 3c8 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3c9 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3ca Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3cb Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3cc Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3cd Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3ce Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3cf Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d0 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d1 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d2 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d3 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d4 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d5 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d6 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d7 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d8 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3d9 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3da Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3db Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3dc Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3dd Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3de Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3df Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e0 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e1 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e2 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e3 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e4 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e5 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3e6 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.369 UTC [common/channelconfig] LogSanityChecks -> DEBU 3e7 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:31.369 UTC [common/channelconfig] LogSanityChecks -> DEBU 3e8 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:31.369 UTC [common/channelconfig] LogSanityChecks -> DEBU 3e9 As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:31.369 UTC [common/channelconfig] LogSanityChecks -> DEBU 3ea As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:31.369 UTC [common/channelconfig] LogSanityChecks -> DEBU 3eb As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:31.369 UTC [common/channelconfig] LogSanityChecks -> DEBU 3ec As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:31.369 UTC [common/capabilities] Supported -> DEBU 3ed Application capability V1_1 is supported and is enabled
2018-07-03 02:16:31.369 UTC [common/capabilities] Supported -> DEBU 3ee Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:31.369 UTC [common/configtx] addToMap -> DEBU 3ef Adding to config map: [Group]  /Resources
2018-07-03 02:16:31.372 UTC [peer] updateTrustedRoots -> DEBU 3f0 Updating trusted root authorities for channel mychannel
2018-07-03 02:16:31.372 UTC [peer] buildTrustedRootsForChain -> DEBU 3f1 updating root CAs for channel [mychannel]
2018-07-03 02:16:31.372 UTC [peer] buildTrustedRootsForChain -> DEBU 3f2 adding app root CAs for MSP [Org1MSP]
2018-07-03 02:16:31.372 UTC [peer] buildTrustedRootsForChain -> DEBU 3f3 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:16:31.372 UTC [peer] buildTrustedRootsForChain -> DEBU 3f4 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:16:31.373 UTC [committer/txvalidator] validateTx -> DEBU 3f5 config transaction received for chain mychannel
2018-07-03 02:16:31.373 UTC [committer/txvalidator] validateTx -> DEBU 3f6 validateTx completes for block 0xc421f183c0 env 0xc421d96f00 txn 0
2018-07-03 02:16:31.373 UTC [committer/txvalidator] Validate -> DEBU 3f7 got result for idx 0, code 0
2018-07-03 02:16:31.373 UTC [committer/txvalidator] Validate -> DEBU 3f8 END Block Validation
2018-07-03 02:16:31.373 UTC [committer] preCommit -> DEBU 3f9 Received configuration update, calling CSCC ConfigUpdate
2018-07-03 02:16:31.373 UTC [kvledger] CommitWithPvtData -> DEBU 3fa Channel [mychannel]: Validating state for block [1]
2018-07-03 02:16:31.373 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 3fb Validating new block with num trans = [1]
2018-07-03 02:16:31.373 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 3fc ValidateAndPrepareBatch() for block number = [1]
2018-07-03 02:16:31.373 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 3fd preprocessing ProtoBlock...
2018-07-03 02:16:31.373 UTC [valimpl] preprocessProtoBlock -> DEBU 3fe txType=CONFIG
2018-07-03 02:16:31.373 UTC [valimpl] processNonEndorserTx -> DEBU 3ff Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:16:31.373 UTC [valimpl] processNonEndorserTx -> DEBU 400 Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:16:31.373 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 401 constructing new tx simulator
2018-07-03 02:16:31.373 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 402 constructing new tx simulator txid = []
2018-07-03 02:16:31.373 UTC [peer] GenerateSimulationResults -> DEBU 403 Processing CONFIG
2018-07-03 02:16:31.373 UTC [peer] processChannelConfigTx -> DEBU 404 channelConfig=sequence:2 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org1.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:16:31.374 UTC [common/channelconfig] NewStandardValues -> DEBU 405 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 406 Processing field: HashingAlgorithm
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 407 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 408 Processing field: OrdererAddresses
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 409 Processing field: Consortium
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40a Processing field: Capabilities
2018-07-03 02:16:31.374 UTC [common/channelconfig] NewStandardValues -> DEBU 40b Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40c Processing field: Capabilities
2018-07-03 02:16:31.374 UTC [common/channelconfig] NewStandardValues -> DEBU 40d Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 40e Processing field: AnchorPeers
2018-07-03 02:16:31.374 UTC [common/channelconfig] NewStandardValues -> DEBU 40f Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 410 Processing field: MSP
2018-07-03 02:16:31.374 UTC [common/channelconfig] Validate -> DEBU 411 Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.374 UTC [common/channelconfig] validateMSP -> DEBU 412 Setting up MSP for org Org2MSP
2018-07-03 02:16:31.375 UTC [common/channelconfig] NewStandardValues -> DEBU 413 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.375 UTC [common/channelconfig] initializeProtosStruct -> DEBU 414 Processing field: AnchorPeers
2018-07-03 02:16:31.375 UTC [common/channelconfig] NewStandardValues -> DEBU 415 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.375 UTC [common/channelconfig] initializeProtosStruct -> DEBU 416 Processing field: MSP
2018-07-03 02:16:31.375 UTC [common/channelconfig] Validate -> DEBU 417 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.375 UTC [common/channelconfig] validateMSP -> DEBU 418 Setting up MSP for org Org1MSP
2018-07-03 02:16:31.376 UTC [common/channelconfig] NewStandardValues -> DEBU 419 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 41a Processing field: ConsensusType
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 41b Processing field: BatchSize
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 41c Processing field: BatchTimeout
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 41d Processing field: KafkaBrokers
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 41e Processing field: ChannelRestrictions
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 41f Processing field: Capabilities
2018-07-03 02:16:31.376 UTC [common/channelconfig] NewStandardValues -> DEBU 420 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.376 UTC [common/channelconfig] initializeProtosStruct -> DEBU 421 Processing field: MSP
2018-07-03 02:16:31.376 UTC [common/channelconfig] validateMSP -> DEBU 422 Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 423 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 424 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 425 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 426 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 427 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 428 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 429 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 42a Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.376 UTC [common/configtx] addToMap -> DEBU 42b Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 42c Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 42d Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 42e Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 42f Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 430 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 431 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 432 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 433 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 434 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 435 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 436 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 437 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 438 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 439 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 43a Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.377 UTC [common/configtx] addToMap -> DEBU 43b Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 43c Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 43d Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 43e Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 43f Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 440 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 441 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 442 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 443 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 444 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 445 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 446 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 447 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 448 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 449 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.378 UTC [common/configtx] addToMap -> DEBU 44a Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.378 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 44b Simulation completed, getting simulation results
2018-07-03 02:16:31.378 UTC [lockbasedtxmgr] Done -> DEBU 44c Done with transaction simulation / query execution []
2018-07-03 02:16:31.378 UTC [lockbasedtxmgr] Done -> DEBU 44d Done with transaction simulation / query execution []
2018-07-03 02:16:31.378 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 44e Block [1] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:16:31.378 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 44f validating rwset...
2018-07-03 02:16:31.378 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 450 postprocessing ProtoBlock...
2018-07-03 02:16:31.378 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 451 ValidateAndPrepareBatch() complete
2018-07-03 02:16:31.378 UTC [kvledger] CommitWithPvtData -> DEBU 452 Channel [mychannel]: Committing block [1] to storage
2018-07-03 02:16:31.380 UTC [pvtdatastorage] Prepare -> DEBU 453 Saved 0 private data write sets for block [1]
2018-07-03 02:16:31.382 UTC [fsblkstorage] indexBlock -> DEBU 454 Indexing block [blockNum=1, blockHash=[]byte{0xba, 0xb0, 0xc4, 0xd9, 0x17, 0xd9, 0x32, 0xdd, 0x7c, 0x12, 0x95, 0x81, 0x1c, 0xb4, 0x7e, 0xbe, 0xe1, 0x3e, 0xaf, 0x98, 0x43, 0x2, 0x9b, 0x37, 0xe6, 0xfd, 0x26, 0xd2, 0x95, 0x9d, 0x3e, 0xd7} txOffsets=
txId= locPointer=offset=71, bytesLength=15610
]
2018-07-03 02:16:31.382 UTC [fsblkstorage] indexBlock -> DEBU 455 Adding txLoc [fileSuffixNum=0, offset=15721, bytesLength=15610] for tx ID: [] to index
2018-07-03 02:16:31.382 UTC [fsblkstorage] indexBlock -> DEBU 456 Adding txLoc [fileSuffixNum=0, offset=15721, bytesLength=15610] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:16:31.384 UTC [fsblkstorage] updateCheckpoint -> DEBU 457 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[33127], isChainEmpty=[false], lastBlockNumber=[1]
2018-07-03 02:16:31.384 UTC [pvtdatastorage] Commit -> DEBU 458 Committing private data for block [1]
2018-07-03 02:16:31.386 UTC [pvtdatastorage] Commit -> DEBU 459 Committed private data for block [1]
2018-07-03 02:16:31.386 UTC [kvledger] CommitWithPvtData -> INFO 45a Channel [mychannel]: Committed block [1] with 1 transaction(s)
2018-07-03 02:16:31.386 UTC [kvledger] CommitWithPvtData -> DEBU 45b Channel [mychannel]: Committing block [1] transactions to state database
2018-07-03 02:16:31.386 UTC [lockbasedtxmgr] Commit -> DEBU 45c Committing updates to state database
2018-07-03 02:16:31.386 UTC [lockbasedtxmgr] Commit -> DEBU 45d Write lock acquired for committing updates to state database
2018-07-03 02:16:31.386 UTC [stateleveldb] ApplyUpdates -> DEBU 45e Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:16:31.388 UTC [lockbasedtxmgr] Commit -> DEBU 45f Updates committed to state database
2018-07-03 02:16:31.388 UTC [kvledger] CommitWithPvtData -> DEBU 460 Channel [mychannel]: Committing block [1] transactions to history database
2018-07-03 02:16:31.388 UTC [historyleveldb] Commit -> DEBU 461 Channel [mychannel]: Updating history database for blockNo [1] with [1] transactions
2018-07-03 02:16:31.388 UTC [historyleveldb] Commit -> DEBU 462 Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:16:31.389 UTC [historyleveldb] Commit -> DEBU 463 Channel [mychannel]: Updates committed to history database for blockNo [1]
2018-07-03 02:16:31.389 UTC [eventhub_producer] CreateBlockEvents -> DEBU 464 Entry
2018-07-03 02:16:31.389 UTC [eventhub_producer] CreateBlockEvents -> DEBU 465 Exit
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 466 Entry
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 467 Event processor timeout > 0
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 468 Event sent successfully
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 469 Exit
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 46a Entry
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 46b Event processor timeout > 0
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 46c Event sent successfully
2018-07-03 02:16:31.389 UTC [eventhub_producer] Send -> DEBU 46d Exit
2018-07-03 02:16:31.539 UTC [gossip/channel] handleStateInfSnapshot -> DEBU 46e Channel mychannel : Couldn't find org identity of peer ���8w���u�B�Q^hT4R/�:�ӝ�n� message sent from �p_E�l:�6b�΀<<>:��C{���D�W
2018-07-03 02:16:34.509 UTC [blocksProvider] DeliverBlocks -> DEBU 46f [mychannel] Adding payload locally, buffer seqNum = [2], peers number [2]
2018-07-03 02:16:34.509 UTC [blocksProvider] DeliverBlocks -> DEBU 470 [mychannel] Gossiping block [2], peers number [2]
2018-07-03 02:16:34.509 UTC [committer/txvalidator] Validate -> DEBU 471 START Block Validation
2018-07-03 02:16:34.509 UTC [committer/txvalidator] Validate -> DEBU 472 expecting 1 block validation responses
2018-07-03 02:16:34.509 UTC [committer/txvalidator] validateTx -> DEBU 473 validateTx starts for block 0xc420122a60 env 0xc422bd94a0 txn 0
2018-07-03 02:16:34.509 UTC [protoutils] ValidateTransaction -> DEBU 474 ValidateTransactionEnvelope starts for envelope 0xc422bd94a0
2018-07-03 02:16:34.509 UTC [protoutils] ValidateTransaction -> DEBU 475 Header is channel_header:"\010\001\032\006\010\202\271\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030O\347\311\342\252\030\364\325C\224\026\305\212M4&J\215\t(U\277\334P" 
2018-07-03 02:16:34.509 UTC [protoutils] validateChannelHeader -> DEBU 476 validateChannelHeader info: header type 1
2018-07-03 02:16:34.509 UTC [protoutils] checkSignatureFromCreator -> DEBU 477 begin
2018-07-03 02:16:34.509 UTC [protoutils] checkSignatureFromCreator -> DEBU 478 creator is &{OrdererMSP db39cb7220c50c0deea1ae60f6dd1d682369376b27b7a2ba8628646877fd38ea}
2018-07-03 02:16:34.509 UTC [protoutils] checkSignatureFromCreator -> DEBU 479 creator is valid
2018-07-03 02:16:34.509 UTC [protoutils] checkSignatureFromCreator -> DEBU 47a exits successfully
2018-07-03 02:16:34.509 UTC [protoutils] validateConfigTransaction -> DEBU 47b validateConfigTransaction starts for data 0xc42199e000, header channel_header:"\010\001\032\006\010\202\271\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030O\347\311\342\252\030\364\325C\224\026\305\212M4&J\215\t(U\277\334P" 
2018-07-03 02:16:34.509 UTC [committer/txvalidator] validateTx -> DEBU 47c Transaction is for channel mychannel
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 47d Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 47e Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 47f Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 480 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 481 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 482 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 483 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 484 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 485 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 486 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.509 UTC [common/configtx] addToMap -> DEBU 487 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.510 UTC [common/configtx] addToMap -> DEBU 488 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.510 UTC [common/configtx] addToMap -> DEBU 489 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.510 UTC [common/configtx] addToMap -> DEBU 48a Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.510 UTC [common/configtx] addToMap -> DEBU 48b Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.510 UTC [common/configtx] verifyDeltaSet -> DEBU 48c Processing change to key: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.510 UTC [common/configtx] policyForItem -> DEBU 48d Getting policy for item Org2MSP with mod_policy Admins
2018-07-03 02:16:34.510 UTC [common/configtx] verifyDeltaSet -> DEBU 48e Processing change to key: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 48f Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 490 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 491 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 492 Setting policy for key Admins to 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 493 Setting policy for key Readers to 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 494 Setting policy for key Writers to 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 495 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 496 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 497 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 498 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 499 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 49a Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 49b Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 49c Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 49d Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 49e Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 49f Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 4a0 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/configtx] recurseConfigMap -> DEBU 4a1 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.510 UTC [common/channelconfig] NewStandardValues -> DEBU 4a2 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a3 Processing field: HashingAlgorithm
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a4 Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a5 Processing field: OrdererAddresses
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a6 Processing field: Consortium
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a7 Processing field: Capabilities
2018-07-03 02:16:34.510 UTC [common/channelconfig] NewStandardValues -> DEBU 4a8 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a9 Processing field: Capabilities
2018-07-03 02:16:34.510 UTC [common/channelconfig] NewStandardValues -> DEBU 4aa Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ab Processing field: AnchorPeers
2018-07-03 02:16:34.510 UTC [common/channelconfig] NewStandardValues -> DEBU 4ac Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.510 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ad Processing field: MSP
2018-07-03 02:16:34.510 UTC [common/channelconfig] Validate -> DEBU 4ae Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.510 UTC [common/channelconfig] validateMSP -> DEBU 4af Setting up MSP for org Org2MSP
2018-07-03 02:16:34.511 UTC [common/channelconfig] NewStandardValues -> DEBU 4b0 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.511 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4b1 Processing field: AnchorPeers
2018-07-03 02:16:34.511 UTC [common/channelconfig] NewStandardValues -> DEBU 4b2 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.511 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4b3 Processing field: MSP
2018-07-03 02:16:34.511 UTC [common/channelconfig] Validate -> DEBU 4b4 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.511 UTC [common/channelconfig] validateMSP -> DEBU 4b5 Setting up MSP for org Org1MSP
2018-07-03 02:16:34.512 UTC [common/channelconfig] NewStandardValues -> DEBU 4b6 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4b7 Processing field: ConsensusType
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4b8 Processing field: BatchSize
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4b9 Processing field: BatchTimeout
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ba Processing field: KafkaBrokers
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4bb Processing field: ChannelRestrictions
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4bc Processing field: Capabilities
2018-07-03 02:16:34.512 UTC [common/channelconfig] NewStandardValues -> DEBU 4bd Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.512 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4be Processing field: MSP
2018-07-03 02:16:34.512 UTC [common/channelconfig] validateMSP -> DEBU 4bf Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c0 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c1 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c2 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c3 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c4 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c5 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c6 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c7 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c8 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4c9 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4ca Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4cb Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.512 UTC [common/configtx] addToMap -> DEBU 4cc Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4cd Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4ce Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4cf Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d0 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d1 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d2 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d3 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d4 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d5 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d6 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d7 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d8 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4d9 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4da Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4db Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4dc Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4dd Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4de Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4df Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e0 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e1 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e2 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e3 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e4 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e5 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e6 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e7 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4e8 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.513 UTC [common/channelconfig] LogSanityChecks -> DEBU 4e9 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:34.513 UTC [common/channelconfig] LogSanityChecks -> DEBU 4ea As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:34.513 UTC [common/channelconfig] LogSanityChecks -> DEBU 4eb As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:34.513 UTC [common/channelconfig] LogSanityChecks -> DEBU 4ec As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:34.513 UTC [common/channelconfig] LogSanityChecks -> DEBU 4ed As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:34.513 UTC [common/channelconfig] LogSanityChecks -> DEBU 4ee As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:34.513 UTC [common/capabilities] Supported -> DEBU 4ef Application capability V1_1 is supported and is enabled
2018-07-03 02:16:34.513 UTC [common/capabilities] Supported -> DEBU 4f0 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:34.513 UTC [common/configtx] addToMap -> DEBU 4f1 Adding to config map: [Group]  /Resources
2018-07-03 02:16:34.517 UTC [peer] updateTrustedRoots -> DEBU 4f2 Updating trusted root authorities for channel mychannel
2018-07-03 02:16:34.518 UTC [peer] buildTrustedRootsForChain -> DEBU 4f3 updating root CAs for channel [mychannel]
2018-07-03 02:16:34.518 UTC [peer] buildTrustedRootsForChain -> DEBU 4f4 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:16:34.518 UTC [peer] buildTrustedRootsForChain -> DEBU 4f5 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:16:34.518 UTC [peer] buildTrustedRootsForChain -> DEBU 4f6 adding app root CAs for MSP [Org1MSP]
2018-07-03 02:16:34.518 UTC [committer/txvalidator] validateTx -> DEBU 4f7 config transaction received for chain mychannel
2018-07-03 02:16:34.519 UTC [committer/txvalidator] validateTx -> DEBU 4f8 validateTx completes for block 0xc420122a60 env 0xc422bd94a0 txn 0
2018-07-03 02:16:34.520 UTC [committer/txvalidator] Validate -> DEBU 4f9 got result for idx 0, code 0
2018-07-03 02:16:34.520 UTC [committer/txvalidator] Validate -> DEBU 4fa END Block Validation
2018-07-03 02:16:34.520 UTC [committer] preCommit -> DEBU 4fb Received configuration update, calling CSCC ConfigUpdate
2018-07-03 02:16:34.520 UTC [kvledger] CommitWithPvtData -> DEBU 4fc Channel [mychannel]: Validating state for block [2]
2018-07-03 02:16:34.520 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 4fd Validating new block with num trans = [1]
2018-07-03 02:16:34.520 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 4fe ValidateAndPrepareBatch() for block number = [2]
2018-07-03 02:16:34.520 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 4ff preprocessing ProtoBlock...
2018-07-03 02:16:34.520 UTC [valimpl] preprocessProtoBlock -> DEBU 500 txType=CONFIG
2018-07-03 02:16:34.520 UTC [valimpl] processNonEndorserTx -> DEBU 501 Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:16:34.520 UTC [valimpl] processNonEndorserTx -> DEBU 502 Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:16:34.520 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 503 constructing new tx simulator
2018-07-03 02:16:34.520 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 504 constructing new tx simulator txid = []
2018-07-03 02:16:34.520 UTC [peer] GenerateSimulationResults -> DEBU 505 Processing CONFIG
2018-07-03 02:16:34.521 UTC [peer] processChannelConfigTx -> DEBU 506 channelConfig=sequence:3 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org1.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org2.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:16:34.521 UTC [common/channelconfig] NewStandardValues -> DEBU 507 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 508 Processing field: HashingAlgorithm
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 509 Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 50a Processing field: OrdererAddresses
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 50b Processing field: Consortium
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 50c Processing field: Capabilities
2018-07-03 02:16:34.521 UTC [common/channelconfig] NewStandardValues -> DEBU 50d Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 50e Processing field: Capabilities
2018-07-03 02:16:34.521 UTC [common/channelconfig] NewStandardValues -> DEBU 50f Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 510 Processing field: AnchorPeers
2018-07-03 02:16:34.521 UTC [common/channelconfig] NewStandardValues -> DEBU 511 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.521 UTC [common/channelconfig] initializeProtosStruct -> DEBU 512 Processing field: MSP
2018-07-03 02:16:34.521 UTC [common/channelconfig] Validate -> DEBU 513 Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.521 UTC [common/channelconfig] validateMSP -> DEBU 514 Setting up MSP for org Org2MSP
2018-07-03 02:16:34.522 UTC [common/channelconfig] NewStandardValues -> DEBU 515 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.522 UTC [common/channelconfig] initializeProtosStruct -> DEBU 516 Processing field: AnchorPeers
2018-07-03 02:16:34.522 UTC [common/channelconfig] NewStandardValues -> DEBU 517 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.522 UTC [common/channelconfig] initializeProtosStruct -> DEBU 518 Processing field: MSP
2018-07-03 02:16:34.522 UTC [common/channelconfig] Validate -> DEBU 519 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.522 UTC [common/channelconfig] validateMSP -> DEBU 51a Setting up MSP for org Org1MSP
2018-07-03 02:16:34.523 UTC [common/channelconfig] NewStandardValues -> DEBU 51b Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 51c Processing field: ConsensusType
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 51d Processing field: BatchSize
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 51e Processing field: BatchTimeout
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 51f Processing field: KafkaBrokers
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 520 Processing field: ChannelRestrictions
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 521 Processing field: Capabilities
2018-07-03 02:16:34.523 UTC [common/channelconfig] NewStandardValues -> DEBU 522 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.523 UTC [common/channelconfig] initializeProtosStruct -> DEBU 523 Processing field: MSP
2018-07-03 02:16:34.523 UTC [common/channelconfig] validateMSP -> DEBU 524 Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 525 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 526 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 527 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 528 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 529 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 52a Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 52b Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 52c Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 52d Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 52e Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 52f Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 530 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 531 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 532 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 533 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 534 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 535 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 536 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 537 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 538 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 539 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 53a Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 53b Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 53c Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 53d Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 53e Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 53f Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 540 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.524 UTC [common/configtx] addToMap -> DEBU 541 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 542 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 543 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 544 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 545 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 546 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 547 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 548 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 549 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 54a Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 54b Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 54c Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.525 UTC [common/configtx] addToMap -> DEBU 54d Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.525 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 54e Simulation completed, getting simulation results
2018-07-03 02:16:34.525 UTC [lockbasedtxmgr] Done -> DEBU 54f Done with transaction simulation / query execution []
2018-07-03 02:16:34.525 UTC [lockbasedtxmgr] Done -> DEBU 550 Done with transaction simulation / query execution []
2018-07-03 02:16:34.525 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 551 Block [2] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:16:34.525 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 552 validating rwset...
2018-07-03 02:16:34.525 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 553 postprocessing ProtoBlock...
2018-07-03 02:16:34.525 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 554 ValidateAndPrepareBatch() complete
2018-07-03 02:16:34.525 UTC [kvledger] CommitWithPvtData -> DEBU 555 Channel [mychannel]: Committing block [2] to storage
2018-07-03 02:16:34.526 UTC [pvtdatastorage] Prepare -> DEBU 556 Saved 0 private data write sets for block [2]
2018-07-03 02:16:34.527 UTC [fsblkstorage] indexBlock -> DEBU 557 Indexing block [blockNum=2, blockHash=[]byte{0x22, 0x8d, 0x20, 0xe, 0xe2, 0x5c, 0xa0, 0x3c, 0xd0, 0x74, 0xe9, 0x2d, 0x10, 0x62, 0xf4, 0xb8, 0x5c, 0x9, 0x54, 0xb6, 0x3d, 0xb0, 0x60, 0x23, 0x3b, 0xa0, 0xe3, 0x9b, 0x27, 0xfa, 0xf6, 0xa8} txOffsets=
txId= locPointer=offset=71, bytesLength=15669
]
2018-07-03 02:16:34.528 UTC [fsblkstorage] indexBlock -> DEBU 558 Adding txLoc [fileSuffixNum=0, offset=33198, bytesLength=15669] for tx ID: [] to index
2018-07-03 02:16:34.528 UTC [fsblkstorage] indexBlock -> DEBU 559 Adding txLoc [fileSuffixNum=0, offset=33198, bytesLength=15669] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:16:34.528 UTC [fsblkstorage] updateCheckpoint -> DEBU 55a Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[50661], isChainEmpty=[false], lastBlockNumber=[2]
2018-07-03 02:16:34.528 UTC [pvtdatastorage] Commit -> DEBU 55b Committing private data for block [2]
2018-07-03 02:16:34.538 UTC [pvtdatastorage] Commit -> DEBU 55c Committed private data for block [2]
2018-07-03 02:16:34.538 UTC [kvledger] CommitWithPvtData -> INFO 55d Channel [mychannel]: Committed block [2] with 1 transaction(s)
2018-07-03 02:16:34.538 UTC [kvledger] CommitWithPvtData -> DEBU 55e Channel [mychannel]: Committing block [2] transactions to state database
2018-07-03 02:16:34.538 UTC [lockbasedtxmgr] Commit -> DEBU 55f Committing updates to state database
2018-07-03 02:16:34.538 UTC [lockbasedtxmgr] Commit -> DEBU 560 Write lock acquired for committing updates to state database
2018-07-03 02:16:34.538 UTC [stateleveldb] ApplyUpdates -> DEBU 561 Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:16:34.540 UTC [lockbasedtxmgr] Commit -> DEBU 562 Updates committed to state database
2018-07-03 02:16:34.540 UTC [kvledger] CommitWithPvtData -> DEBU 563 Channel [mychannel]: Committing block [2] transactions to history database
2018-07-03 02:16:34.540 UTC [historyleveldb] Commit -> DEBU 564 Channel [mychannel]: Updating history database for blockNo [2] with [1] transactions
2018-07-03 02:16:34.540 UTC [historyleveldb] Commit -> DEBU 565 Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:16:34.542 UTC [historyleveldb] Commit -> DEBU 566 Channel [mychannel]: Updates committed to history database for blockNo [2]
2018-07-03 02:16:34.542 UTC [eventhub_producer] CreateBlockEvents -> DEBU 567 Entry
2018-07-03 02:16:34.542 UTC [eventhub_producer] CreateBlockEvents -> DEBU 568 Exit
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 569 Entry
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 56a Event processor timeout > 0
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 56b Event sent successfully
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 56c Exit
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 56d Entry
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 56e Event processor timeout > 0
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 56f Event sent successfully
2018-07-03 02:16:34.542 UTC [eventhub_producer] Send -> DEBU 570 Exit

