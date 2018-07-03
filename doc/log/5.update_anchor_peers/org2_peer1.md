2018-07-03 02:16:31.371 UTC [committer/txvalidator] Validate -> DEBU 354 START Block Validation
2018-07-03 02:16:31.371 UTC [committer/txvalidator] Validate -> DEBU 355 expecting 1 block validation responses
2018-07-03 02:16:31.371 UTC [committer/txvalidator] validateTx -> DEBU 356 validateTx starts for block 0xc4222732c0 env 0xc42228c2a0 txn 0
2018-07-03 02:16:31.371 UTC [protoutils] ValidateTransaction -> DEBU 357 ValidateTransactionEnvelope starts for envelope 0xc42228c2a0
2018-07-03 02:16:31.371 UTC [protoutils] ValidateTransaction -> DEBU 358 Header is channel_header:"\010\001\032\006\010\377\270\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030\240\207\201hQ\352\201\237\235K\264\024\016U\335]P\311\372^\267^\241}" 
2018-07-03 02:16:31.371 UTC [protoutils] validateChannelHeader -> DEBU 359 validateChannelHeader info: header type 1
2018-07-03 02:16:31.371 UTC [protoutils] checkSignatureFromCreator -> DEBU 35a begin
2018-07-03 02:16:31.371 UTC [protoutils] checkSignatureFromCreator -> DEBU 35b creator is &{OrdererMSP db39cb7220c50c0deea1ae60f6dd1d682369376b27b7a2ba8628646877fd38ea}
2018-07-03 02:16:31.371 UTC [protoutils] checkSignatureFromCreator -> DEBU 35c creator is valid
2018-07-03 02:16:31.371 UTC [protoutils] checkSignatureFromCreator -> DEBU 35d exits successfully
2018-07-03 02:16:31.371 UTC [protoutils] validateConfigTransaction -> DEBU 35e validateConfigTransaction starts for data 0xc422bd6000, header channel_header:"\010\001\032\006\010\377\270\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgN
V\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030\240\207\201hQ\352\201\237\235K\264\024\016U\335]P\311\372^\267^\241}" 
2018-07-03 02:16:31.371 UTC [committer/txvalidator] validateTx -> DEBU 35f Transaction is for channel mychannel
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 360 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 361 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 362 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 363 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 364 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 365 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.371 UTC [common/configtx] addToMap -> DEBU 366 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 367 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 368 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 369 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 36a Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 36b Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 36c Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 36d Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.372 UTC [common/configtx] addToMap -> DEBU 36e Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.372 UTC [common/configtx] verifyDeltaSet -> DEBU 36f Processing change to key: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.372 UTC [common/configtx] policyForItem -> DEBU 370 Getting policy for item Org1MSP with mod_policy Admins
2018-07-03 02:16:31.372 UTC [common/configtx] verifyDeltaSet -> DEBU 371 Processing change to key: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 372 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 373 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 374 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 375 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 376 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 377 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 378 Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 379 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 37a Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 37b Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 37c Setting policy for key Admins to 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 37d Setting policy for key Readers to 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 37e Setting policy for key Writers to 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 37f Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.372 UTC [common/configtx] recurseConfigMap -> DEBU 380 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.373 UTC [common/configtx] recurseConfigMap -> DEBU 381 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.373 UTC [common/configtx] recurseConfigMap -> DEBU 382 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.373 UTC [common/configtx] recurseConfigMap -> DEBU 383 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.373 UTC [common/configtx] recurseConfigMap -> DEBU 384 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.373 UTC [common/channelconfig] NewStandardValues -> DEBU 385 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 386 Processing field: HashingAlgorithm
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 387 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 388 Processing field: OrdererAddresses
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 389 Processing field: Consortium
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 38a Processing field: Capabilities
2018-07-03 02:16:31.373 UTC [common/channelconfig] NewStandardValues -> DEBU 38b Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 38c Processing field: Capabilities
2018-07-03 02:16:31.373 UTC [common/channelconfig] NewStandardValues -> DEBU 38d Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 38e Processing field: AnchorPeers
2018-07-03 02:16:31.373 UTC [common/channelconfig] NewStandardValues -> DEBU 38f Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.373 UTC [common/channelconfig] initializeProtosStruct -> DEBU 390 Processing field: MSP
2018-07-03 02:16:31.373 UTC [common/channelconfig] Validate -> DEBU 391 Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.373 UTC [common/channelconfig] validateMSP -> DEBU 392 Setting up MSP for org Org2MSP
2018-07-03 02:16:31.374 UTC [common/channelconfig] NewStandardValues -> DEBU 393 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 394 Processing field: AnchorPeers
2018-07-03 02:16:31.374 UTC [common/channelconfig] NewStandardValues -> DEBU 395 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.374 UTC [common/channelconfig] initializeProtosStruct -> DEBU 396 Processing field: MSP
2018-07-03 02:16:31.374 UTC [common/channelconfig] Validate -> DEBU 397 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.374 UTC [common/channelconfig] validateMSP -> DEBU 398 Setting up MSP for org Org1MSP
2018-07-03 02:16:31.383 UTC [common/channelconfig] NewStandardValues -> DEBU 399 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.383 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39a Processing field: ConsensusType
2018-07-03 02:16:31.383 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39b Processing field: BatchSize
2018-07-03 02:16:31.383 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39c Processing field: BatchTimeout
2018-07-03 02:16:31.384 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39d Processing field: KafkaBrokers
2018-07-03 02:16:31.384 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39e Processing field: ChannelRestrictions
2018-07-03 02:16:31.384 UTC [common/channelconfig] initializeProtosStruct -> DEBU 39f Processing field: Capabilities
2018-07-03 02:16:31.384 UTC [common/channelconfig] NewStandardValues -> DEBU 3a0 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.384 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3a1 Processing field: MSP
2018-07-03 02:16:31.384 UTC [common/channelconfig] validateMSP -> DEBU 3a2 Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a3 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a4 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a5 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a6 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a7 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a8 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3a9 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3aa Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3ab Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.384 UTC [common/configtx] addToMap -> DEBU 3ac Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3ad Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3ae Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3af Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b0 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b1 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b2 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b3 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b4 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b5 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b6 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b7 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b8 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3b9 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3ba Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3bb Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3bc Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3bd Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3be Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3bf Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c0 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c1 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c2 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c3 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c4 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c5 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c6 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c7 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c8 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3c9 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.385 UTC [common/configtx] addToMap -> DEBU 3ca Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.385 UTC [common/channelconfig] LogSanityChecks -> DEBU 3cb As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:31.385 UTC [common/channelconfig] LogSanityChecks -> DEBU 3cc As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:31.385 UTC [common/channelconfig] LogSanityChecks -> DEBU 3cd As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:31.385 UTC [common/channelconfig] LogSanityChecks -> DEBU 3ce As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:31.385 UTC [common/channelconfig] LogSanityChecks -> DEBU 3cf As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:31.385 UTC [common/channelconfig] LogSanityChecks -> DEBU 3d0 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:31.385 UTC [common/capabilities] Supported -> DEBU 3d1 Application capability V1_1 is supported and is enabled
2018-07-03 02:16:31.386 UTC [common/capabilities] Supported -> DEBU 3d2 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:31.386 UTC [common/configtx] addToMap -> DEBU 3d3 Adding to config map: [Group]  /Resources
2018-07-03 02:16:31.386 UTC [gossip/service] updateEndpoints -> WARN 3d4 Failed to update ordering service endpoints, due to Channel with mychannel id was not found
2018-07-03 02:16:31.387 UTC [peer] updateTrustedRoots -> DEBU 3d5 Updating trusted root authorities for channel mychannel
2018-07-03 02:16:31.387 UTC [peer] buildTrustedRootsForChain -> DEBU 3d6 updating root CAs for channel [mychannel]
2018-07-03 02:16:31.387 UTC [peer] buildTrustedRootsForChain -> DEBU 3d7 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:16:31.387 UTC [peer] buildTrustedRootsForChain -> DEBU 3d8 adding app root CAs for MSP [Org1MSP]
2018-07-03 02:16:31.387 UTC [peer] buildTrustedRootsForChain -> DEBU 3d9 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:16:31.394 UTC [committer/txvalidator] validateTx -> DEBU 3da config transaction received for chain mychannel
2018-07-03 02:16:31.394 UTC [committer/txvalidator] validateTx -> DEBU 3db validateTx completes for block 0xc4222732c0 env 0xc42228c2a0 txn 0
2018-07-03 02:16:31.394 UTC [committer/txvalidator] Validate -> DEBU 3dc got result for idx 0, code 0
2018-07-03 02:16:31.394 UTC [committer/txvalidator] Validate -> DEBU 3dd END Block Validation
2018-07-03 02:16:31.394 UTC [committer] preCommit -> DEBU 3de Received configuration update, calling CSCC ConfigUpdate
2018-07-03 02:16:31.394 UTC [kvledger] CommitWithPvtData -> DEBU 3df Channel [mychannel]: Validating state for block [1]
2018-07-03 02:16:31.394 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 3e0 Validating new block with num trans = [1]
2018-07-03 02:16:31.394 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 3e1 ValidateAndPrepareBatch() for block number = [1]
2018-07-03 02:16:31.394 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 3e2 preprocessing ProtoBlock...
2018-07-03 02:16:31.394 UTC [valimpl] preprocessProtoBlock -> DEBU 3e3 txType=CONFIG
2018-07-03 02:16:31.394 UTC [valimpl] processNonEndorserTx -> DEBU 3e4 Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:16:31.394 UTC [valimpl] processNonEndorserTx -> DEBU 3e5 Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:16:31.394 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 3e6 constructing new tx simulator
2018-07-03 02:16:31.394 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 3e7 constructing new tx simulator txid = []
2018-07-03 02:16:31.394 UTC [peer] GenerateSimulationResults -> DEBU 3e8 Processing CONFIG
2018-07-03 02:16:31.395 UTC [peer] processChannelConfigTx -> DEBU 3e9 channelConfig=sequence:2 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org1.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:16:31.396 UTC [common/channelconfig] NewStandardValues -> DEBU 3ea Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3eb Processing field: HashingAlgorithm
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ec Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ed Processing field: OrdererAddresses
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ee Processing field: Consortium
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ef Processing field: Capabilities
2018-07-03 02:16:31.396 UTC [common/channelconfig] NewStandardValues -> DEBU 3f0 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f1 Processing field: Capabilities
2018-07-03 02:16:31.396 UTC [common/channelconfig] NewStandardValues -> DEBU 3f2 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f3 Processing field: AnchorPeers
2018-07-03 02:16:31.396 UTC [common/channelconfig] NewStandardValues -> DEBU 3f4 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.396 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f5 Processing field: MSP
2018-07-03 02:16:31.396 UTC [common/channelconfig] Validate -> DEBU 3f6 Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.396 UTC [common/channelconfig] validateMSP -> DEBU 3f7 Setting up MSP for org Org2MSP
2018-07-03 02:16:31.397 UTC [common/channelconfig] NewStandardValues -> DEBU 3f8 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.397 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3f9 Processing field: AnchorPeers
2018-07-03 02:16:31.397 UTC [common/channelconfig] NewStandardValues -> DEBU 3fa Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.397 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3fb Processing field: MSP
2018-07-03 02:16:31.397 UTC [common/channelconfig] Validate -> DEBU 3fc Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.397 UTC [common/channelconfig] validateMSP -> DEBU 3fd Setting up MSP for org Org1MSP
2018-07-03 02:16:31.402 UTC [common/channelconfig] NewStandardValues -> DEBU 3fe Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 3ff Processing field: ConsensusType
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 400 Processing field: BatchSize
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 401 Processing field: BatchTimeout
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 402 Processing field: KafkaBrokers
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 403 Processing field: ChannelRestrictions
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 404 Processing field: Capabilities
2018-07-03 02:16:31.402 UTC [common/channelconfig] NewStandardValues -> DEBU 405 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.402 UTC [common/channelconfig] initializeProtosStruct -> DEBU 406 Processing field: MSP
2018-07-03 02:16:31.402 UTC [common/channelconfig] validateMSP -> DEBU 407 Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 408 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 409 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 40a Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 40b Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 40c Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 40d Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 40e Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 40f Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 410 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 411 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 412 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 413 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 414 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 415 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 416 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 417 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 418 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 419 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 41a Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 41b Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 41c Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 41d Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 41e Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 41f Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 420 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 421 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 422 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 423 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 424 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 425 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 426 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.404 UTC [common/configtx] addToMap -> DEBU 427 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 428 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 429 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 42a Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 42b Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 42c Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 42d Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 42e Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.405 UTC [common/configtx] addToMap -> DEBU 42f Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.405 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 430 Simulation completed, getting simulation results
2018-07-03 02:16:31.405 UTC [lockbasedtxmgr] Done -> DEBU 431 Done with transaction simulation / query execution []
2018-07-03 02:16:31.405 UTC [lockbasedtxmgr] Done -> DEBU 432 Done with transaction simulation / query execution []
2018-07-03 02:16:31.405 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 433 Block [1] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:16:31.405 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 434 validating rwset...
2018-07-03 02:16:31.405 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 435 postprocessing ProtoBlock...
2018-07-03 02:16:31.405 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 436 ValidateAndPrepareBatch() complete
2018-07-03 02:16:31.405 UTC [kvledger] CommitWithPvtData -> DEBU 437 Channel [mychannel]: Committing block [1] to storage
2018-07-03 02:16:31.406 UTC [pvtdatastorage] Prepare -> DEBU 438 Saved 0 private data write sets for block [1]
2018-07-03 02:16:31.407 UTC [fsblkstorage] indexBlock -> DEBU 439 Indexing block [blockNum=1, blockHash=[]byte{0xba, 0xb0, 0xc4, 0xd9, 0x17, 0xd9, 0x32, 0xdd, 0x7c, 0x12, 0x95, 0x81, 0x1c, 0xb4, 0x7e, 0xbe, 0xe1, 0x3e, 0xaf, 0x98, 0x43, 0x2, 0x9b, 0x37, 0xe6, 0xfd, 0x26, 0xd2, 0x95, 0x9d, 0x3e, 0xd7} txOffsets=
txId= locPointer=offset=71, bytesLength=15610
]
2018-07-03 02:16:31.407 UTC [fsblkstorage] indexBlock -> DEBU 43a Adding txLoc [fileSuffixNum=0, offset=15721, bytesLength=15610] for tx ID: [] to index
2018-07-03 02:16:31.407 UTC [fsblkstorage] indexBlock -> DEBU 43b Adding txLoc [fileSuffixNum=0, offset=15721, bytesLength=15610] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:16:31.408 UTC [fsblkstorage] updateCheckpoint -> DEBU 43c Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[33127], isChainEmpty=[false], lastBlockNumber=[1]
2018-07-03 02:16:31.408 UTC [pvtdatastorage] Commit -> DEBU 43d Committing private data for block [1]
2018-07-03 02:16:31.409 UTC [pvtdatastorage] Commit -> DEBU 43e Committed private data for block [1]
2018-07-03 02:16:31.409 UTC [kvledger] CommitWithPvtData -> INFO 43f Channel [mychannel]: Committed block [1] with 1 transaction(s)
2018-07-03 02:16:31.409 UTC [kvledger] CommitWithPvtData -> DEBU 440 Channel [mychannel]: Committing block [1] transactions to state database
2018-07-03 02:16:31.409 UTC [lockbasedtxmgr] Commit -> DEBU 441 Committing updates to state database
2018-07-03 02:16:31.409 UTC [lockbasedtxmgr] Commit -> DEBU 442 Write lock acquired for committing updates to state database
2018-07-03 02:16:31.409 UTC [stateleveldb] ApplyUpdates -> DEBU 443 Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:16:31.411 UTC [lockbasedtxmgr] Commit -> DEBU 444 Updates committed to state database
2018-07-03 02:16:31.411 UTC [kvledger] CommitWithPvtData -> DEBU 445 Channel [mychannel]: Committing block [1] transactions to history database
2018-07-03 02:16:31.411 UTC [historyleveldb] Commit -> DEBU 446 Channel [mychannel]: Updating history database for blockNo [1] with [1] transactions
2018-07-03 02:16:31.411 UTC [historyleveldb] Commit -> DEBU 447 Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:16:31.412 UTC [historyleveldb] Commit -> DEBU 448 Channel [mychannel]: Updates committed to history database for blockNo [1]
2018-07-03 02:16:31.412 UTC [eventhub_producer] CreateBlockEvents -> DEBU 449 Entry
2018-07-03 02:16:31.412 UTC [eventhub_producer] CreateBlockEvents -> DEBU 44a Exit
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 44b Entry
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 44c Event processor timeout > 0
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 44d Event sent successfully
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 44e Exit
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 44f Entry
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 450 Event processor timeout > 0
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 451 Event sent successfully
2018-07-03 02:16:31.412 UTC [eventhub_producer] Send -> DEBU 452 Exit
2018-07-03 02:16:34.522 UTC [committer/txvalidator] Validate -> DEBU 453 START Block Validation
2018-07-03 02:16:34.522 UTC [committer/txvalidator] Validate -> DEBU 454 expecting 1 block validation responses
2018-07-03 02:16:34.522 UTC [committer/txvalidator] validateTx -> DEBU 455 validateTx starts for block 0xc42347b080 env 0xc4224ad440 txn 0
2018-07-03 02:16:34.522 UTC [protoutils] ValidateTransaction -> DEBU 456 ValidateTransactionEnvelope starts for envelope 0xc4224ad440
2018-07-03 02:16:34.522 UTC [protoutils] ValidateTransaction -> DEBU 457 Header is channel_header:"\010\001\032\006\010\202\271\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030O\347\311\342\252\030\364\325C\224\026\305\212M4&J\215\t(U\277\334P" 
2018-07-03 02:16:34.522 UTC [protoutils] validateChannelHeader -> DEBU 458 validateChannelHeader info: header type 1
2018-07-03 02:16:34.522 UTC [protoutils] checkSignatureFromCreator -> DEBU 459 begin
2018-07-03 02:16:34.522 UTC [protoutils] checkSignatureFromCreator -> DEBU 45a creator is &{OrdererMSP db39cb7220c50c0deea1ae60f6dd1d682369376b27b7a2ba8628646877fd38ea}
2018-07-03 02:16:34.522 UTC [protoutils] checkSignatureFromCreator -> DEBU 45b creator is valid
2018-07-03 02:16:34.522 UTC [protoutils] checkSignatureFromCreator -> DEBU 45c exits successfully
2018-07-03 02:16:34.522 UTC [protoutils] validateConfigTransaction -> DEBU 45d validateConfigTransaction starts for data 0xc423496000, header channel_header:"\010\001\032\006\010\202\271\353\331\005\"\tmychannel" signature_header:"\n\220\006\n\nOrdererMSP\022\201\006-----BEGIN CERTIFICATE-----\nMIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI\nKoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8\nnPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA\nMAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h\nYqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B\nbxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD\n-----END CERTIFICATE-----\n\022\030O\347\311\342\252\030\364\325C\224\026\305\212M4&J\215\t(U\277\334P" 
2018-07-03 02:16:34.522 UTC [committer/txvalidator] validateTx -> DEBU 45e Transaction is for channel mychannel
2018-07-03 02:16:34.522 UTC [common/configtx] addToMap -> DEBU 45f Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.522 UTC [common/configtx] addToMap -> DEBU 460 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 461 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 462 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 463 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 464 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 465 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 466 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 467 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 468 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 469 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 46a Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 46b Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 46c Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.523 UTC [common/configtx] addToMap -> DEBU 46d Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.523 UTC [common/configtx] verifyDeltaSet -> DEBU 46e Processing change to key: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.523 UTC [common/configtx] policyForItem -> DEBU 46f Getting policy for item Org2MSP with mod_policy Admins
2018-07-03 02:16:34.523 UTC [common/configtx] verifyDeltaSet -> DEBU 470 Processing change to key: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.523 UTC [common/configtx] recurseConfigMap -> DEBU 471 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.523 UTC [common/configtx] recurseConfigMap -> DEBU 472 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 473 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 474 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 475 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 476 Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 477 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 478 Setting policy for key Admins to 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 479 Setting policy for key Readers to 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 47a Setting policy for key Writers to 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 47b Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 47c Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 47d Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 47e Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 47f Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 480 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 481 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 482 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/configtx] recurseConfigMap -> DEBU 483 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.524 UTC [common/channelconfig] NewStandardValues -> DEBU 484 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 485 Processing field: HashingAlgorithm
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 486 Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 487 Processing field: OrdererAddresses
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 488 Processing field: Consortium
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 489 Processing field: Capabilities
2018-07-03 02:16:34.524 UTC [common/channelconfig] NewStandardValues -> DEBU 48a Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 48b Processing field: Capabilities
2018-07-03 02:16:34.524 UTC [common/channelconfig] NewStandardValues -> DEBU 48c Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 48d Processing field: AnchorPeers
2018-07-03 02:16:34.524 UTC [common/channelconfig] NewStandardValues -> DEBU 48e Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.524 UTC [common/channelconfig] initializeProtosStruct -> DEBU 48f Processing field: MSP
2018-07-03 02:16:34.524 UTC [common/channelconfig] Validate -> DEBU 490 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.524 UTC [common/channelconfig] validateMSP -> DEBU 491 Setting up MSP for org Org1MSP
2018-07-03 02:16:34.532 UTC [common/channelconfig] NewStandardValues -> DEBU 492 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.532 UTC [common/channelconfig] initializeProtosStruct -> DEBU 493 Processing field: AnchorPeers
2018-07-03 02:16:34.532 UTC [common/channelconfig] NewStandardValues -> DEBU 494 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.532 UTC [common/channelconfig] initializeProtosStruct -> DEBU 495 Processing field: MSP
2018-07-03 02:16:34.532 UTC [common/channelconfig] Validate -> DEBU 496 Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.533 UTC [common/channelconfig] validateMSP -> DEBU 497 Setting up MSP for org Org2MSP
2018-07-03 02:16:34.534 UTC [common/channelconfig] NewStandardValues -> DEBU 498 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 499 Processing field: ConsensusType
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49a Processing field: BatchSize
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49b Processing field: BatchTimeout
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49c Processing field: KafkaBrokers
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49d Processing field: ChannelRestrictions
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49e Processing field: Capabilities
2018-07-03 02:16:34.534 UTC [common/channelconfig] NewStandardValues -> DEBU 49f Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.534 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a0 Processing field: MSP
2018-07-03 02:16:34.534 UTC [common/channelconfig] validateMSP -> DEBU 4a1 Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a2 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a3 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a4 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a5 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a6 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a7 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a8 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4a9 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4aa Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4ab Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4ac Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4ad Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4ae Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4af Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b0 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b1 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b2 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b3 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b4 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b5 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b6 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b7 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b8 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.535 UTC [common/configtx] addToMap -> DEBU 4b9 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4ba Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4bb Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4bc Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4bd Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4be Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4bf Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c0 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c1 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c2 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c3 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c4 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c5 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c6 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c7 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c8 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4c9 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4ca Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.536 UTC [common/channelconfig] LogSanityChecks -> DEBU 4cb As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:34.536 UTC [common/channelconfig] LogSanityChecks -> DEBU 4cc As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:34.536 UTC [common/channelconfig] LogSanityChecks -> DEBU 4cd As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:34.536 UTC [common/channelconfig] LogSanityChecks -> DEBU 4ce As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:34.536 UTC [common/channelconfig] LogSanityChecks -> DEBU 4cf As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:34.536 UTC [common/channelconfig] LogSanityChecks -> DEBU 4d0 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:34.536 UTC [common/capabilities] Supported -> DEBU 4d1 Application capability V1_1 is supported and is enabled
2018-07-03 02:16:34.536 UTC [common/capabilities] Supported -> DEBU 4d2 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:34.536 UTC [common/configtx] addToMap -> DEBU 4d3 Adding to config map: [Group]  /Resources
2018-07-03 02:16:34.543 UTC [gossip/service] updateEndpoints -> WARN 4d4 Failed to update ordering service endpoints, due to Channel with mychannel id was not found
2018-07-03 02:16:34.545 UTC [peer] updateTrustedRoots -> DEBU 4d5 Updating trusted root authorities for channel mychannel
2018-07-03 02:16:34.547 UTC [peer] buildTrustedRootsForChain -> DEBU 4d6 updating root CAs for channel [mychannel]
2018-07-03 02:16:34.547 UTC [peer] buildTrustedRootsForChain -> DEBU 4d7 adding app root CAs for MSP [Org1MSP]
2018-07-03 02:16:34.547 UTC [peer] buildTrustedRootsForChain -> DEBU 4d8 adding app root CAs for MSP [Org2MSP]
2018-07-03 02:16:34.547 UTC [peer] buildTrustedRootsForChain -> DEBU 4d9 adding orderer root CAs for MSP [OrdererMSP]
2018-07-03 02:16:34.547 UTC [committer/txvalidator] validateTx -> DEBU 4da config transaction received for chain mychannel
2018-07-03 02:16:34.547 UTC [committer/txvalidator] validateTx -> DEBU 4db validateTx completes for block 0xc42347b080 env 0xc4224ad440 txn 0
2018-07-03 02:16:34.547 UTC [committer/txvalidator] Validate -> DEBU 4dc got result for idx 0, code 0
2018-07-03 02:16:34.547 UTC [committer/txvalidator] Validate -> DEBU 4dd END Block Validation
2018-07-03 02:16:34.547 UTC [committer] preCommit -> DEBU 4de Received configuration update, calling CSCC ConfigUpdate
2018-07-03 02:16:34.547 UTC [kvledger] CommitWithPvtData -> DEBU 4df Channel [mychannel]: Validating state for block [2]
2018-07-03 02:16:34.547 UTC [lockbasedtxmgr] ValidateAndPrepare -> DEBU 4e0 Validating new block with num trans = [1]
2018-07-03 02:16:34.548 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 4e1 ValidateAndPrepareBatch() for block number = [2]
2018-07-03 02:16:34.548 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 4e2 preprocessing ProtoBlock...
2018-07-03 02:16:34.548 UTC [valimpl] preprocessProtoBlock -> DEBU 4e3 txType=CONFIG
2018-07-03 02:16:34.548 UTC [valimpl] processNonEndorserTx -> DEBU 4e4 Performing custom processing for transaction [txid=], [txType=CONFIG]
2018-07-03 02:16:34.548 UTC [valimpl] processNonEndorserTx -> DEBU 4e5 Processor for custom tx processing:&peer.configtxProcessor{}
2018-07-03 02:16:34.548 UTC [lockbasedtxmgr] NewTxSimulator -> DEBU 4e6 constructing new tx simulator
2018-07-03 02:16:34.548 UTC [lockbasedtxmgr] newLockBasedTxSimulator -> DEBU 4e7 constructing new tx simulator txid = []
2018-07-03 02:16:34.548 UTC [peer] GenerateSimulationResults -> DEBU 4e8 Processing CONFIG
2018-07-03 02:16:34.548 UTC [peer] processChannelConfigTx -> DEBU 4e9 channelConfig=sequence:3 channel_group:<groups:<key:"Application" value:<version:1 groups:<key:"Org1MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org1.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\257!\n\007Org1MSP\022\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y\nZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf\nKtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p\ncOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV\nHSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO\nPQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2\nSNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\327\006-----BEGIN CERTIFICATE-----\nMIICSjCCAfCgAwIBAgIRAP/jRUcSgFP0pvVd9YupOUYwCgYIKoZIzj0EAwIwdjEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHzAdBgNVBAMTFnRs\nc2NhLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMz\nNzA5WjB2MQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UE\nBxMNU2FuIEZyYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEfMB0G\nA1UEAxMWdGxzY2Eub3JnMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49\nAwEHA0IABEQIA+fDLVH3PSfBt9pHQEQ1tGeBwpG2AzdjLhqm6/SItsXn7NqZHCJX\nSx/Aux6EAbD1lE3bnT1VtPy6T87GgLGjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNV\nHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMBAf8wKQYDVR0OBCIEIG9bnQIh0dup\n2HvvqQLO+s1DVi3dyBBp4oHYSuLnuKHoMAoGCCqGSM49BAMCA0gAMEUCIQCgkRWa\nITZt5iOLyMHXtgj7LJJMB06p5VDyNHTM+Ik43QIgDZg1OdKqs6hrcBxx09BBo0e6\nk+FzkfMFLRGFQqeow8o=\n-----END CERTIFICATE-----\nZ\272\r\010\001\022\332\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\006client\032\330\006\n\317\006-----BEGIN CERTIFICATE-----\nMIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\nQjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k\nkp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj\n4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1\nEAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo\nJaPsTQzNKw==\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Org2MSP" value:<version:1 values:<key:"AnchorPeers" value:<value:"\n\033\n\026peer0.org2.example.com\020\2137" mod_policy:"Admins" > > values:<key:"MSP" value:<value:"\022\237!\n\007Org2MSP\022\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\"\252\006-----BEGIN CERTIFICATE-----\nMIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv\ncmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS\npiH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr\n/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD\nVR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI\nzj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA\nZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\323\006-----BEGIN CERTIFICATE-----\nMIICSDCCAe+gAwIBAgIQPXdJS6Xu+7qSyg0fJuE8KDAKBggqhkjOPQQDAjB2MQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEfMB0GA1UEAxMWdGxz\nY2Eub3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3\nMDlaMHYxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQH\nEw1TYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMR8wHQYD\nVQQDExZ0bHNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0D\nAQcDQgAEmYa6Nu3dm3NLPRi249A02u0/HsLGtNRl8TXeesKC2ZRIVYOxsezaVqAX\nW7O0IOWsm9VILy/TmGtPeA/hJbBRjKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1Ud\nJQQIMAYGBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgLgWKVjnPX+OE\nJ1RvZMaphPnXTQgB5LcH43rDAlXzqa8wCgYIKoZIzj0EAwIDRwAwRAIgXR2ruINz\nsK1xuzv4s4yAvy4ML4WvTkjk6bM/tx8DaJgCIBUiBpD0aKqZ/Ifxs6iwfpXT9QzO\nKRTX6WcBGnUwJiC9\n-----END CERTIFICATE-----\nZ\262\r\010\001\022\326\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\006client\032\324\006\n\313\006-----BEGIN CERTIFICATE-----\nMIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu\nb3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla\nMHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T\nYW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD\nExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE\n1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn\nb3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG\nBFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d\nb+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl\nTmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13\nG4VS/ZlT\n-----END CERTIFICATE-----\n\022\004peer" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > groups:<key:"Orderer" value:<groups:<key:"OrdererOrg" value:<values:<key:"MSP" value:<value:"\022\222\023\n\nOrdererMSP\022\262\006-----BEGIN CERTIFICATE-----\nMIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w\nbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE\nBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz\nY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv\nbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn\nHpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd\nMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB\nAf8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG\nCCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj\nZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=\n-----END CERTIFICATE-----\n\"\201\006-----BEGIN CERTIFICATE-----\nMIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt\ncGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV\nBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp\nc2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG\nSM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh\ncUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM\nBgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi\ndGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX\n/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=\n-----END CERTIFICATE-----\nB\016\n\004SHA2\022\006SHA256J\272\006-----BEGIN CERTIFICATE-----\nMIICNTCCAdugAwIBAgIQJmJ4qa5/NvR57KGzT4iHlDAKBggqhkjOPQQDAjBsMQsw\nCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy\nYW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xGjAYBgNVBAMTEXRsc2NhLmV4\nYW1wbGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowbDELMAkG\nA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFu\nY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRowGAYDVQQDExF0bHNjYS5leGFt\ncGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABNOAsCWsc6XhVZDnmVpp\n1pn+BS+S0RBhcauHXAKpyhGs/3uOXZoQkdGPeuo2/8qGlIb6Kb+HbEi7qeJoY8Yr\n9aOjXzBdMA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB\n/wQFMAMBAf8wKQYDVR0OBCIEID0wqXyOxMDMyk9vzwG6Qp5kLqM4D/8zNA5ETxlQ\nlXg6MAoGCCqGSM49BAMCA0gAMEUCIQCAbyOqPBOK1MD7g7XTm2Uim49jaT3M5fcw\nSukC38TogwIgf3HBmRsGd1V3obVdszYRZmBuEq8wRLqS5HZmifZxg9Y=\n-----END CERTIFICATE-----\n" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BatchSize" value:<value:"\010\n\020\200\200\3001\030\200\200 " mod_policy:"Admins" > > values:<key:"BatchTimeout" value:<value:"\n\0022s" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"ChannelRestrictions" value:<mod_policy:"Admins" > > values:<key:"ConsensusType" value:<value:"\n\004solo" mod_policy:"Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"BlockValidation" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > > values:<key:"BlockDataHashingStructure" value:<value:"\010\377\377\377\377\017" mod_policy:"Admins" > > values:<key:"Capabilities" value:<value:"\n\010\n\004V1_1\022\000" mod_policy:"Admins" > > values:<key:"Consortium" value:<value:"\n\020SampleConsortium" mod_policy:"Admins" > > values:<key:"HashingAlgorithm" value:<value:"\n\006SHA256" mod_policy:"Admins" > > values:<key:"OrdererAddresses" value:<value:"\n\030orderer.example.com:7050" mod_policy:"/Channel/Orderer/Admins" > > policies:<key:"Admins" value:<policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" > > policies:<key:"Readers" value:<policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" > > policies:<key:"Writers" value:<policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" > > mod_policy:"Admins" > 
2018-07-03 02:16:34.549 UTC [common/channelconfig] NewStandardValues -> DEBU 4ea Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4eb Processing field: HashingAlgorithm
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ec Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ed Processing field: OrdererAddresses
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ee Processing field: Consortium
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ef Processing field: Capabilities
2018-07-03 02:16:34.549 UTC [common/channelconfig] NewStandardValues -> DEBU 4f0 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f1 Processing field: Capabilities
2018-07-03 02:16:34.549 UTC [common/channelconfig] NewStandardValues -> DEBU 4f2 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f3 Processing field: AnchorPeers
2018-07-03 02:16:34.549 UTC [common/channelconfig] NewStandardValues -> DEBU 4f4 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f5 Processing field: MSP
2018-07-03 02:16:34.549 UTC [common/channelconfig] Validate -> DEBU 4f6 Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.549 UTC [common/channelconfig] validateMSP -> DEBU 4f7 Setting up MSP for org Org2MSP
2018-07-03 02:16:34.549 UTC [common/channelconfig] NewStandardValues -> DEBU 4f8 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4f9 Processing field: AnchorPeers
2018-07-03 02:16:34.549 UTC [common/channelconfig] NewStandardValues -> DEBU 4fa Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.549 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4fb Processing field: MSP
2018-07-03 02:16:34.549 UTC [common/channelconfig] Validate -> DEBU 4fc Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.549 UTC [common/channelconfig] validateMSP -> DEBU 4fd Setting up MSP for org Org1MSP
2018-07-03 02:16:34.550 UTC [common/channelconfig] NewStandardValues -> DEBU 4fe Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ff Processing field: ConsensusType
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 500 Processing field: BatchSize
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 501 Processing field: BatchTimeout
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 502 Processing field: KafkaBrokers
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 503 Processing field: ChannelRestrictions
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 504 Processing field: Capabilities
2018-07-03 02:16:34.550 UTC [common/channelconfig] NewStandardValues -> DEBU 505 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.550 UTC [common/channelconfig] initializeProtosStruct -> DEBU 506 Processing field: MSP
2018-07-03 02:16:34.550 UTC [common/channelconfig] validateMSP -> DEBU 507 Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 508 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 509 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 50a Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 50b Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 50c Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 50d Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 50e Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 50f Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 510 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 511 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 512 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 513 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 514 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 515 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 516 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 517 Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 518 Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 519 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.551 UTC [common/configtx] addToMap -> DEBU 51a Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 51b Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 51c Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 51d Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 51e Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 51f Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 520 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 521 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 522 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 523 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 524 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 525 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 526 Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 527 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 528 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 529 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.565 UTC [common/configtx] addToMap -> DEBU 52a Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.566 UTC [common/configtx] addToMap -> DEBU 52b Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.566 UTC [common/configtx] addToMap -> DEBU 52c Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.566 UTC [common/configtx] addToMap -> DEBU 52d Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.566 UTC [common/configtx] addToMap -> DEBU 52e Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.566 UTC [common/configtx] addToMap -> DEBU 52f Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.566 UTC [common/configtx] addToMap -> DEBU 530 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.566 UTC [lockbasedtxmgr] GetTxSimulationResults -> DEBU 531 Simulation completed, getting simulation results
2018-07-03 02:16:34.566 UTC [lockbasedtxmgr] Done -> DEBU 532 Done with transaction simulation / query execution []
2018-07-03 02:16:34.566 UTC [lockbasedtxmgr] Done -> DEBU 533 Done with transaction simulation / query execution []
2018-07-03 02:16:34.566 UTC [statebasedval] ValidateAndPrepareBatch -> DEBU 534 Block [2] Transaction index [0] TxId [] marked as valid by state validator
2018-07-03 02:16:34.566 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 535 validating rwset...
2018-07-03 02:16:34.566 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 536 postprocessing ProtoBlock...
2018-07-03 02:16:34.566 UTC [valimpl] ValidateAndPrepareBatch -> DEBU 537 ValidateAndPrepareBatch() complete
2018-07-03 02:16:34.566 UTC [kvledger] CommitWithPvtData -> DEBU 538 Channel [mychannel]: Committing block [2] to storage
2018-07-03 02:16:34.573 UTC [pvtdatastorage] Prepare -> DEBU 539 Saved 0 private data write sets for block [2]
2018-07-03 02:16:34.576 UTC [gossip/comm] func1 -> WARN 53a peer0.org1.example.com:7051, PKIid:[163 29 112 95 69 187 19 108 58 133 54 20 98 151 206 128 60 60 62 58 20 208 232 67 123 244 146 23 203 68 247 87] isn't responsive: EOF
2018-07-03 02:16:34.579 UTC [fsblkstorage] indexBlock -> DEBU 53b Indexing block [blockNum=2, blockHash=[]byte{0x22, 0x8d, 0x20, 0xe, 0xe2, 0x5c, 0xa0, 0x3c, 0xd0, 0x74, 0xe9, 0x2d, 0x10, 0x62, 0xf4, 0xb8, 0x5c, 0x9, 0x54, 0xb6, 0x3d, 0xb0, 0x60, 0x23, 0x3b, 0xa0, 0xe3, 0x9b, 0x27, 0xfa, 0xf6, 0xa8} txOffsets=
txId= locPointer=offset=71, bytesLength=15669
]
2018-07-03 02:16:34.579 UTC [fsblkstorage] indexBlock -> DEBU 53c Adding txLoc [fileSuffixNum=0, offset=33198, bytesLength=15669] for tx ID: [] to index
2018-07-03 02:16:34.579 UTC [fsblkstorage] indexBlock -> DEBU 53d Adding txLoc [fileSuffixNum=0, offset=33198, bytesLength=15669] for tx number:[0] ID: [] to blockNumTranNum index
2018-07-03 02:16:34.579 UTC [gossip/discovery] expireDeadMembers -> WARN 53e Entering [[163 29 112 95 69 187 19 108 58 133 54 20 98 151 206 128 60 60 62 58 20 208 232 67 123 244 146 23 203 68 247 87]]
2018-07-03 02:16:34.579 UTC [gossip/discovery] expireDeadMembers -> WARN 53f Closing connection to Endpoint: peer0.org1.example.com:7051, InternalEndpoint: , PKI-ID: [163 29 112 95 69 187 19 108 58 133 54 20 98 151 206 128 60 60 62 58 20 208 232 67 123 244 146 23 203 68 247 87], Metadata: []
2018-07-03 02:16:34.579 UTC [gossip/discovery] expireDeadMembers -> WARN 540 Exiting
2018-07-03 02:16:34.580 UTC [fsblkstorage] updateCheckpoint -> DEBU 541 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[50661], isChainEmpty=[false], lastBlockNumber=[2]
2018-07-03 02:16:34.580 UTC [pvtdatastorage] Commit -> DEBU 542 Committing private data for block [2]
2018-07-03 02:16:34.585 UTC [pvtdatastorage] Commit -> DEBU 543 Committed private data for block [2]
2018-07-03 02:16:34.585 UTC [kvledger] CommitWithPvtData -> INFO 544 Channel [mychannel]: Committed block [2] with 1 transaction(s)
2018-07-03 02:16:34.585 UTC [kvledger] CommitWithPvtData -> DEBU 545 Channel [mychannel]: Committing block [2] transactions to state database
2018-07-03 02:16:34.585 UTC [lockbasedtxmgr] Commit -> DEBU 546 Committing updates to state database
2018-07-03 02:16:34.585 UTC [lockbasedtxmgr] Commit -> DEBU 547 Write lock acquired for committing updates to state database
2018-07-03 02:16:34.585 UTC [stateleveldb] ApplyUpdates -> DEBU 548 Channel [mychannel]: Applying key(string)=[resourcesconfigtx.CHANNEL_CONFIG_KEY] key(bytes)=[[]byte{0x0, 0x72, 0x65, 0x73, 0x6f, 0x75, 0x72, 0x63, 0x65, 0x73, 0x63, 0x6f, 0x6e, 0x66, 0x69, 0x67, 0x74, 0x78, 0x2e, 0x43, 0x48, 0x41, 0x4e, 0x4e, 0x45, 0x4c, 0x5f, 0x43, 0x4f, 0x4e, 0x46, 0x49, 0x47, 0x5f, 0x4b, 0x45, 0x59}]
2018-07-03 02:16:34.604 UTC [lockbasedtxmgr] Commit -> DEBU 549 Updates committed to state database
2018-07-03 02:16:34.604 UTC [kvledger] CommitWithPvtData -> DEBU 54a Channel [mychannel]: Committing block [2] transactions to history database
2018-07-03 02:16:34.604 UTC [historyleveldb] Commit -> DEBU 54b Channel [mychannel]: Updating history database for blockNo [2] with [1] transactions
2018-07-03 02:16:34.604 UTC [historyleveldb] Commit -> DEBU 54c Skipping transaction [0] since it is not an endorsement transaction
2018-07-03 02:16:34.606 UTC [historyleveldb] Commit -> DEBU 54d Channel [mychannel]: Updates committed to history database for blockNo [2]
2018-07-03 02:16:34.606 UTC [eventhub_producer] CreateBlockEvents -> DEBU 54e Entry
2018-07-03 02:16:34.606 UTC [eventhub_producer] CreateBlockEvents -> DEBU 54f Exit
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 550 Entry
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 551 Event processor timeout > 0
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 552 Event sent successfully
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 554 Exit
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 555 Entry
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 556 Event processor timeout > 0
2018-07-03 02:16:34.606 UTC [gossip/comm] func1 -> WARN 553 peer0.org2.example.com:7051, PKIid:[118 128 184 113 89 113 12 35 237 54 105 143 62 211 143 82 9 186 89 105 206 26 47 227 199 141 151 109 90 227 236 3] isn't responsive: EOF
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 557 Event sent successfully
2018-07-03 02:16:34.606 UTC [eventhub_producer] Send -> DEBU 558 Exit
2018-07-03 02:16:34.606 UTC [gossip/discovery] expireDeadMembers -> WARN 559 Entering [[118 128 184 113 89 113 12 35 237 54 105 143 62 211 143 82 9 186 89 105 206 26 47 227 199 141 151 109 90 227 236 3]]
2018-07-03 02:16:34.606 UTC [gossip/discovery] expireDeadMembers -> WARN 55a Closing connection to Endpoint: peer0.org2.example.com:7051, InternalEndpoint: peer0.org2.example.com:7051, PKI-ID: [118 128 184 113 89 113 12 35 237 54 105 143 62 211 143 82 9 186 89 105 206 26 47 227 199 141 151 109 90 227 236 3], Metadata: []
2018-07-03 02:16:34.606 UTC [gossip/discovery] expireDeadMembers -> WARN 55b Exiting
2018-07-03 02:16:36.446 UTC [gossip/gossip] validateMsg -> WARN 55c StateInfo message GossipMessage: tag:CHAN_OR_ORG state_info:<metadata:"\000\000\000\000\000\000\000\002" timestamp:<inc_num:11651379494838206464 seq_num:1530584194600799520 > pki_id:"\303\347\2338\177\177w\377\266\207u\321B\361Q^hT4R/\211:\001\252\034\323\235\202n\006\264" channel_MAC:"\366\370\2641\311\243\272y\211\216\020\233!\313y\223\322H^\227\263\301\237\034\324\207:;\201\252\310%" properties:<ledger_height:2 > > , Envelope: 109 bytes, Signature: 71 bytes is found invalid: PKIID wasn't found
2018-07-03 02:16:36.446 UTC [gossip/gossip] handleMessage -> WARN 55d Message GossipMessage: tag:CHAN_OR_ORG state_info:<metadata:"\000\000\000\000\000\000\000\002" timestamp:<inc_num:11651379494838206464 seq_num:1530584194600799520 > pki_id:"\303\347\2338\177\177w\377\266\207u\321B\361Q^hT4R/\211:\001\252\034\323\235\202n\006\264" channel_MAC:"\366\370\2641\311\243\272y\211\216\020\233!\313y\223\322H^\227\263\301\237\034\324\207:;\201\252\310%" properties:<ledger_height:2 > > , Envelope: 109 bytes, Signature: 71 bytes isn't valid
2018-07-03 02:16:37.402 UTC [gossip/gossip] handleMessage -> WARN 55e Message GossipMessage: tag:EMPTY alive_msg:<membership:<endpoint:"peer1.org1.example.com:7051" pki_id:"\303\347\2338\177\177w\377\266\207u\321B\361Q^hT4R/\211:\001\252\034\323\235\202n\006\264" > timestamp:<inc_num:1530582726168332226 seq_num:1035 > > , Envelope: 84 bytes, Signature: 70 bytes isn't valid
2018-07-03 02:16:37.402 UTC [gossip/gossip] handleMessage -> WARN 55f Message GossipMessage: tag:EMPTY alive_msg:<membership:<endpoint:"peer1.org1.example.com:7051" pki_id:"\303\347\2338\177\177w\377\266\207u\321B\361Q^hT4R/\211:\001\252\034\323\235\202n\006\264" > timestamp:<inc_num:1530582726168332226 seq_num:1035 > > , Envelope: 84 bytes, Signature: 70 bytes isn't valid

