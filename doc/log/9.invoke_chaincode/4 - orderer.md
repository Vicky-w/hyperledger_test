2018-07-03 05:22:46.662 UTC [orderer/consensus/solo] main -> DEBU 9df Batch timer expired, creating block
2018-07-03 05:22:46.662 UTC [msp] GetLocalMSP -> DEBU 9e0 Returning existing local MSP
2018-07-03 05:22:46.662 UTC [msp] GetDefaultSigningIdentity -> DEBU 9e1 Obtaining default signing identity
2018-07-03 05:22:46.662 UTC [msp] GetLocalMSP -> DEBU 9e2 Returning existing local MSP
2018-07-03 05:22:46.662 UTC [msp] GetDefaultSigningIdentity -> DEBU 9e3 Obtaining default signing identity
2018-07-03 05:22:46.663 UTC [msp/identity] Sign -> DEBU 9e4 Sign: plaintext: 0A90060A0A4F7264657265724D535012...231E92D19B10E844928A269948F2CD41 
2018-07-03 05:22:46.663 UTC [msp/identity] Sign -> DEBU 9e5 Sign: digest: B147155C9873B8AB400A98456F6B3DDD7F248F35DE1AB74B45E7230894FFEAF7 
2018-07-03 05:22:46.663 UTC [msp] GetLocalMSP -> DEBU 9e6 Returning existing local MSP
2018-07-03 05:22:46.663 UTC [msp] GetDefaultSigningIdentity -> DEBU 9e7 Obtaining default signing identity
2018-07-03 05:22:46.663 UTC [orderer/commmon/multichannel] addLastConfigSignature -> DEBU 9e8 [channel: mychannel] About to write block, setting its LAST_CONFIG to 2
2018-07-03 05:22:46.663 UTC [msp] GetLocalMSP -> DEBU 9e9 Returning existing local MSP
2018-07-03 05:22:46.663 UTC [msp] GetDefaultSigningIdentity -> DEBU 9ea Obtaining default signing identity
2018-07-03 05:22:46.663 UTC [msp/identity] Sign -> DEBU 9eb Sign: plaintext: 08020A90060A0A4F7264657265724D53...231E92D19B10E844928A269948F2CD41 
2018-07-03 05:22:46.663 UTC [msp/identity] Sign -> DEBU 9ec Sign: digest: 499AE2864FFCB5E26F19A3E61ACB4F49A87405B74A323C8040A411304FD66383 
2018-07-03 05:22:46.670 UTC [fsblkstorage] indexBlock -> DEBU 9ed Indexing block [blockNum=8, blockHash=[]byte{0xc1, 0x4, 0xfa, 0x6b, 0xb0, 0x49, 0x57, 0xab, 0xb9, 0x47, 0xde, 0x91, 0xc3, 0x11, 0xe5, 0x9, 0x8d, 0x8c, 0xdc, 0x2a, 0x83, 0xd2, 0xca, 0x9d, 0x55, 0x78, 0x10, 0x47, 0x59, 0xd, 0x1d, 0xaa} txOffsets=
txId=ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8 locPointer=offset=70, bytesLength=2968
]
2018-07-03 05:22:46.671 UTC [fsblkstorage] updateCheckpoint -> DEBU 9ee Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[80206], isChainEmpty=[false], lastBlockNumber=[8]
2018-07-03 05:22:46.671 UTC [orderer/commmon/multichannel] commitBlock -> DEBU 9ef [channel: mychannel] Wrote block 8
2018-07-03 05:22:46.671 UTC [fsblkstorage] waitForBlock -> DEBU 9f0 Came out of wait. maxAvailaBlockNumber=[8]
2018-07-03 05:22:46.671 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 9f1 Remaining bytes=[4832], Going to peek [8] bytes
2018-07-03 05:22:46.671 UTC [fsblkstorage] waitForBlock -> DEBU 9f3 Came out of wait. maxAvailaBlockNumber=[8]
2018-07-03 05:22:46.671 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 9f2 Returning blockbytes - length=[4830], placementInfo={fileNum=[0], startOffset=[75374], bytesOffset=[75376]}
2018-07-03 05:22:46.671 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 9f5 blockbytes [4830] read from file [0]
2018-07-03 05:22:46.671 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 9f4 Remaining bytes=[4832], Going to peek [8] bytes
2018-07-03 05:22:46.671 UTC [common/deliver] deliverBlocks -> DEBU 9f7 [channel: mychannel] Delivering block for (0xc420a96660) for 172.18.0.2:55226
2018-07-03 05:22:46.671 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 9f6 Returning blockbytes - length=[4830], placementInfo={fileNum=[0], startOffset=[75374], bytesOffset=[75376]}
2018-07-03 05:22:46.671 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 9f8 blockbytes [4830] read from file [0]
2018-07-03 05:22:46.671 UTC [common/deliver] deliverBlocks -> DEBU 9f9 [channel: mychannel] Delivering block for (0xc420c243c0) for 172.18.0.6:54766
2018-07-03 05:22:46.672 UTC [fsblkstorage] waitForBlock -> DEBU 9fa Going to wait for newer blocks. maxAvailaBlockNumber=[8], waitForBlockNum=[9]
2018-07-03 05:22:46.672 UTC [fsblkstorage] waitForBlock -> DEBU 9fb Going to wait for newer blocks. maxAvailaBlockNumber=[8], waitForBlockNum=[9]

