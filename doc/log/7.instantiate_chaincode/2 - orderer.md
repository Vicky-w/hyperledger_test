2018-07-03 02:34:08.441 UTC [orderer/common/server] Broadcast -> DEBU 88e Starting new Broadcast handler
2018-07-03 02:34:08.441 UTC [orderer/common/broadcast] Handle -> DEBU 88f Starting new broadcast loop for 172.18.0.7:42762
2018-07-03 02:34:17.687 UTC [orderer/common/broadcast] Handle -> DEBU 890 [channel: mychannel] Broadcast is processing normal message from 172.18.0.7:42762 with txid '3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c' of type ENDORSER_TRANSACTION
2018-07-03 02:34:17.699 UTC [policies] Evaluate -> DEBU 891 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers ==
2018-07-03 02:34:17.700 UTC [policies] Evaluate -> DEBU 892 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:34:17.700 UTC [policies] Evaluate -> DEBU 893 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers ==
2018-07-03 02:34:17.700 UTC [policies] Evaluate -> DEBU 894 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:34:17.700 UTC [policies] Evaluate -> DEBU 895 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers ==
2018-07-03 02:34:17.700 UTC [msp] DeserializeIdentity -> INFO 896 Obtaining identity
2018-07-03 02:34:17.701 UTC [msp/identity] newIdentity -> DEBU 897 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKjCCAdGgAwIBAgIRAMLlXa0OL9IXZbTJ79UqyfEwCgYIKoZIzj0EAwIwczEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xGTAXBgNVBAoTEG9yZzIuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh
Lm9yZzIuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5
WjBsMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN
U2FuIEZyYW5jaXNjbzEPMA0GA1UECxMGY2xpZW50MR8wHQYDVQQDDBZBZG1pbkBv
cmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEKhVugIuS
piH5hFoxQNSTH+IA4eb+KGFZ2+486Tr1ptN8DjdXIdCKQB3JC4aYpj4zJ2oTTiwr
/+ym9H7N1Sk6PKNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYD
VR0jBCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZI
zj0EAwIDRwAwRAIgf3OLkdcZAwktri6kHgIJl2jErdLg7LfELdZh4xX6vqMCIHJA
ZzkeIB4wB0O59pF9oC0fOGuzmGhz6mBAFAK8Qk+C
-----END CERTIFICATE-----
2018-07-03 02:34:17.702 UTC [cauthdsl] func1 -> DEBU 898 0xc420800060 gate 1530585257702178130 evaluation starts
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 899 0xc420800060 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 89a 0xc420800060 processing identity 0 with bytes of 0a074f7267324d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b6a4343416447674177494241674952414d4c6c5861304f4c3949585a62544a3739557179664577436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a49755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a49755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42734d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a45504d4130474131554543784d47593278705a5735304d523877485159445651514444425a425a473170626b42760a636d63794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a304441516344516741454b685675674975530a7069483568466f78514e5354482b49413465622b4b47465a322b34383654723170744e38446a64584964434b5142334a43346159706a347a4a326f54546977720a2f2b796d3948374e31536b36504b4e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759440a5652306a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a490a7a6a304541774944527741775241496766334f4c6b64635a41776b747269366b4867494a6c326a4572644c67374c66454c645a683478583676714d4349484a410a5a7a6b654942347742304f35397046396f4330664f47757a6d47687a366d424146414b38516b2b430a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 89b 0xc420800060 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected Org1MSP, got Org2MSP)
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 89c 0xc420800060 principal evaluation fails
2018-07-03 02:34:17.702 UTC [cauthdsl] func1 -> DEBU 89d 0xc420800060 gate 1530585257702178130 evaluation fails
2018-07-03 02:34:17.702 UTC [policies] Evaluate -> DEBU 89e Signature set did not satisfy policy /Channel/Application/Org1MSP/Writers
2018-07-03 02:34:17.702 UTC [policies] Evaluate -> DEBU 89f == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers
2018-07-03 02:34:17.702 UTC [policies] Evaluate -> DEBU 8a0 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers ==
2018-07-03 02:34:17.702 UTC [cauthdsl] func1 -> DEBU 8a1 0xc4208000e0 gate 1530585257702451692 evaluation starts
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 8a2 0xc4208000e0 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 8a3 0xc4208000e0 processing identity 0 with bytes of 0a074f7267324d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b6a4343416447674177494241674952414d4c6c5861304f4c3949585a62544a3739557179664577436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a49755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a49755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42734d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a45504d4130474131554543784d47593278705a5735304d523877485159445651514444425a425a473170626b42760a636d63794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a304441516344516741454b685675674975530a7069483568466f78514e5354482b49413465622b4b47465a322b34383654723170744e38446a64584964434b5142334a43346159706a347a4a326f54546977720a2f2b796d3948374e31536b36504b4e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759440a5652306a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a490a7a6a304541774944527741775241496766334f4c6b64635a41776b747269366b4867494a6c326a4572644c67374c66454c645a683478583676714d4349484a410a5a7a6b654942347742304f35397046396f4330664f47757a6d47687a366d424146414b38516b2b430a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:34:17.702 UTC [msp] SatisfiesPrincipal -> DEBU 8a4 Checking if identity satisfies MEMBER role for Org2MSP
2018-07-03 02:34:17.702 UTC [msp] Validate -> DEBU 8a5 MSP Org2MSP validating identity
2018-07-03 02:34:17.702 UTC [msp] getCertificationChain -> DEBU 8a6 MSP Org2MSP getting certification chain
2018-07-03 02:34:17.702 UTC [cauthdsl] func2 -> DEBU 8a7 0xc4208000e0 principal matched by identity 0
2018-07-03 02:34:17.703 UTC [msp/identity] Verify -> DEBU 8a8 Verify: digest = 00000000  8f 9e db f3 d5 ba dc b4  46 47 07 1f a2 f3 ae 8a  |........FG......|
00000010  17 dd 41 00 43 b8 2e fc  00 2c 32 c1 5e 51 60 24  |..A.C....,2.^Q`$|
2018-07-03 02:34:17.703 UTC [msp/identity] Verify -> DEBU 8a9 Verify: sig = 00000000  30 44 02 20 43 78 ef df  0c 4a fd f3 47 02 45 b4  |0D. Cx...J..G.E.|
00000010  09 d5 77 9e fc df a4 ae  f3 33 55 a1 9b 45 cb 6f  |..w......3U..E.o|
00000020  33 55 90 a5 02 20 55 ce  dd c5 28 20 2d ef 5b 96  |3U... U...( -.[.|
00000030  d4 a9 62 c0 99 87 dd 9d  0d b5 84 88 0a a1 96 12  |..b.............|
00000040  76 5f 2c 2c 81 ee                                 |v_,,..|
2018-07-03 02:34:17.703 UTC [cauthdsl] func2 -> DEBU 8aa 0xc4208000e0 principal evaluation succeeds for identity 0
2018-07-03 02:34:17.703 UTC [cauthdsl] func1 -> DEBU 8ab 0xc4208000e0 gate 1530585257702451692 evaluation succeeds
2018-07-03 02:34:17.703 UTC [policies] Evaluate -> DEBU 8ac Signature set satisfies policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:34:17.703 UTC [policies] Evaluate -> DEBU 8ad == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:34:17.703 UTC [policies] Evaluate -> DEBU 8ae Signature set satisfies policy /Channel/Application/Writers
2018-07-03 02:34:17.703 UTC [policies] Evaluate -> DEBU 8af == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers
2018-07-03 02:34:17.703 UTC [policies] Evaluate -> DEBU 8b0 Signature set satisfies policy /Channel/Writers
2018-07-03 02:34:17.703 UTC [policies] Evaluate -> DEBU 8b1 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers
2018-07-03 02:34:17.703 UTC [orderer/common/broadcast] Handle -> DEBU 8b2 [channel: mychannel] Broadcast has successfully enqueued message of type ENDORSER_TRANSACTION from 172.18.0.7:42762
2018-07-03 02:34:17.703 UTC [orderer/common/blockcutter] Ordered -> DEBU 8b3 Enqueuing message into batch
2018-07-03 02:34:17.710 UTC [orderer/common/broadcast] Handle -> DEBU 8b4 Received EOF from 172.18.0.7:42762, hangup
2018-07-03 02:34:17.710 UTC [orderer/common/server] func1 -> DEBU 8b5 Closing Broadcast stream
2018-07-03 02:34:19.704 UTC [orderer/consensus/solo] main -> DEBU 8b6 Batch timer expired, creating block
2018-07-03 02:34:19.710 UTC [msp] GetLocalMSP -> DEBU 8b7 Returning existing local MSP
2018-07-03 02:34:19.710 UTC [msp] GetDefaultSigningIdentity -> DEBU 8b8 Obtaining default signing identity
2018-07-03 02:34:19.711 UTC [msp] GetLocalMSP -> DEBU 8b9 Returning existing local MSP
2018-07-03 02:34:19.711 UTC [msp] GetDefaultSigningIdentity -> DEBU 8ba Obtaining default signing identity
2018-07-03 02:34:19.711 UTC [msp/identity] Sign -> DEBU 8bb Sign: plaintext: 0A90060A0A4F7264657265724D535012...B5FBA73F5EBC112AB3FE46E7FF0155CD 
2018-07-03 02:34:19.711 UTC [msp/identity] Sign -> DEBU 8bc Sign: digest: 944F36E76E213247A28CF56D06A93B46726395EC8B129AD0CCF340BD34619385 
2018-07-03 02:34:19.712 UTC [msp] GetLocalMSP -> DEBU 8bd Returning existing local MSP
2018-07-03 02:34:19.712 UTC [msp] GetDefaultSigningIdentity -> DEBU 8be Obtaining default signing identity
2018-07-03 02:34:19.712 UTC [orderer/commmon/multichannel] addLastConfigSignature -> DEBU 8bf [channel: mychannel] About to write block, setting its LAST_CONFIG to 2
2018-07-03 02:34:19.713 UTC [msp] GetLocalMSP -> DEBU 8c0 Returning existing local MSP
2018-07-03 02:34:19.713 UTC [msp] GetDefaultSigningIdentity -> DEBU 8c1 Obtaining default signing identity
2018-07-03 02:34:19.713 UTC [msp/identity] Sign -> DEBU 8c2 Sign: plaintext: 08020A90060A0A4F7264657265724D53...B5FBA73F5EBC112AB3FE46E7FF0155CD 
2018-07-03 02:34:19.713 UTC [msp/identity] Sign -> DEBU 8c3 Sign: digest: A39084994261AF9180FA5C90D259678AD0E30E2EFD6F9C09C93D2F5ED3CFBFD2 
2018-07-03 02:34:19.729 UTC [fsblkstorage] indexBlock -> DEBU 8c4 Indexing block [blockNum=3, blockHash=[]byte{0x1f, 0x6f, 0xfe, 0x4d, 0x3d, 0x11, 0x9f, 0xa0, 0x86, 0x6b, 0xf3, 0x64, 0x19, 0x4d, 0x16, 0x44, 0x9c, 0x9e, 0x43, 0xa4, 0xc4, 0x70, 0xde, 0xef, 0x8, 0x60, 0xcb, 0xa2, 0x3e, 0xac, 0xb7, 0x96} txOffsets=
txId=3c7ea62025d44933bbba1b4a18d92e89ccb1c2bccdd7f8dace083ef7a1fc186c locPointer=offset=70, bytesLength=3526
]
2018-07-03 02:34:19.732 UTC [fsblkstorage] updateCheckpoint -> DEBU 8c5 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[56047], isChainEmpty=[false], lastBlockNumber=[3]
2018-07-03 02:34:19.732 UTC [orderer/commmon/multichannel] commitBlock -> DEBU 8c6 [channel: mychannel] Wrote block 3
2018-07-03 02:34:19.732 UTC [fsblkstorage] waitForBlock -> DEBU 8c7 Came out of wait. maxAvailaBlockNumber=[3]
2018-07-03 02:34:19.733 UTC [fsblkstorage] waitForBlock -> DEBU 8c8 Came out of wait. maxAvailaBlockNumber=[3]
2018-07-03 02:34:19.733 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 8c9 Remaining bytes=[5389], Going to peek [8] bytes
2018-07-03 02:34:19.733 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 8cb Remaining bytes=[5389], Going to peek [8] bytes
2018-07-03 02:34:19.733 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 8ca Returning blockbytes - length=[5387], placementInfo={fileNum=[0], startOffset=[50658], bytesOffset=[50660]}
2018-07-03 02:34:19.734 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 8cd blockbytes [5387] read from file [0]
2018-07-03 02:34:19.733 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 8cc Returning blockbytes - length=[5387], placementInfo={fileNum=[0], startOffset=[50658], bytesOffset=[50660]}
2018-07-03 02:34:19.735 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 8ce blockbytes [5387] read from file [0]
2018-07-03 02:34:19.735 UTC [common/deliver] deliverBlocks -> DEBU 8cf [channel: mychannel] Delivering block for (0xc420a96660) for 172.18.0.2:55226
2018-07-03 02:34:19.736 UTC [common/deliver] deliverBlocks -> DEBU 8d0 [channel: mychannel] Delivering block for (0xc420c243c0) for 172.18.0.6:54766
2018-07-03 02:34:19.736 UTC [fsblkstorage] waitForBlock -> DEBU 8d1 Going to wait for newer blocks. maxAvailaBlockNumber=[3], waitForBlockNum=[4]
2018-07-03 02:34:19.737 UTC [fsblkstorage] waitForBlock -> DEBU 8d2 Going to wait for newer blocks. maxAvailaBlockNumber=[3], waitForBlockNum=[4]

