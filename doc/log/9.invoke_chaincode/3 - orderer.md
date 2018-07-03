2018-07-03 05:22:44.639 UTC [orderer/common/server] Broadcast -> DEBU 9c1 Starting new Broadcast handler
2018-07-03 05:22:44.639 UTC [orderer/common/broadcast] Handle -> DEBU 9c2 Starting new broadcast loop for 172.18.0.7:42790
2018-07-03 05:22:44.660 UTC [orderer/common/broadcast] Handle -> DEBU 9c3 [channel: mychannel] Broadcast is processing normal message from 172.18.0.7:42790 with txid 'ced12bdc5044715e61c24e9e2704c0556d672c19fc3a2830a4d18383b8b152d8' of type ENDORSER_TRANSACTION
2018-07-03 05:22:44.660 UTC [policies] Evaluate -> DEBU 9c4 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers ==
2018-07-03 05:22:44.660 UTC [policies] Evaluate -> DEBU 9c5 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 05:22:44.660 UTC [policies] Evaluate -> DEBU 9c6 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers ==
2018-07-03 05:22:44.660 UTC [policies] Evaluate -> DEBU 9c7 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 05:22:44.660 UTC [policies] Evaluate -> DEBU 9c8 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers ==
2018-07-03 05:22:44.660 UTC [cauthdsl] func1 -> DEBU 9c9 0xc420800060 gate 1530595364660866694 evaluation starts
2018-07-03 05:22:44.660 UTC [cauthdsl] func2 -> DEBU 9ca 0xc420800060 signed by 0 principal evaluation starts (used [false])
2018-07-03 05:22:44.660 UTC [cauthdsl] func2 -> DEBU 9cb 0xc420800060 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b54434341644367417749424167495162394f7458584a6e586b4d7a58544c5271556a323754414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d53356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d53356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d477778437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513877445159445651514c45775a6a62476c6c626e5178487a416442674e5642414d4d466b466b62576c75514739790a5a7a45755a586868625842735a53356a623230775754415442676371686b6a4f5051494242676771686b6a4f50514d4242774e4341415164527130364f3679660a4b747348425a57495577533839435967525278673533764e797266654767757264343536584939396e4f614a4756797252654c534966632b45752b67756b30700a634f6a7463336c6335675a726f303077537a414f42674e56485138424166384542414d434234417744415944565230544151482f424149774144417242674e560a48534d454a4441696743425a422f514b4b5841556335375747425a586432506a4d5865672b2b566f33697057666244724931632f457a414b42676771686b6a4f0a5051514441674e48414442454169416d7556374f31556b415574587342534973396e796f355466416f7973777765614a514467734833326b7841496756484e320a534e4c335238314e4a73727a2f754d614239724b64484b656351366e4545396e597163327a474d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 05:22:44.660 UTC [msp] SatisfiesPrincipal -> DEBU 9cc Checking if identity satisfies MEMBER role for Org1MSP
2018-07-03 05:22:44.660 UTC [msp] Validate -> DEBU 9cd MSP Org1MSP validating identity
2018-07-03 05:22:44.661 UTC [msp] getCertificationChain -> DEBU 9ce MSP Org1MSP getting certification chain
2018-07-03 05:22:44.661 UTC [cauthdsl] func2 -> DEBU 9cf 0xc420800060 principal matched by identity 0
2018-07-03 05:22:44.661 UTC [msp/identity] Verify -> DEBU 9d0 Verify: digest = 00000000  7b 4a 8d 6f d3 d1 d4 0a  f5 3f 10 2b 5b 6d 10 b3  |{J.o.....?.+[m..|
00000010  f8 43 b4 b5 71 20 05 86  37 e7 2a 47 3b 79 a9 73  |.C..q ..7.*G;y.s|
2018-07-03 05:22:44.661 UTC [msp/identity] Verify -> DEBU 9d1 Verify: sig = 00000000  30 44 02 20 2d f2 f0 bf  38 5e 29 30 cb 70 1f 47  |0D. -...8^)0.p.G|
00000010  a8 7c 2e ff a5 a8 41 a4  48 68 7b bc d7 89 ce 63  |.|....A.Hh{....c|
00000020  bd 90 b6 48 02 20 2b dd  fa 9c c3 51 22 69 b1 bf  |...H. +....Q"i..|
00000030  d9 81 22 ae 15 bd eb 3a  41 50 fb f7 93 6e 1e 54  |.."....:AP...n.T|
00000040  a1 37 b0 d7 4d fa                                 |.7..M.|
2018-07-03 05:22:44.661 UTC [cauthdsl] func2 -> DEBU 9d2 0xc420800060 principal evaluation succeeds for identity 0
2018-07-03 05:22:44.661 UTC [cauthdsl] func1 -> DEBU 9d3 0xc420800060 gate 1530595364660866694 evaluation succeeds
2018-07-03 05:22:44.661 UTC [policies] Evaluate -> DEBU 9d4 Signature set satisfies policy /Channel/Application/Org1MSP/Writers
2018-07-03 05:22:44.661 UTC [policies] Evaluate -> DEBU 9d5 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers
2018-07-03 05:22:44.661 UTC [policies] Evaluate -> DEBU 9d6 Signature set satisfies policy /Channel/Application/Writers
2018-07-03 05:22:44.661 UTC [policies] Evaluate -> DEBU 9d7 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers
2018-07-03 05:22:44.661 UTC [policies] Evaluate -> DEBU 9d8 Signature set satisfies policy /Channel/Writers
2018-07-03 05:22:44.661 UTC [policies] Evaluate -> DEBU 9d9 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers
2018-07-03 05:22:44.661 UTC [orderer/common/broadcast] Handle -> DEBU 9da [channel: mychannel] Broadcast has successfully enqueued message of type ENDORSER_TRANSACTION from 172.18.0.7:42790
2018-07-03 05:22:44.661 UTC [orderer/common/blockcutter] Ordered -> DEBU 9db Enqueuing message into batch
2018-07-03 05:22:44.662 UTC [orderer/common/broadcast] Handle -> DEBU 9dc Received EOF from 172.18.0.7:42790, hangup
2018-07-03 05:22:44.662 UTC [orderer/common/server] func1 -> DEBU 9dd Closing Broadcast stream
2018-07-03 05:22:44.670 UTC [grpc] Printf -> DEBU 9de transport: http2Server.HandleStreams failed to read frame: read tcp 172.18.0.4:7050->172.18.0.7:42790: read: connection reset by peer

