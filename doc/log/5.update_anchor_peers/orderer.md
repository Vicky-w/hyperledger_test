2018-07-03 02:16:31.324 UTC [orderer/common/server] Deliver -> DEBU 420 Starting new Deliver handler
2018-07-03 02:16:31.324 UTC [common/deliver] Handle -> DEBU 421 Starting new deliver loop for 172.18.0.7:42712
2018-07-03 02:16:31.324 UTC [common/deliver] Handle -> DEBU 422 Attempting to read seek info message from 172.18.0.7:42712
2018-07-03 02:16:31.329 UTC [orderer/common/server] Broadcast -> DEBU 423 Starting new Broadcast handler
2018-07-03 02:16:31.329 UTC [orderer/common/broadcast] Handle -> DEBU 424 Starting new broadcast loop for 172.18.0.7:42714
2018-07-03 02:16:31.329 UTC [orderer/common/broadcast] Handle -> DEBU 425 [channel: mychannel] Broadcast is processing config update message from 172.18.0.7:42714
2018-07-03 02:16:31.329 UTC [orderer/common/msgprocessor] ProcessConfigUpdateMsg -> DEBU 426 Processing config update message for channel mychannel
2018-07-03 02:16:31.329 UTC [policies] Evaluate -> DEBU 427 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers ==
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 428 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 429 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Orderer/Writers ==
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 42a This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 42b == Evaluating *cauthdsl.policy Policy /Channel/Orderer/OrdererOrg/Writers ==
2018-07-03 02:16:31.330 UTC [cauthdsl] func1 -> DEBU 42c 0xc42000e060 gate 1530584191330067384 evaluation starts
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 42d 0xc42000e060 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 42e 0xc42000e060 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b54434341644367417749424167495162394f7458584a6e586b4d7a58544c5271556a323754414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d53356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d53356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d477778437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513877445159445651514c45775a6a62476c6c626e5178487a416442674e5642414d4d466b466b62576c75514739790a5a7a45755a586868625842735a53356a623230775754415442676371686b6a4f5051494242676771686b6a4f50514d4242774e4341415164527130364f3679660a4b747348425a57495577533839435967525278673533764e797266654767757264343536584939396e4f614a4756797252654c534966632b45752b67756b30700a634f6a7463336c6335675a726f303077537a414f42674e56485138424166384542414d434234417744415944565230544151482f424149774144417242674e560a48534d454a4441696743425a422f514b4b5841556335375747425a586432506a4d5865672b2b566f33697057666244724931632f457a414b42676771686b6a4f0a5051514441674e48414442454169416d7556374f31556b415574587342534973396e796f355466416f7973777765614a514467734833326b7841496756484e320a534e4c335238314e4a73727a2f754d614239724b64484b656351366e4545396e597163327a474d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 42f 0xc42000e060 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected OrdererMSP, got Org1MSP)
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 430 0xc42000e060 principal evaluation fails
2018-07-03 02:16:31.330 UTC [cauthdsl] func1 -> DEBU 431 0xc42000e060 gate 1530584191330067384 evaluation fails
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 432 Signature set did not satisfy policy /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 433 == Done Evaluating *cauthdsl.policy Policy /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.330 UTC [policies] func1 -> DEBU 434 Evaluation Failed: Only 0 policies were satisfied, but needed 1 of [ OrdererOrg.Writers ]
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 435 Signature set did not satisfy policy /Channel/Orderer/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 436 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Orderer/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 437 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers ==
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 438 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 439 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers ==
2018-07-03 02:16:31.330 UTC [cauthdsl] func1 -> DEBU 43a 0xc42000e068 gate 1530584191330212664 evaluation starts
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 43b 0xc42000e068 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 43c 0xc42000e068 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b54434341644367417749424167495162394f7458584a6e586b4d7a58544c5271556a323754414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d53356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d53356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d477778437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513877445159445651514c45775a6a62476c6c626e5178487a416442674e5642414d4d466b466b62576c75514739790a5a7a45755a586868625842735a53356a623230775754415442676371686b6a4f5051494242676771686b6a4f50514d4242774e4341415164527130364f3679660a4b747348425a57495577533839435967525278673533764e797266654767757264343536584939396e4f614a4756797252654c534966632b45752b67756b30700a634f6a7463336c6335675a726f303077537a414f42674e56485138424166384542414d434234417744415944565230544151482f424149774144417242674e560a48534d454a4441696743425a422f514b4b5841556335375747425a586432506a4d5865672b2b566f33697057666244724931632f457a414b42676771686b6a4f0a5051514441674e48414442454169416d7556374f31556b415574587342534973396e796f355466416f7973777765614a514467734833326b7841496756484e320a534e4c335238314e4a73727a2f754d614239724b64484b656351366e4545396e597163327a474d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 43d 0xc42000e068 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected Org2MSP, got Org1MSP)
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 43e 0xc42000e068 principal evaluation fails
2018-07-03 02:16:31.330 UTC [cauthdsl] func1 -> DEBU 43f 0xc42000e068 gate 1530584191330212664 evaluation fails
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 440 Signature set did not satisfy policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 441 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 442 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers ==
2018-07-03 02:16:31.330 UTC [cauthdsl] func1 -> DEBU 443 0xc42000e078 gate 1530584191330274490 evaluation starts
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 444 0xc42000e078 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 445 0xc42000e078 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b54434341644367417749424167495162394f7458584a6e586b4d7a58544c5271556a323754414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d53356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d53356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d477778437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513877445159445651514c45775a6a62476c6c626e5178487a416442674e5642414d4d466b466b62576c75514739790a5a7a45755a586868625842735a53356a623230775754415442676371686b6a4f5051494242676771686b6a4f50514d4242774e4341415164527130364f3679660a4b747348425a57495577533839435967525278673533764e797266654767757264343536584939396e4f614a4756797252654c534966632b45752b67756b30700a634f6a7463336c6335675a726f303077537a414f42674e56485138424166384542414d434234417744415944565230544151482f424149774144417242674e560a48534d454a4441696743425a422f514b4b5841556335375747425a586432506a4d5865672b2b566f33697057666244724931632f457a414b42676771686b6a4f0a5051514441674e48414442454169416d7556374f31556b415574587342534973396e796f355466416f7973777765614a514467734833326b7841496756484e320a534e4c335238314e4a73727a2f754d614239724b64484b656351366e4545396e597163327a474d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.330 UTC [msp] SatisfiesPrincipal -> DEBU 446 Checking if identity satisfies MEMBER role for Org1MSP
2018-07-03 02:16:31.330 UTC [msp] Validate -> DEBU 447 MSP Org1MSP validating identity
2018-07-03 02:16:31.330 UTC [msp] getCertificationChain -> DEBU 448 MSP Org1MSP getting certification chain
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 449 0xc42000e078 principal matched by identity 0
2018-07-03 02:16:31.330 UTC [msp/identity] Verify -> DEBU 44a Verify: digest = 00000000  1c 5a 1c 3c 44 44 74 62  f0 ec 0d 68 1d 4b b5 53  |.Z.<DDtb...h.K.S|
00000010  c0 af 96 5e 1a e3 24 d2  05 f9 66 e6 8e eb 99 9a  |...^..$...f.....|
2018-07-03 02:16:31.330 UTC [msp/identity] Verify -> DEBU 44b Verify: sig = 00000000  30 44 02 20 40 92 9e 25  74 b1 e8 c3 85 7e ef 93  |0D. @..%t....~..|
00000010  e6 9d 89 52 08 20 43 7b  1c f0 8c 54 48 c6 bf 01  |...R. C{...TH...|
00000020  f0 11 98 4a 02 20 38 d4  97 dc 5e 12 14 eb 9d 63  |...J. 8...^....c|
00000030  78 c9 60 90 ef c8 39 26  8b b1 f6 f2 9f 86 fe f4  |x.`...9&........|
00000040  44 f6 9c c3 69 17                                 |D...i.|
2018-07-03 02:16:31.330 UTC [cauthdsl] func2 -> DEBU 44c 0xc42000e078 principal evaluation succeeds for identity 0
2018-07-03 02:16:31.330 UTC [cauthdsl] func1 -> DEBU 44d 0xc42000e078 gate 1530584191330274490 evaluation succeeds
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 44e Signature set satisfies policy /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 44f == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 450 Signature set satisfies policy /Channel/Application/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 451 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 452 Signature set satisfies policy /Channel/Writers
2018-07-03 02:16:31.330 UTC [policies] Evaluate -> DEBU 453 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 454 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 455 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 456 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 457 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 458 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 459 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.330 UTC [common/configtx] addToMap -> DEBU 45a Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 45b Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 45c Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 45d Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 45e Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 45f Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 460 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 461 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.331 UTC [common/configtx] addToMap -> DEBU 462 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.331 UTC [common/configtx] verifyDeltaSet -> DEBU 463 Processing change to key: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.331 UTC [common/configtx] policyForItem -> DEBU 464 Getting policy for item Org1MSP with mod_policy Admins
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 465 Manager Channel looking up path [Application]
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 466 Manager Channel has managers Orderer
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 467 Manager Channel has managers Application
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 468 Manager Channel/Application looking up path []
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 469 Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 46a Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 46b Manager Channel/Application looking up path [Org1MSP]
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 46c Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 46d Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:31.331 UTC [policies] Manager -> DEBU 46e Manager Channel/Application/Org1MSP looking up path []
2018-07-03 02:16:31.331 UTC [policies] Evaluate -> DEBU 46f == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Admins ==
2018-07-03 02:16:31.331 UTC [cauthdsl] func1 -> DEBU 470 0xc42000e828 gate 1530584191331575513 evaluation starts
2018-07-03 02:16:31.331 UTC [cauthdsl] func2 -> DEBU 471 0xc42000e828 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.331 UTC [cauthdsl] func2 -> DEBU 472 0xc42000e828 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b54434341644367417749424167495162394f7458584a6e586b4d7a58544c5271556a323754414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d53356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d53356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d477778437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513877445159445651514c45775a6a62476c6c626e5178487a416442674e5642414d4d466b466b62576c75514739790a5a7a45755a586868625842735a53356a623230775754415442676371686b6a4f5051494242676771686b6a4f50514d4242774e4341415164527130364f3679660a4b747348425a57495577533839435967525278673533764e797266654767757264343536584939396e4f614a4756797252654c534966632b45752b67756b30700a634f6a7463336c6335675a726f303077537a414f42674e56485138424166384542414d434234417744415944565230544151482f424149774144417242674e560a48534d454a4441696743425a422f514b4b5841556335375747425a586432506a4d5865672b2b566f33697057666244724931632f457a414b42676771686b6a4f0a5051514441674e48414442454169416d7556374f31556b415574587342534973396e796f355466416f7973777765614a514467734833326b7841496756484e320a534e4c335238314e4a73727a2f754d614239724b64484b656351366e4545396e597163327a474d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.331 UTC [msp] SatisfiesPrincipal -> DEBU 473 Checking if identity satisfies ADMIN role for Org1MSP
2018-07-03 02:16:31.331 UTC [cauthdsl] func2 -> DEBU 474 0xc42000e828 principal matched by identity 0
2018-07-03 02:16:31.331 UTC [msp/identity] Verify -> DEBU 475 Verify: digest = 00000000  5a d8 07 b8 ed 36 3a 61  4b ec a7 fd 75 0d 7d 3f  |Z....6:aK...u.}?|
00000010  7d b5 7a 2e 2e c7 1e dc  c7 86 72 4e 63 9a 7e 74  |}.z.......rNc.~t|
2018-07-03 02:16:31.331 UTC [msp/identity] Verify -> DEBU 476 Verify: sig = 00000000  30 45 02 21 00 a6 ba f1  33 82 df 04 09 82 2a bc  |0E.!....3.....*.|
00000010  06 16 f1 73 f4 5f f4 61  e6 1f 0c f5 45 ad d2 c2  |...s._.a....E...|
00000020  12 e1 11 e3 21 02 20 6c  d9 fa 59 8c c7 e1 9f d2  |....!. l..Y.....|
00000030  15 14 99 af d9 96 eb 63  a2 1b fc e6 57 03 d7 58  |.......c....W..X|
00000040  89 98 dd 9b 9f 7e 20                              |.....~ |
2018-07-03 02:16:31.331 UTC [cauthdsl] func2 -> DEBU 477 0xc42000e828 principal evaluation succeeds for identity 0
2018-07-03 02:16:31.331 UTC [cauthdsl] func1 -> DEBU 478 0xc42000e828 gate 1530584191331575513 evaluation succeeds
2018-07-03 02:16:31.331 UTC [policies] Evaluate -> DEBU 479 Signature set satisfies policy /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.331 UTC [policies] Evaluate -> DEBU 47a == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.331 UTC [common/configtx] verifyDeltaSet -> DEBU 47b Processing change to key: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 47c Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 47d Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 47e Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 47f Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 480 Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 481 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.331 UTC [common/configtx] recurseConfigMap -> DEBU 482 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 483 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 484 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 485 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 486 Setting policy for key Admins to 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 487 Setting policy for key Readers to 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 488 Setting policy for key Writers to 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 489 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 48a Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 48b Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 48c Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 48d Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/configtx] recurseConfigMap -> DEBU 48e Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.332 UTC [common/channelconfig] NewStandardValues -> DEBU 48f Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 490 Processing field: HashingAlgorithm
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 491 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 492 Processing field: OrdererAddresses
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 493 Processing field: Consortium
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 494 Processing field: Capabilities
2018-07-03 02:16:31.332 UTC [common/channelconfig] NewStandardValues -> DEBU 495 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 496 Processing field: ConsensusType
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 497 Processing field: BatchSize
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 498 Processing field: BatchTimeout
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 499 Processing field: KafkaBrokers
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49a Processing field: ChannelRestrictions
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49b Processing field: Capabilities
2018-07-03 02:16:31.332 UTC [common/channelconfig] NewStandardValues -> DEBU 49c Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 49d Processing field: MSP
2018-07-03 02:16:31.332 UTC [common/channelconfig] validateMSP -> DEBU 49e Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.332 UTC [msp] newBccspMsp -> DEBU 49f Creating BCCSP-based MSP instance
2018-07-03 02:16:31.332 UTC [msp] New -> DEBU 4a0 Creating Cache-MSP instance
2018-07-03 02:16:31.332 UTC [msp] Setup -> DEBU 4a1 Setting up MSP instance OrdererMSP
2018-07-03 02:16:31.332 UTC [msp/identity] newIdentity -> DEBU 4a2 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w
bGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE
BhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz
Y28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv
bTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn
Hpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd
MA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB
Af8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG
CCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj
ZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=
-----END CERTIFICATE-----
2018-07-03 02:16:31.332 UTC [msp/identity] newIdentity -> DEBU 4a3 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt
cGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV
BAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp
c2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG
SM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh
cUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM
BgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi
dGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX
/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=
-----END CERTIFICATE-----
2018-07-03 02:16:31.332 UTC [msp] Validate -> DEBU 4a4 MSP OrdererMSP validating identity
2018-07-03 02:16:31.332 UTC [common/channelconfig] NewStandardValues -> DEBU 4a5 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a6 Processing field: Capabilities
2018-07-03 02:16:31.332 UTC [common/channelconfig] NewStandardValues -> DEBU 4a7 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4a8 Processing field: AnchorPeers
2018-07-03 02:16:31.332 UTC [common/channelconfig] NewStandardValues -> DEBU 4a9 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.332 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4aa Processing field: MSP
2018-07-03 02:16:31.332 UTC [common/channelconfig] Validate -> DEBU 4ab Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.332 UTC [common/channelconfig] validateMSP -> DEBU 4ac Setting up MSP for org Org2MSP
2018-07-03 02:16:31.332 UTC [msp] newBccspMsp -> DEBU 4ad Creating BCCSP-based MSP instance
2018-07-03 02:16:31.333 UTC [msp] New -> DEBU 4ae Creating Cache-MSP instance
2018-07-03 02:16:31.333 UTC [msp] Setup -> DEBU 4af Setting up MSP instance Org2MSP
2018-07-03 02:16:31.333 UTC [msp/identity] newIdentity -> DEBU 4b0 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn
b3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d
b+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl
TmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13
G4VS/ZlT
-----END CERTIFICATE-----
2018-07-03 02:16:31.333 UTC [msp/identity] newIdentity -> DEBU 4b1 Creating identity instance for cert -----BEGIN CERTIFICATE-----
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
2018-07-03 02:16:31.333 UTC [msp] SatisfiesPrincipal -> DEBU 4b2 Checking if identity satisfies role [CLIENT] for Org2MSP
2018-07-03 02:16:31.333 UTC [msp] Validate -> DEBU 4b3 MSP Org2MSP validating identity
2018-07-03 02:16:31.333 UTC [msp] getCertificationChain -> DEBU 4b4 MSP Org2MSP getting certification chain
2018-07-03 02:16:31.333 UTC [msp] hasOURole -> DEBU 4b5 MSP Org2MSP checking if the identity is a client
2018-07-03 02:16:31.333 UTC [msp] getCertificationChain -> DEBU 4b6 MSP Org2MSP getting certification chain
2018-07-03 02:16:31.333 UTC [common/channelconfig] NewStandardValues -> DEBU 4b7 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.333 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4b8 Processing field: AnchorPeers
2018-07-03 02:16:31.333 UTC [common/channelconfig] NewStandardValues -> DEBU 4b9 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.333 UTC [common/channelconfig] initializeProtosStruct -> DEBU 4ba Processing field: MSP
2018-07-03 02:16:31.333 UTC [common/channelconfig] Validate -> DEBU 4bb Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.333 UTC [common/channelconfig] validateMSP -> DEBU 4bc Setting up MSP for org Org1MSP
2018-07-03 02:16:31.333 UTC [msp] newBccspMsp -> DEBU 4bd Creating BCCSP-based MSP instance
2018-07-03 02:16:31.333 UTC [msp] New -> DEBU 4be Creating Cache-MSP instance
2018-07-03 02:16:31.333 UTC [msp] Setup -> DEBU 4bf Setting up MSP instance Org1MSP
2018-07-03 02:16:31.334 UTC [msp/identity] newIdentity -> DEBU 4c0 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
QjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k
kp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj
4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1
EAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo
JaPsTQzNKw==
-----END CERTIFICATE-----
2018-07-03 02:16:31.334 UTC [msp/identity] newIdentity -> DEBU 4c1 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y
ZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf
KtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p
cOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV
HSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO
PQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2
SNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=
-----END CERTIFICATE-----
2018-07-03 02:16:31.334 UTC [msp] SatisfiesPrincipal -> DEBU 4c2 Checking if identity satisfies role [CLIENT] for Org1MSP
2018-07-03 02:16:31.334 UTC [msp] Validate -> DEBU 4c3 MSP Org1MSP validating identity
2018-07-03 02:16:31.334 UTC [msp] getCertificationChain -> DEBU 4c4 MSP Org1MSP getting certification chain
2018-07-03 02:16:31.334 UTC [msp] hasOURole -> DEBU 4c5 MSP Org1MSP checking if the identity is a client
2018-07-03 02:16:31.334 UTC [msp] getCertificationChain -> DEBU 4c6 MSP Org1MSP getting certification chain
2018-07-03 02:16:31.334 UTC [msp] Setup -> DEBU 4c7 Setting up the MSP manager (3 msps)
2018-07-03 02:16:31.334 UTC [msp] Setup -> DEBU 4c8 MSP manager setup complete, setup 3 msps
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4c9 Proposed new policy Writers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4ca Proposed new policy Admins for Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4cb Proposed new policy Readers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4cc Proposed new policy Writers for Channel/Orderer
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4cd Proposed new policy BlockValidation for Channel/Orderer
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4ce Proposed new policy Admins for Channel/Orderer
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4cf Proposed new policy Readers for Channel/Orderer
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d0 Proposed new policy Writers for Channel/Application/Org2MSP
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d1 Proposed new policy Admins for Channel/Application/Org2MSP
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d2 Proposed new policy Readers for Channel/Application/Org2MSP
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d3 Proposed new policy Readers for Channel/Application/Org1MSP
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d4 Proposed new policy Writers for Channel/Application/Org1MSP
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d5 Proposed new policy Admins for Channel/Application/Org1MSP
2018-07-03 02:16:31.334 UTC [policies] NewManagerImpl -> DEBU 4d6 Proposed new policy Readers for Channel/Application
2018-07-03 02:16:31.335 UTC [policies] NewManagerImpl -> DEBU 4d7 Proposed new policy Writers for Channel/Application
2018-07-03 02:16:31.335 UTC [policies] NewManagerImpl -> DEBU 4d8 Proposed new policy Admins for Channel/Application
2018-07-03 02:16:31.335 UTC [policies] NewManagerImpl -> DEBU 4d9 Proposed new policy Readers for Channel
2018-07-03 02:16:31.335 UTC [policies] NewManagerImpl -> DEBU 4da Proposed new policy Writers for Channel
2018-07-03 02:16:31.335 UTC [policies] NewManagerImpl -> DEBU 4db Proposed new policy Admins for Channel
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4dc Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4dd Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4de Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4df Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e0 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e1 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e2 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e3 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e4 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e5 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e6 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e7 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e8 Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4e9 Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4ea Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4eb Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4ec Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4ed Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4ee Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4ef Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f0 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f1 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f2 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f3 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f4 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f5 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f6 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f7 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f8 Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.335 UTC [common/configtx] addToMap -> DEBU 4f9 Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 4fa Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 4fb Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 4fc Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 4fd Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 4fe Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 4ff Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 500 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 501 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 502 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.336 UTC [common/configtx] addToMap -> DEBU 503 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.336 UTC [common/channelconfig] LogSanityChecks -> DEBU 504 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:31.336 UTC [common/channelconfig] LogSanityChecks -> DEBU 505 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 506 Manager Channel looking up path [Application]
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 507 Manager Channel has managers Orderer
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 508 Manager Channel has managers Application
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 509 Manager Channel/Application looking up path []
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 50a Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 50b Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:31.336 UTC [common/channelconfig] LogSanityChecks -> DEBU 50c As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:31.336 UTC [common/channelconfig] LogSanityChecks -> DEBU 50d As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:31.336 UTC [common/channelconfig] LogSanityChecks -> DEBU 50e As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 50f Manager Channel looking up path [Orderer]
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 510 Manager Channel has managers Orderer
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 511 Manager Channel has managers Application
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 512 Manager Channel/Orderer looking up path []
2018-07-03 02:16:31.336 UTC [policies] Manager -> DEBU 513 Manager Channel/Orderer has managers OrdererOrg
2018-07-03 02:16:31.336 UTC [common/channelconfig] LogSanityChecks -> DEBU 514 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:31.336 UTC [common/capabilities] Supported -> DEBU 515 Orderer capability V1_1 is supported and is enabled
2018-07-03 02:16:31.336 UTC [common/capabilities] Supported -> DEBU 516 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:31.336 UTC [msp] GetLocalMSP -> DEBU 517 Returning existing local MSP
2018-07-03 02:16:31.336 UTC [msp] GetDefaultSigningIdentity -> DEBU 518 Obtaining default signing identity
2018-07-03 02:16:31.336 UTC [msp] GetLocalMSP -> DEBU 519 Returning existing local MSP
2018-07-03 02:16:31.336 UTC [msp] GetDefaultSigningIdentity -> DEBU 51a Obtaining default signing identity
2018-07-03 02:16:31.336 UTC [msp/identity] Sign -> DEBU 51b Sign: plaintext: 0AC7060A1508011A0608FFB8EBD90522...39268BB1F6F29F86FEF444F69CC36917 
2018-07-03 02:16:31.336 UTC [msp/identity] Sign -> DEBU 51c Sign: digest: 132581D5C983BF29BCFBC4E416C2F374C4D0C651EB1AEE973AB5FF20A9A84692 
2018-07-03 02:16:31.336 UTC [policies] Evaluate -> DEBU 51d == Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers ==
2018-07-03 02:16:31.336 UTC [policies] Evaluate -> DEBU 51e This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.336 UTC [policies] Evaluate -> DEBU 51f == Evaluating *policies.implicitMetaPolicy Policy /Channel/Orderer/Writers ==
2018-07-03 02:16:31.336 UTC [policies] Evaluate -> DEBU 520 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.336 UTC [policies] Evaluate -> DEBU 521 == Evaluating *cauthdsl.policy Policy /Channel/Orderer/OrdererOrg/Writers ==
2018-07-03 02:16:31.337 UTC [msp] DeserializeIdentity -> INFO 522 Obtaining identity
2018-07-03 02:16:31.337 UTC [msp/identity] newIdentity -> DEBU 523 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt
cGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV
BAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp
c2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI
KoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8
nPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA
MAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h
YqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B
bxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD
-----END CERTIFICATE-----
2018-07-03 02:16:31.337 UTC [cauthdsl] func1 -> DEBU 524 0xc42000efa8 gate 1530584191337276599 evaluation starts
2018-07-03 02:16:31.337 UTC [cauthdsl] func2 -> DEBU 525 0xc42000efa8 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.337 UTC [cauthdsl] func2 -> DEBU 526 0xc42000efa8 processing identity 0 with bytes of 0a0a4f7264657265724d53501281062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434444434341624f674177494241674952414a667833556b764a4f56754277334e423851756c337377436759494b6f5a497a6a3045417749776154454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784644415342674e5642416f54433256345957317762475575593239744d52637746515944565151444577356a5953356c654746740a6347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c614d466778437a414a42674e560a42415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d52597746415944565151484577315459573467526e4a68626d4e700a63324e764d527777476759445651514445784e76636d526c636d56794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159490a4b6f5a497a6a304441516344516741452f35784c5a39324a575469534d3469326767464175596268753675387249616766747755744d76336a5051737a6f7a380a6e506a57735946655945487a783839395057664955794f49666e5642776f797a36616b2f59364e4e4d45737744675944565230504151482f42415144416765410a4d41774741315564457745422f7751434d4141774b7759445652306a42435177496f41673644517235564a7842714b7339346a45536d54426b624b794d2f37680a59714a30624d54434b614666356a4577436759494b6f5a497a6a30454177494452774177524149674c334d584a57556e5a394c5765314f644a565569557034420a62785337475448496a4957364c49754e64393043494644514447737345574c666a336b4252424a716f756f6c3132312b6b74526535725539466379554b3361440a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.337 UTC [msp] SatisfiesPrincipal -> DEBU 527 Checking if identity satisfies MEMBER role for OrdererMSP
2018-07-03 02:16:31.337 UTC [msp] Validate -> DEBU 528 MSP OrdererMSP validating identity
2018-07-03 02:16:31.337 UTC [cauthdsl] func2 -> DEBU 529 0xc42000efa8 principal matched by identity 0
2018-07-03 02:16:31.337 UTC [msp/identity] Verify -> DEBU 52a Verify: digest = 00000000  13 25 81 d5 c9 83 bf 29  bc fb c4 e4 16 c2 f3 74  |.%.....).......t|
00000010  c4 d0 c6 51 eb 1a ee 97  3a b5 ff 20 a9 a8 46 92  |...Q....:.. ..F.|
2018-07-03 02:16:31.337 UTC [msp/identity] Verify -> DEBU 52b Verify: sig = 00000000  30 45 02 21 00 e9 4c d6  f9 73 05 78 3e 83 5c 0d  |0E.!..L..s.x>.\.|
00000010  d7 4e f3 58 a3 4b a8 b8  86 4d 3b 30 60 61 c4 2d  |.N.X.K...M;0`a.-|
00000020  cd f6 66 63 26 02 20 56  13 fd 02 d8 90 30 fc 34  |..fc&. V.....0.4|
00000030  de 44 67 a0 4f bd 80 93  a1 d1 ad 69 bc b5 02 61  |.Dg.O......i...a|
00000040  74 f2 d6 d3 6c fa da                              |t...l..|
2018-07-03 02:16:31.337 UTC [cauthdsl] func2 -> DEBU 52c 0xc42000efa8 principal evaluation succeeds for identity 0
2018-07-03 02:16:31.337 UTC [cauthdsl] func1 -> DEBU 52d 0xc42000efa8 gate 1530584191337276599 evaluation succeeds
2018-07-03 02:16:31.337 UTC [policies] Evaluate -> DEBU 52e Signature set satisfies policy /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.337 UTC [policies] Evaluate -> DEBU 52f == Done Evaluating *cauthdsl.policy Policy /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.337 UTC [policies] Evaluate -> DEBU 530 Signature set satisfies policy /Channel/Orderer/Writers
2018-07-03 02:16:31.337 UTC [policies] Evaluate -> DEBU 531 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Orderer/Writers
2018-07-03 02:16:31.337 UTC [policies] Evaluate -> DEBU 532 Signature set satisfies policy /Channel/Writers
2018-07-03 02:16:31.337 UTC [policies] Evaluate -> DEBU 533 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers
2018-07-03 02:16:31.337 UTC [orderer/common/broadcast] Handle -> DEBU 534 [channel: mychannel] Broadcast has successfully enqueued message of type CONFIG_UPDATE from 172.18.0.7:42714
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 535 Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 536 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 537 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 538 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 539 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 53a Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 53b Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 53c Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 53d Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 53e Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 53f Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 540 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 541 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 542 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.338 UTC [common/configtx] addToMap -> DEBU 543 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.338 UTC [common/configtx] verifyDeltaSet -> DEBU 544 Processing change to key: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.338 UTC [common/configtx] verifyDeltaSet -> DEBU 545 Processing change to key: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.338 UTC [common/configtx] policyForItem -> DEBU 546 Getting policy for item Org1MSP with mod_policy Admins
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 547 Manager Channel looking up path [Application]
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 548 Manager Channel has managers Orderer
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 549 Manager Channel has managers Application
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 54a Manager Channel/Application looking up path []
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 54b Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 54c Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 54d Manager Channel/Application looking up path [Org1MSP]
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 54e Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 54f Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:31.338 UTC [policies] Manager -> DEBU 550 Manager Channel/Application/Org1MSP looking up path []
2018-07-03 02:16:31.338 UTC [policies] Evaluate -> DEBU 551 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Admins ==
2018-07-03 02:16:31.338 UTC [cauthdsl] func1 -> DEBU 552 0xc420c0e738 gate 1530584191338991346 evaluation starts
2018-07-03 02:16:31.338 UTC [cauthdsl] func2 -> DEBU 553 0xc420c0e738 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.339 UTC [cauthdsl] func2 -> DEBU 554 0xc420c0e738 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b54434341644367417749424167495162394f7458584a6e586b4d7a58544c5271556a323754414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d53356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d53356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d477778437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513877445159445651514c45775a6a62476c6c626e5178487a416442674e5642414d4d466b466b62576c75514739790a5a7a45755a586868625842735a53356a623230775754415442676371686b6a4f5051494242676771686b6a4f50514d4242774e4341415164527130364f3679660a4b747348425a57495577533839435967525278673533764e797266654767757264343536584939396e4f614a4756797252654c534966632b45752b67756b30700a634f6a7463336c6335675a726f303077537a414f42674e56485138424166384542414d434234417744415944565230544151482f424149774144417242674e560a48534d454a4441696743425a422f514b4b5841556335375747425a586432506a4d5865672b2b566f33697057666244724931632f457a414b42676771686b6a4f0a5051514441674e48414442454169416d7556374f31556b415574587342534973396e796f355466416f7973777765614a514467734833326b7841496756484e320a534e4c335238314e4a73727a2f754d614239724b64484b656351366e4545396e597163327a474d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.339 UTC [msp] SatisfiesPrincipal -> DEBU 555 Checking if identity satisfies ADMIN role for Org1MSP
2018-07-03 02:16:31.339 UTC [cauthdsl] func2 -> DEBU 556 0xc420c0e738 principal matched by identity 0
2018-07-03 02:16:31.339 UTC [msp/identity] Verify -> DEBU 557 Verify: digest = 00000000  5a d8 07 b8 ed 36 3a 61  4b ec a7 fd 75 0d 7d 3f  |Z....6:aK...u.}?|
00000010  7d b5 7a 2e 2e c7 1e dc  c7 86 72 4e 63 9a 7e 74  |}.z.......rNc.~t|
2018-07-03 02:16:31.339 UTC [msp/identity] Verify -> DEBU 558 Verify: sig = 00000000  30 45 02 21 00 a6 ba f1  33 82 df 04 09 82 2a bc  |0E.!....3.....*.|
00000010  06 16 f1 73 f4 5f f4 61  e6 1f 0c f5 45 ad d2 c2  |...s._.a....E...|
00000020  12 e1 11 e3 21 02 20 6c  d9 fa 59 8c c7 e1 9f d2  |....!. l..Y.....|
00000030  15 14 99 af d9 96 eb 63  a2 1b fc e6 57 03 d7 58  |.......c....W..X|
00000040  89 98 dd 9b 9f 7e 20                              |.....~ |
2018-07-03 02:16:31.339 UTC [cauthdsl] func2 -> DEBU 559 0xc420c0e738 principal evaluation succeeds for identity 0
2018-07-03 02:16:31.339 UTC [cauthdsl] func1 -> DEBU 55a 0xc420c0e738 gate 1530584191338991346 evaluation succeeds
2018-07-03 02:16:31.339 UTC [policies] Evaluate -> DEBU 55b Signature set satisfies policy /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.339 UTC [policies] Evaluate -> DEBU 55c == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 55d Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 55e Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 55f Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 560 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 561 Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 562 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.339 UTC [common/configtx] recurseConfigMap -> DEBU 563 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.341 UTC [common/configtx] recurseConfigMap -> DEBU 564 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.341 UTC [common/configtx] recurseConfigMap -> DEBU 565 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org2MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:31.341 UTC [common/configtx] recurseConfigMap -> DEBU 566 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org2MSP" > mod_policy:"Admins" 
2018-07-03 02:16:31.341 UTC [common/configtx] recurseConfigMap -> DEBU 567 Setting policy for key Admins to 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 568 Setting policy for key Readers to 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 569 Setting policy for key Writers to 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 56a Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 56b Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 56c Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 56d Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 56e Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:31.342 UTC [common/configtx] recurseConfigMap -> DEBU 56f Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:31.342 UTC [common/channelconfig] NewStandardValues -> DEBU 570 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 571 Processing field: HashingAlgorithm
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 572 Processing field: BlockDataHashingStructure
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 573 Processing field: OrdererAddresses
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 574 Processing field: Consortium
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 575 Processing field: Capabilities
2018-07-03 02:16:31.342 UTC [common/channelconfig] NewStandardValues -> DEBU 576 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 577 Processing field: Capabilities
2018-07-03 02:16:31.342 UTC [common/channelconfig] NewStandardValues -> DEBU 578 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 579 Processing field: AnchorPeers
2018-07-03 02:16:31.342 UTC [common/channelconfig] NewStandardValues -> DEBU 57a Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.342 UTC [common/channelconfig] initializeProtosStruct -> DEBU 57b Processing field: MSP
2018-07-03 02:16:31.342 UTC [common/channelconfig] Validate -> DEBU 57c Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:31.342 UTC [common/channelconfig] validateMSP -> DEBU 57d Setting up MSP for org Org1MSP
2018-07-03 02:16:31.343 UTC [msp] newBccspMsp -> DEBU 57e Creating BCCSP-based MSP instance
2018-07-03 02:16:31.343 UTC [msp] New -> DEBU 57f Creating Cache-MSP instance
2018-07-03 02:16:31.343 UTC [msp] Setup -> DEBU 580 Setting up MSP instance Org1MSP
2018-07-03 02:16:31.344 UTC [msp/identity] newIdentity -> DEBU 581 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
QjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k
kp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj
4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1
EAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo
JaPsTQzNKw==
-----END CERTIFICATE-----
2018-07-03 02:16:31.344 UTC [msp/identity] newIdentity -> DEBU 582 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y
ZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf
KtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p
cOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV
HSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO
PQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2
SNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=
-----END CERTIFICATE-----
2018-07-03 02:16:31.344 UTC [msp] SatisfiesPrincipal -> DEBU 583 Checking if identity satisfies role [CLIENT] for Org1MSP
2018-07-03 02:16:31.345 UTC [msp] Validate -> DEBU 584 MSP Org1MSP validating identity
2018-07-03 02:16:31.345 UTC [msp] getCertificationChain -> DEBU 585 MSP Org1MSP getting certification chain
2018-07-03 02:16:31.345 UTC [msp] hasOURole -> DEBU 586 MSP Org1MSP checking if the identity is a client
2018-07-03 02:16:31.345 UTC [msp] getCertificationChain -> DEBU 587 MSP Org1MSP getting certification chain
2018-07-03 02:16:31.345 UTC [common/channelconfig] NewStandardValues -> DEBU 588 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:31.345 UTC [common/channelconfig] initializeProtosStruct -> DEBU 589 Processing field: AnchorPeers
2018-07-03 02:16:31.345 UTC [common/channelconfig] NewStandardValues -> DEBU 58a Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.345 UTC [common/channelconfig] initializeProtosStruct -> DEBU 58b Processing field: MSP
2018-07-03 02:16:31.345 UTC [common/channelconfig] Validate -> DEBU 58c Anchor peers for org Org2MSP are 
2018-07-03 02:16:31.345 UTC [common/channelconfig] validateMSP -> DEBU 58d Setting up MSP for org Org2MSP
2018-07-03 02:16:31.345 UTC [msp] newBccspMsp -> DEBU 58e Creating BCCSP-based MSP instance
2018-07-03 02:16:31.345 UTC [msp] New -> DEBU 58f Creating Cache-MSP instance
2018-07-03 02:16:31.345 UTC [msp] Setup -> DEBU 590 Setting up MSP instance Org2MSP
2018-07-03 02:16:31.345 UTC [msp/identity] newIdentity -> DEBU 591 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn
b3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d
b+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl
TmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13
G4VS/ZlT
-----END CERTIFICATE-----
2018-07-03 02:16:31.345 UTC [msp/identity] newIdentity -> DEBU 592 Creating identity instance for cert -----BEGIN CERTIFICATE-----
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
2018-07-03 02:16:31.346 UTC [msp] SatisfiesPrincipal -> DEBU 593 Checking if identity satisfies role [CLIENT] for Org2MSP
2018-07-03 02:16:31.346 UTC [msp] Validate -> DEBU 595 MSP Org2MSP validating identity
2018-07-03 02:16:31.346 UTC [msp] getCertificationChain -> DEBU 596 MSP Org2MSP getting certification chain
2018-07-03 02:16:31.346 UTC [orderer/common/broadcast] Handle -> DEBU 594 Received EOF from 172.18.0.7:42714, hangup
2018-07-03 02:16:31.347 UTC [orderer/common/server] func1 -> DEBU 597 Closing Broadcast stream
2018-07-03 02:16:31.347 UTC [msp] hasOURole -> DEBU 598 MSP Org2MSP checking if the identity is a client
2018-07-03 02:16:31.347 UTC [msp] getCertificationChain -> DEBU 599 MSP Org2MSP getting certification chain
2018-07-03 02:16:31.347 UTC [common/channelconfig] NewStandardValues -> DEBU 59a Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 59b Processing field: ConsensusType
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 59c Processing field: BatchSize
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 59d Processing field: BatchTimeout
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 59e Processing field: KafkaBrokers
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 59f Processing field: ChannelRestrictions
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 5a0 Processing field: Capabilities
2018-07-03 02:16:31.347 UTC [common/channelconfig] NewStandardValues -> DEBU 5a1 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:31.347 UTC [common/channelconfig] initializeProtosStruct -> DEBU 5a2 Processing field: MSP
2018-07-03 02:16:31.347 UTC [common/channelconfig] validateMSP -> DEBU 5a3 Setting up MSP for org OrdererOrg
2018-07-03 02:16:31.347 UTC [msp] newBccspMsp -> DEBU 5a4 Creating BCCSP-based MSP instance
2018-07-03 02:16:31.347 UTC [msp] New -> DEBU 5a5 Creating Cache-MSP instance
2018-07-03 02:16:31.347 UTC [msp] Setup -> DEBU 5a6 Setting up MSP instance OrdererMSP
2018-07-03 02:16:31.347 UTC [msp/identity] newIdentity -> DEBU 5a7 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w
bGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE
BhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz
Y28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv
bTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn
Hpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd
MA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB
Af8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG
CCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj
ZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=
-----END CERTIFICATE-----
2018-07-03 02:16:31.347 UTC [msp/identity] newIdentity -> DEBU 5a8 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt
cGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV
BAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp
c2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG
SM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh
cUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM
BgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi
dGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX
/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=
-----END CERTIFICATE-----
2018-07-03 02:16:31.347 UTC [msp] Validate -> DEBU 5a9 MSP OrdererMSP validating identity
2018-07-03 02:16:31.348 UTC [msp] Setup -> DEBU 5aa Setting up the MSP manager (3 msps)
2018-07-03 02:16:31.348 UTC [msp] Setup -> DEBU 5ab MSP manager setup complete, setup 3 msps
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5ac Proposed new policy Writers for Channel/Application/Org2MSP
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5ad Proposed new policy Admins for Channel/Application/Org2MSP
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5ae Proposed new policy Readers for Channel/Application/Org2MSP
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5af Proposed new policy Readers for Channel/Application/Org1MSP
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b0 Proposed new policy Writers for Channel/Application/Org1MSP
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b1 Proposed new policy Admins for Channel/Application/Org1MSP
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b2 Proposed new policy Writers for Channel/Application
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b3 Proposed new policy Admins for Channel/Application
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b4 Proposed new policy Readers for Channel/Application
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b5 Proposed new policy Readers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b6 Proposed new policy Writers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b7 Proposed new policy Admins for Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b8 Proposed new policy Writers for Channel/Orderer
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5b9 Proposed new policy BlockValidation for Channel/Orderer
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5ba Proposed new policy Admins for Channel/Orderer
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5bb Proposed new policy Readers for Channel/Orderer
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5bc Proposed new policy Readers for Channel
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5bd Proposed new policy Writers for Channel
2018-07-03 02:16:31.348 UTC [policies] NewManagerImpl -> DEBU 5be Proposed new policy Admins for Channel
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5bf Adding to config map: [Group]  /Channel
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c0 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c1 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c2 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c3 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c4 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c5 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c6 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c7 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c8 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5c9 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5ca Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5cb Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5cc Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5cd Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5ce Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:31.348 UTC [common/configtx] addToMap -> DEBU 5cf Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d0 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d1 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d2 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d3 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d4 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d5 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d6 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d7 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d8 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5d9 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5da Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5db Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5dc Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5dd Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5de Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5df Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e0 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e1 Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e2 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e3 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e4 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e5 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:31.349 UTC [common/configtx] addToMap -> DEBU 5e6 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:31.349 UTC [common/channelconfig] LogSanityChecks -> DEBU 5e7 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:31.349 UTC [common/channelconfig] LogSanityChecks -> DEBU 5e8 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5e9 Manager Channel looking up path [Application]
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5ea Manager Channel has managers Application
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5eb Manager Channel has managers Orderer
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5ec Manager Channel/Application looking up path []
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5ed Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5ee Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:31.349 UTC [common/channelconfig] LogSanityChecks -> DEBU 5ef As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:31.349 UTC [common/channelconfig] LogSanityChecks -> DEBU 5f0 As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:31.349 UTC [common/channelconfig] LogSanityChecks -> DEBU 5f1 As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5f2 Manager Channel looking up path [Orderer]
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5f3 Manager Channel has managers Application
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5f4 Manager Channel has managers Orderer
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5f5 Manager Channel/Orderer looking up path []
2018-07-03 02:16:31.349 UTC [policies] Manager -> DEBU 5f6 Manager Channel/Orderer has managers OrdererOrg
2018-07-03 02:16:31.349 UTC [common/channelconfig] LogSanityChecks -> DEBU 5f7 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:31.349 UTC [common/capabilities] Supported -> DEBU 5f8 Orderer capability V1_1 is supported and is enabled
2018-07-03 02:16:31.349 UTC [common/capabilities] Supported -> DEBU 5f9 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:31.349 UTC [msp] GetLocalMSP -> DEBU 5fa Returning existing local MSP
2018-07-03 02:16:31.349 UTC [msp] GetDefaultSigningIdentity -> DEBU 5fb Obtaining default signing identity
2018-07-03 02:16:31.349 UTC [msp] GetLocalMSP -> DEBU 5fc Returning existing local MSP
2018-07-03 02:16:31.349 UTC [msp] GetDefaultSigningIdentity -> DEBU 5fd Obtaining default signing identity
2018-07-03 02:16:31.349 UTC [msp/identity] Sign -> DEBU 5fe Sign: plaintext: 0A90060A0A4F7264657265724D535012...E564ECB5EDB7443DF9EE4751F2A48EA2 
2018-07-03 02:16:31.349 UTC [msp/identity] Sign -> DEBU 5ff Sign: digest: D836A1535544A59AD60940590ADBFE84EED61C385209ADB9E2E0ECBE72A703AF 
2018-07-03 02:16:31.349 UTC [orderer/commmon/multichannel] addLastConfigSignature -> DEBU 600 [channel: mychannel] Detected lastConfigSeq transitioning from 1 to 2, setting lastConfigBlockNum from 0 to 1
2018-07-03 02:16:31.349 UTC [msp] GetLocalMSP -> DEBU 601 Returning existing local MSP
2018-07-03 02:16:31.349 UTC [msp] GetDefaultSigningIdentity -> DEBU 602 Obtaining default signing identity
2018-07-03 02:16:31.349 UTC [orderer/commmon/multichannel] addLastConfigSignature -> DEBU 603 [channel: mychannel] About to write block, setting its LAST_CONFIG to 1
2018-07-03 02:16:31.349 UTC [msp] GetLocalMSP -> DEBU 604 Returning existing local MSP
2018-07-03 02:16:31.349 UTC [msp] GetDefaultSigningIdentity -> DEBU 605 Obtaining default signing identity
2018-07-03 02:16:31.349 UTC [msp/identity] Sign -> DEBU 606 Sign: plaintext: 08010A90060A0A4F7264657265724D53...E564ECB5EDB7443DF9EE4751F2A48EA2 
2018-07-03 02:16:31.349 UTC [msp/identity] Sign -> DEBU 607 Sign: digest: 4EC0883F1F88A4CFFC070B488F239FA7DDA46949FE28CD4F357E3C9DD43FA005 
2018-07-03 02:16:31.350 UTC [common/deliver] Handle -> WARN 608 Error reading from 172.18.0.7:42712: rpc error: code = Canceled desc = context canceled
2018-07-03 02:16:31.350 UTC [orderer/common/server] func1 -> DEBU 609 Closing Deliver stream
2018-07-03 02:16:31.350 UTC [grpc] Printf -> DEBU 60a transport: http2Server.HandleStreams failed to read frame: read tcp 172.18.0.4:7050->172.18.0.7:42714: read: connection reset by peer
2018-07-03 02:16:31.355 UTC [fsblkstorage] indexBlock -> DEBU 60b Indexing block [blockNum=1, blockHash=[]byte{0xba, 0xb0, 0xc4, 0xd9, 0x17, 0xd9, 0x32, 0xdd, 0x7c, 0x12, 0x95, 0x81, 0x1c, 0xb4, 0x7e, 0xbe, 0xe1, 0x3e, 0xaf, 0x98, 0x43, 0x2, 0x9b, 0x37, 0xe6, 0xfd, 0x26, 0xd2, 0x95, 0x9d, 0x3e, 0xd7} txOffsets=
txId= locPointer=offset=71, bytesLength=15610
]
2018-07-03 02:16:31.357 UTC [fsblkstorage] updateCheckpoint -> DEBU 60c Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[33125], isChainEmpty=[false], lastBlockNumber=[1]
2018-07-03 02:16:31.357 UTC [orderer/commmon/multichannel] commitBlock -> DEBU 60d [channel: mychannel] Wrote block 1
2018-07-03 02:16:31.357 UTC [fsblkstorage] waitForBlock -> DEBU 60e Came out of wait. maxAvailaBlockNumber=[1]
2018-07-03 02:16:31.357 UTC [fsblkstorage] Next -> DEBU 60f Initializing block stream for iterator. itr.maxBlockNumAvailable=1
2018-07-03 02:16:31.357 UTC [fsblkstorage] newBlockfileStream -> DEBU 610 newBlockfileStream(): filePath=[/var/hyperledger/production/orderer/chains/mychannel/blockfile_000000], startOffset=[15649]
2018-07-03 02:16:31.357 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 611 Remaining bytes=[17476], Going to peek [8] bytes
2018-07-03 02:16:31.357 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 612 Returning blockbytes - length=[17473], placementInfo={fileNum=[0], startOffset=[15649], bytesOffset=[15652]}
2018-07-03 02:16:31.357 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 613 blockbytes [17473] read from file [0]
2018-07-03 02:16:31.357 UTC [policies] Evaluate -> DEBU 614 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers ==
2018-07-03 02:16:31.357 UTC [policies] Evaluate -> DEBU 615 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.357 UTC [policies] Evaluate -> DEBU 616 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers ==
2018-07-03 02:16:31.357 UTC [policies] Evaluate -> DEBU 617 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.357 UTC [policies] Evaluate -> DEBU 618 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers ==
2018-07-03 02:16:31.357 UTC [msp] DeserializeIdentity -> INFO 619 Obtaining identity
2018-07-03 02:16:31.357 UTC [msp/identity] newIdentity -> DEBU 61a Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICJzCCAc6gAwIBAgIQYJ1nWgjjFK2QEuiX09MP/jAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MGoxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMQ0wCwYDVQQLEwRwZWVyMR8wHQYDVQQDExZwZWVyMC5vcmcy
LmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEt4lTLAuzDRm0
4g/cHsw1603B8pUvX35Aciske9dRJBXlFUS2NDBd4mvtqlvBRQVTKAFu4L8P9C+P
JSbSlO9haaNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYDVR0j
BCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0E
AwIDRwAwRAIgWn6JQhLZCLMX46tZWRG3tzTwh2smyTL4PTwUznqI63ACID3drmjG
DqkCmDra/7bjgFvX4x6xWmVfuS7DnSqrrJdW
-----END CERTIFICATE-----
2018-07-03 02:16:31.358 UTC [cauthdsl] func1 -> DEBU 61b 0xc420c0e690 gate 1530584191358095449 evaluation starts
2018-07-03 02:16:31.358 UTC [cauthdsl] func2 -> DEBU 61c 0xc420c0e690 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.358 UTC [cauthdsl] func2 -> DEBU 61d 0xc420c0e690 processing identity 0 with bytes of 0a074f7267324d535012a6062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434a7a4343416336674177494241674951594a316e57676a6a464b32514575695830394d502f6a414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d69356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d69356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d476f78437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513077437759445651514c457752775a5756794d523877485159445651514445785a775a5756794d433576636d63790a4c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a3044415163445167414574346c544c41757a44526d300a34672f63487377313630334238705576583335416369736b653964524a42586c465553324e444264346d7674716c7642525156544b414675344c385039432b500a4a5362536c4f396861614e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759445652306a0a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a497a6a30450a417749445277417752414967576e364a51684c5a434c4d583436745a57524733747a54776832736d79544c34505477557a6e71493633414349443364726d6a470a44716b436d4472612f37626a6746765834783678576d5666755337446e537172724a64570a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.358 UTC [msp] SatisfiesPrincipal -> DEBU 61e Checking if identity satisfies MEMBER role for Org2MSP
2018-07-03 02:16:31.358 UTC [msp] Validate -> DEBU 61f MSP Org2MSP validating identity
2018-07-03 02:16:31.358 UTC [msp] getCertificationChain -> DEBU 620 MSP Org2MSP getting certification chain
2018-07-03 02:16:31.358 UTC [cauthdsl] func2 -> DEBU 621 0xc420c0e690 principal matched by identity 0
2018-07-03 02:16:31.358 UTC [msp/identity] Verify -> DEBU 622 Verify: digest = 00000000  66 61 32 f5 ba 5a b5 09  52 1d 96 75 aa e7 c9 58  |fa2..Z..R..u...X|
00000010  86 50 5b 37 8f a9 09 46  b0 8f 25 a6 95 b5 1b 51  |.P[7...F..%....Q|
2018-07-03 02:16:31.358 UTC [msp/identity] Verify -> DEBU 623 Verify: sig = 00000000  30 44 02 20 7c 2a ff 3d  ee 03 db 71 c4 19 63 c7  |0D. |*.=...q..c.|
00000010  9f 8a ae 35 5f 92 be 6f  63 e0 50 dc e1 63 ff d2  |...5_..oc.P..c..|
00000020  8a 18 ca 9d 02 20 72 af  fb 12 82 41 be c0 51 3b  |..... r....A..Q;|
00000030  0d 7b 9f dc 09 ca 88 25  05 34 71 dc 1f 20 cd 51  |.{.....%.4q.. .Q|
00000040  bc 33 58 04 97 aa                                 |.3X...|
2018-07-03 02:16:31.358 UTC [cauthdsl] func2 -> DEBU 624 0xc420c0e690 principal evaluation succeeds for identity 0
2018-07-03 02:16:31.358 UTC [cauthdsl] func1 -> DEBU 625 0xc420c0e690 gate 1530584191358095449 evaluation succeeds
2018-07-03 02:16:31.358 UTC [policies] Evaluate -> DEBU 626 Signature set satisfies policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.358 UTC [policies] Evaluate -> DEBU 627 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.358 UTC [policies] Evaluate -> DEBU 628 Signature set satisfies policy /Channel/Application/Readers
2018-07-03 02:16:31.358 UTC [policies] Evaluate -> DEBU 629 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers
2018-07-03 02:16:31.358 UTC [policies] Evaluate -> DEBU 62a Signature set satisfies policy /Channel/Readers
2018-07-03 02:16:31.358 UTC [policies] Evaluate -> DEBU 62b == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers
2018-07-03 02:16:31.358 UTC [common/deliver] deliverBlocks -> DEBU 62c [channel: mychannel] Delivering block for (0xc420a96660) for 172.18.0.2:55226
2018-07-03 02:16:31.361 UTC [fsblkstorage] waitForBlock -> DEBU 62d Came out of wait. maxAvailaBlockNumber=[1]
2018-07-03 02:16:31.361 UTC [fsblkstorage] Next -> DEBU 62e Initializing block stream for iterator. itr.maxBlockNumAvailable=1
2018-07-03 02:16:31.361 UTC [fsblkstorage] newBlockfileStream -> DEBU 62f newBlockfileStream(): filePath=[/var/hyperledger/production/orderer/chains/mychannel/blockfile_000000], startOffset=[15649]
2018-07-03 02:16:31.361 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 630 Remaining bytes=[17476], Going to peek [8] bytes
2018-07-03 02:16:31.361 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 631 Returning blockbytes - length=[17473], placementInfo={fileNum=[0], startOffset=[15649], bytesOffset=[15652]}
2018-07-03 02:16:31.361 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 632 blockbytes [17473] read from file [0]
2018-07-03 02:16:31.361 UTC [policies] Evaluate -> DEBU 633 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers ==
2018-07-03 02:16:31.361 UTC [policies] Evaluate -> DEBU 634 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.361 UTC [policies] Evaluate -> DEBU 635 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers ==
2018-07-03 02:16:31.361 UTC [policies] Evaluate -> DEBU 636 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:31.362 UTC [policies] Evaluate -> DEBU 637 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers ==
2018-07-03 02:16:31.362 UTC [msp] DeserializeIdentity -> INFO 638 Obtaining identity
2018-07-03 02:16:31.362 UTC [msp/identity] newIdentity -> DEBU 639 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKDCCAc+gAwIBAgIRAJtiEX85zYg6nslTt+qSSbgwCgYIKoZIzj0EAwIwczEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh
Lm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5
WjBqMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN
U2FuIEZyYW5jaXNjbzENMAsGA1UECxMEcGVlcjEfMB0GA1UEAxMWcGVlcjAub3Jn
MS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABGgf4MnrbbDo
iVuZtmSyeLTZoI8AkYnDFT62fmL7SkSbpFvS6NgVVzzIqjvk7neds7lb7GQkZg7Y
YAPe9UxKxtijTTBLMA4GA1UdDwEB/wQEAwIHgDAMBgNVHRMBAf8EAjAAMCsGA1Ud
IwQkMCKAIFkH9AopcBRzntYYFld3Y+Mxd6D75WjeKlZ9sOsjVz8TMAoGCCqGSM49
BAMCA0cAMEQCIDdYm3WxVcK61cl3u0Wt5M/twcmqoSIJ6IeoDEBJHkMtAiBkucyT
80H7y+3ojQYsd6Wi8fUvh6+h9NkFKSoWsgMDRw==
-----END CERTIFICATE-----
2018-07-03 02:16:31.363 UTC [cauthdsl] func1 -> DEBU 63a 0xc420ac4018 gate 1530584191363106387 evaluation starts
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 63b 0xc420ac4018 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 63c 0xc420ac4018 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b44434341632b674177494241674952414a7469455838357a5967366e736c54742b715353626777436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a45755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a45755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42714d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a454e4d4173474131554543784d456347566c636a45664d4230474131554541784d576347566c636a417562334a6e0a4d53356c654746746347786c4c6d4e766254425a4d424d4742797147534d34394167454743437147534d3439417745484130494142476766344d6e726262446f0a6956755a746d5379654c545a6f4938416b596e4446543632666d4c37536b536270467653364e6756567a7a49716a766b376e656473376c623747516b5a6737590a594150653955784b7874696a5454424c4d41344741315564447745422f775145417749486744414d42674e5648524d4241663845416a41414d437347413155640a4977516b4d434b4149466b4839416f706342527a6e745959466c6433592b4d786436443735576a654b6c5a39734f736a567a38544d416f4743437147534d34390a42414d43413063414d455143494464596d33577856634b3631636c3375305774354d2f7477636d716f53494a3649656f4445424a486b4d744169426b756379540a38304837792b336f6a515973643657693866557668362b68394e6b464b536f5773674d4452773d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 63d 0xc420ac4018 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected Org2MSP, got Org1MSP)
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 63e 0xc420ac4018 principal evaluation fails
2018-07-03 02:16:31.363 UTC [cauthdsl] func1 -> DEBU 63f 0xc420ac4018 gate 1530584191363106387 evaluation fails
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 640 Signature set did not satisfy policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 641 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 642 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Readers ==
2018-07-03 02:16:31.363 UTC [cauthdsl] func1 -> DEBU 643 0xc420ac4028 gate 1530584191363215205 evaluation starts
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 644 0xc420ac4028 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 645 0xc420ac4028 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b44434341632b674177494241674952414a7469455838357a5967366e736c54742b715353626777436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a45755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a45755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42714d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a454e4d4173474131554543784d456347566c636a45664d4230474131554541784d576347566c636a417562334a6e0a4d53356c654746746347786c4c6d4e766254425a4d424d4742797147534d34394167454743437147534d3439417745484130494142476766344d6e726262446f0a6956755a746d5379654c545a6f4938416b596e4446543632666d4c37536b536270467653364e6756567a7a49716a766b376e656473376c623747516b5a6737590a594150653955784b7874696a5454424c4d41344741315564447745422f775145417749486744414d42674e5648524d4241663845416a41414d437347413155640a4977516b4d434b4149466b4839416f706342527a6e745959466c6433592b4d786436443735576a654b6c5a39734f736a567a38544d416f4743437147534d34390a42414d43413063414d455143494464596d33577856634b3631636c3375305774354d2f7477636d716f53494a3649656f4445424a486b4d744169426b756379540a38304837792b336f6a515973643657693866557668362b68394e6b464b536f5773674d4452773d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:31.363 UTC [msp] SatisfiesPrincipal -> DEBU 646 Checking if identity satisfies MEMBER role for Org1MSP
2018-07-03 02:16:31.363 UTC [msp] Validate -> DEBU 647 MSP Org1MSP validating identity
2018-07-03 02:16:31.363 UTC [msp] getCertificationChain -> DEBU 648 MSP Org1MSP getting certification chain
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 649 0xc420ac4028 principal matched by identity 0
2018-07-03 02:16:31.363 UTC [msp/identity] Verify -> DEBU 64a Verify: digest = 00000000  50 db 9a 16 fa d5 f2 40  0e 28 23 28 eb 6d 12 be  |P......@.(#(.m..|
00000010  1e 88 9f 8c 1b 55 f7 a0  90 b3 d7 14 1e 4c 3f 0f  |.....U.......L?.|
2018-07-03 02:16:31.363 UTC [msp/identity] Verify -> DEBU 64b Verify: sig = 00000000  30 45 02 21 00 b7 20 ad  28 a2 ed 0e d6 fb 92 a9  |0E.!.. .(.......|
00000010  c5 45 05 5b d9 08 b6 33  5d 95 0f 6c e7 a7 6b 5a  |.E.[...3]..l..kZ|
00000020  35 0d f1 5e e9 02 20 7c  1c 0e 66 eb c4 88 f9 6b  |5..^.. |..f....k|
00000030  d5 28 02 2f 9d 19 79 09  f6 93 1f 7c aa b4 63 38  |.(./..y....|..c8|
00000040  16 3e bb 2d 8f 56 cb                              |.>.-.V.|
2018-07-03 02:16:31.363 UTC [cauthdsl] func2 -> DEBU 64c 0xc420ac4028 principal evaluation succeeds for identity 0
2018-07-03 02:16:31.363 UTC [cauthdsl] func1 -> DEBU 64d 0xc420ac4028 gate 1530584191363215205 evaluation succeeds
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 64e Signature set satisfies policy /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 64f == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 650 Signature set satisfies policy /Channel/Application/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 651 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 652 Signature set satisfies policy /Channel/Readers
2018-07-03 02:16:31.363 UTC [policies] Evaluate -> DEBU 653 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers
2018-07-03 02:16:31.363 UTC [common/deliver] deliverBlocks -> DEBU 654 [channel: mychannel] Delivering block for (0xc420c243c0) for 172.18.0.6:54766
2018-07-03 02:16:31.364 UTC [fsblkstorage] waitForBlock -> DEBU 655 Going to wait for newer blocks. maxAvailaBlockNumber=[1], waitForBlockNum=[2]
2018-07-03 02:16:31.370 UTC [fsblkstorage] waitForBlock -> DEBU 656 Going to wait for newer blocks. maxAvailaBlockNumber=[1], waitForBlockNum=[2]
2018-07-03 02:16:34.471 UTC [orderer/common/server] Deliver -> DEBU 657 Starting new Deliver handler
2018-07-03 02:16:34.471 UTC [common/deliver] Handle -> DEBU 658 Starting new deliver loop for 172.18.0.7:42728
2018-07-03 02:16:34.471 UTC [common/deliver] Handle -> DEBU 659 Attempting to read seek info message from 172.18.0.7:42728
2018-07-03 02:16:34.477 UTC [orderer/common/server] Broadcast -> DEBU 65a Starting new Broadcast handler
2018-07-03 02:16:34.477 UTC [orderer/common/broadcast] Handle -> DEBU 65b Starting new broadcast loop for 172.18.0.7:42730
2018-07-03 02:16:34.477 UTC [orderer/common/broadcast] Handle -> DEBU 65c [channel: mychannel] Broadcast is processing config update message from 172.18.0.7:42730
2018-07-03 02:16:34.477 UTC [orderer/common/msgprocessor] ProcessConfigUpdateMsg -> DEBU 65d Processing config update message for channel mychannel
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 65e == Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers ==
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 65f This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 660 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers ==
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 661 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 662 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers ==
2018-07-03 02:16:34.477 UTC [msp] DeserializeIdentity -> INFO 663 Obtaining identity
2018-07-03 02:16:34.477 UTC [msp/identity] newIdentity -> DEBU 664 Creating identity instance for cert -----BEGIN CERTIFICATE-----
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
2018-07-03 02:16:34.477 UTC [cauthdsl] func1 -> DEBU 665 0xc420ac4058 gate 1530584194477570837 evaluation starts
2018-07-03 02:16:34.477 UTC [cauthdsl] func2 -> DEBU 666 0xc420ac4058 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.477 UTC [cauthdsl] func2 -> DEBU 667 0xc420ac4058 processing identity 0 with bytes of 0a074f7267324d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b6a4343416447674177494241674952414d4c6c5861304f4c3949585a62544a3739557179664577436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a49755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a49755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42734d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a45504d4130474131554543784d47593278705a5735304d523877485159445651514444425a425a473170626b42760a636d63794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a304441516344516741454b685675674975530a7069483568466f78514e5354482b49413465622b4b47465a322b34383654723170744e38446a64584964434b5142334a43346159706a347a4a326f54546977720a2f2b796d3948374e31536b36504b4e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759440a5652306a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a490a7a6a304541774944527741775241496766334f4c6b64635a41776b747269366b4867494a6c326a4572644c67374c66454c645a683478583676714d4349484a410a5a7a6b654942347742304f35397046396f4330664f47757a6d47687a366d424146414b38516b2b430a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.477 UTC [msp] SatisfiesPrincipal -> DEBU 668 Checking if identity satisfies MEMBER role for Org2MSP
2018-07-03 02:16:34.477 UTC [msp] Validate -> DEBU 669 MSP Org2MSP validating identity
2018-07-03 02:16:34.477 UTC [msp] getCertificationChain -> DEBU 66a MSP Org2MSP getting certification chain
2018-07-03 02:16:34.477 UTC [cauthdsl] func2 -> DEBU 66b 0xc420ac4058 principal matched by identity 0
2018-07-03 02:16:34.477 UTC [msp/identity] Verify -> DEBU 66c Verify: digest = 00000000  5b a7 a8 f4 23 e7 92 f4  65 5c fa ee 48 45 ae 4c  |[...#...e\..HE.L|
00000010  fa f8 c2 07 33 a7 af d5  64 08 4d 16 50 8a 89 e7  |....3...d.M.P...|
2018-07-03 02:16:34.477 UTC [msp/identity] Verify -> DEBU 66d Verify: sig = 00000000  30 45 02 21 00 dd b4 09  a9 8e fc 1e 7b ce 8d 6c  |0E.!........{..l|
00000010  ee da 18 fb ed c7 42 0e  9a d3 46 50 10 c2 36 43  |......B...FP..6C|
00000020  98 86 f9 c5 4a 02 20 3a  90 0c ff 49 86 ef 5d 25  |....J. :...I..]%|
00000030  28 bc 03 e4 88 ee f5 73  42 26 21 39 22 69 ac db  |(......sB&!9"i..|
00000040  78 d3 7d fa 7a 7e c5                              |x.}.z~.|
2018-07-03 02:16:34.477 UTC [cauthdsl] func2 -> DEBU 66e 0xc420ac4058 principal evaluation succeeds for identity 0
2018-07-03 02:16:34.477 UTC [cauthdsl] func1 -> DEBU 66f 0xc420ac4058 gate 1530584194477570837 evaluation succeeds
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 670 Signature set satisfies policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 671 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.477 UTC [policies] Evaluate -> DEBU 672 Signature set satisfies policy /Channel/Application/Writers
2018-07-03 02:16:34.478 UTC [policies] Evaluate -> DEBU 673 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers
2018-07-03 02:16:34.478 UTC [policies] Evaluate -> DEBU 674 Signature set satisfies policy /Channel/Writers
2018-07-03 02:16:34.478 UTC [policies] Evaluate -> DEBU 675 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 676 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 677 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 678 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 679 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 67a Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 67b Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 67c Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 67d Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 67e Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 67f Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 680 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 681 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 682 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 683 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.478 UTC [common/configtx] addToMap -> DEBU 684 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.478 UTC [common/configtx] verifyDeltaSet -> DEBU 685 Processing change to key: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.478 UTC [common/configtx] policyForItem -> DEBU 686 Getting policy for item Org2MSP with mod_policy Admins
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 687 Manager Channel looking up path [Application]
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 688 Manager Channel has managers Application
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 689 Manager Channel has managers Orderer
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 68a Manager Channel/Application looking up path []
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 68b Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 68c Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 68d Manager Channel/Application looking up path [Org2MSP]
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 68e Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 68f Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:34.478 UTC [policies] Manager -> DEBU 690 Manager Channel/Application/Org2MSP looking up path []
2018-07-03 02:16:34.478 UTC [policies] Evaluate -> DEBU 691 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Admins ==
2018-07-03 02:16:34.478 UTC [cauthdsl] func1 -> DEBU 692 0xc420ac42b8 gate 1530584194478626706 evaluation starts
2018-07-03 02:16:34.478 UTC [cauthdsl] func2 -> DEBU 693 0xc420ac42b8 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.478 UTC [cauthdsl] func2 -> DEBU 694 0xc420ac42b8 processing identity 0 with bytes of 0a074f7267324d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b6a4343416447674177494241674952414d4c6c5861304f4c3949585a62544a3739557179664577436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a49755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a49755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42734d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a45504d4130474131554543784d47593278705a5735304d523877485159445651514444425a425a473170626b42760a636d63794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a304441516344516741454b685675674975530a7069483568466f78514e5354482b49413465622b4b47465a322b34383654723170744e38446a64584964434b5142334a43346159706a347a4a326f54546977720a2f2b796d3948374e31536b36504b4e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759440a5652306a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a490a7a6a304541774944527741775241496766334f4c6b64635a41776b747269366b4867494a6c326a4572644c67374c66454c645a683478583676714d4349484a410a5a7a6b654942347742304f35397046396f4330664f47757a6d47687a366d424146414b38516b2b430a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.478 UTC [msp] SatisfiesPrincipal -> DEBU 695 Checking if identity satisfies ADMIN role for Org2MSP
2018-07-03 02:16:34.478 UTC [cauthdsl] func2 -> DEBU 696 0xc420ac42b8 principal matched by identity 0
2018-07-03 02:16:34.478 UTC [msp/identity] Verify -> DEBU 697 Verify: digest = 00000000  48 90 f7 60 1d 05 d1 24  25 f2 3b cd 40 5e 35 82  |H..`...$%.;.@^5.|
00000010  b6 5c f2 64 bb d2 dd a8  e1 35 38 30 2c 2a 12 03  |.\.d.....580,*..|
2018-07-03 02:16:34.478 UTC [msp/identity] Verify -> DEBU 698 Verify: sig = 00000000  30 45 02 21 00 c6 a2 62  27 ae 84 0d 02 49 dc 00  |0E.!...b'....I..|
00000010  b7 da 64 71 81 66 c9 c1  e1 f9 46 9f d4 81 b8 48  |..dq.f....F....H|
00000020  78 2e 78 5b f1 02 20 0f  c5 34 fc 1e af 72 93 98  |x.x[.. ..4...r..|
00000030  da e3 ce 92 b6 92 33 fd  b6 ff fd 05 d8 f3 c3 59  |......3........Y|
00000040  f7 40 13 eb 48 a3 af                              |.@..H..|
2018-07-03 02:16:34.478 UTC [cauthdsl] func2 -> DEBU 699 0xc420ac42b8 principal evaluation succeeds for identity 0
2018-07-03 02:16:34.478 UTC [cauthdsl] func1 -> DEBU 69a 0xc420ac42b8 gate 1530584194478626706 evaluation succeeds
2018-07-03 02:16:34.478 UTC [policies] Evaluate -> DEBU 69b Signature set satisfies policy /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.478 UTC [policies] Evaluate -> DEBU 69c == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.478 UTC [common/configtx] verifyDeltaSet -> DEBU 69d Processing change to key: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.478 UTC [common/configtx] recurseConfigMap -> DEBU 69e Setting policy for key Readers to 
2018-07-03 02:16:34.478 UTC [common/configtx] recurseConfigMap -> DEBU 69f Setting policy for key Writers to 
2018-07-03 02:16:34.478 UTC [common/configtx] recurseConfigMap -> DEBU 6a0 Setting policy for key Admins to 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a1 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a2 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a3 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a4 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a5 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a6 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a7 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a8 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6a9 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6aa Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6ab Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6ac Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6ad Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6ae Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6af Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/configtx] recurseConfigMap -> DEBU 6b0 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.479 UTC [common/channelconfig] NewStandardValues -> DEBU 6b1 Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6b2 Processing field: HashingAlgorithm
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6b3 Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6b4 Processing field: OrdererAddresses
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6b5 Processing field: Consortium
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6b6 Processing field: Capabilities
2018-07-03 02:16:34.479 UTC [common/channelconfig] NewStandardValues -> DEBU 6b7 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6b8 Processing field: Capabilities
2018-07-03 02:16:34.479 UTC [common/channelconfig] NewStandardValues -> DEBU 6b9 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6ba Processing field: AnchorPeers
2018-07-03 02:16:34.479 UTC [common/channelconfig] NewStandardValues -> DEBU 6bb Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.479 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6bc Processing field: MSP
2018-07-03 02:16:34.479 UTC [common/channelconfig] Validate -> DEBU 6bd Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.479 UTC [common/channelconfig] validateMSP -> DEBU 6be Setting up MSP for org Org2MSP
2018-07-03 02:16:34.479 UTC [msp] newBccspMsp -> DEBU 6bf Creating BCCSP-based MSP instance
2018-07-03 02:16:34.479 UTC [msp] New -> DEBU 6c0 Creating Cache-MSP instance
2018-07-03 02:16:34.479 UTC [msp] Setup -> DEBU 6c1 Setting up MSP instance Org2MSP
2018-07-03 02:16:34.479 UTC [msp/identity] newIdentity -> DEBU 6c2 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn
b3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d
b+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl
TmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13
G4VS/ZlT
-----END CERTIFICATE-----
2018-07-03 02:16:34.479 UTC [msp/identity] newIdentity -> DEBU 6c3 Creating identity instance for cert -----BEGIN CERTIFICATE-----
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
2018-07-03 02:16:34.480 UTC [msp] SatisfiesPrincipal -> DEBU 6c4 Checking if identity satisfies role [CLIENT] for Org2MSP
2018-07-03 02:16:34.480 UTC [msp] Validate -> DEBU 6c5 MSP Org2MSP validating identity
2018-07-03 02:16:34.480 UTC [msp] getCertificationChain -> DEBU 6c6 MSP Org2MSP getting certification chain
2018-07-03 02:16:34.480 UTC [msp] hasOURole -> DEBU 6c7 MSP Org2MSP checking if the identity is a client
2018-07-03 02:16:34.480 UTC [msp] getCertificationChain -> DEBU 6c8 MSP Org2MSP getting certification chain
2018-07-03 02:16:34.480 UTC [common/channelconfig] NewStandardValues -> DEBU 6c9 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.480 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6ca Processing field: AnchorPeers
2018-07-03 02:16:34.480 UTC [common/channelconfig] NewStandardValues -> DEBU 6cb Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.480 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6cc Processing field: MSP
2018-07-03 02:16:34.480 UTC [common/channelconfig] Validate -> DEBU 6cd Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.480 UTC [common/channelconfig] validateMSP -> DEBU 6ce Setting up MSP for org Org1MSP
2018-07-03 02:16:34.480 UTC [msp] newBccspMsp -> DEBU 6cf Creating BCCSP-based MSP instance
2018-07-03 02:16:34.480 UTC [msp] New -> DEBU 6d0 Creating Cache-MSP instance
2018-07-03 02:16:34.480 UTC [msp] Setup -> DEBU 6d1 Setting up MSP instance Org1MSP
2018-07-03 02:16:34.480 UTC [msp/identity] newIdentity -> DEBU 6d2 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
QjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k
kp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj
4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1
EAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo
JaPsTQzNKw==
-----END CERTIFICATE-----
2018-07-03 02:16:34.480 UTC [msp/identity] newIdentity -> DEBU 6d3 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y
ZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf
KtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p
cOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV
HSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO
PQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2
SNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=
-----END CERTIFICATE-----
2018-07-03 02:16:34.481 UTC [msp] SatisfiesPrincipal -> DEBU 6d4 Checking if identity satisfies role [CLIENT] for Org1MSP
2018-07-03 02:16:34.481 UTC [msp] Validate -> DEBU 6d5 MSP Org1MSP validating identity
2018-07-03 02:16:34.481 UTC [msp] getCertificationChain -> DEBU 6d6 MSP Org1MSP getting certification chain
2018-07-03 02:16:34.481 UTC [msp] hasOURole -> DEBU 6d7 MSP Org1MSP checking if the identity is a client
2018-07-03 02:16:34.481 UTC [msp] getCertificationChain -> DEBU 6d8 MSP Org1MSP getting certification chain
2018-07-03 02:16:34.481 UTC [common/channelconfig] NewStandardValues -> DEBU 6d9 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6da Processing field: ConsensusType
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6db Processing field: BatchSize
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6dc Processing field: BatchTimeout
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6dd Processing field: KafkaBrokers
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6de Processing field: ChannelRestrictions
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6df Processing field: Capabilities
2018-07-03 02:16:34.481 UTC [common/channelconfig] NewStandardValues -> DEBU 6e0 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.481 UTC [common/channelconfig] initializeProtosStruct -> DEBU 6e1 Processing field: MSP
2018-07-03 02:16:34.481 UTC [common/channelconfig] validateMSP -> DEBU 6e2 Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.481 UTC [msp] newBccspMsp -> DEBU 6e3 Creating BCCSP-based MSP instance
2018-07-03 02:16:34.481 UTC [msp] New -> DEBU 6e4 Creating Cache-MSP instance
2018-07-03 02:16:34.481 UTC [msp] Setup -> DEBU 6e5 Setting up MSP instance OrdererMSP
2018-07-03 02:16:34.481 UTC [msp/identity] newIdentity -> DEBU 6e6 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w
bGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE
BhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz
Y28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv
bTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn
Hpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd
MA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB
Af8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG
CCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj
ZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=
-----END CERTIFICATE-----
2018-07-03 02:16:34.481 UTC [msp/identity] newIdentity -> DEBU 6e7 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt
cGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV
BAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp
c2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG
SM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh
cUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM
BgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi
dGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX
/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=
-----END CERTIFICATE-----
2018-07-03 02:16:34.481 UTC [msp] Validate -> DEBU 6e8 MSP OrdererMSP validating identity
2018-07-03 02:16:34.482 UTC [msp] Setup -> DEBU 6e9 Setting up the MSP manager (3 msps)
2018-07-03 02:16:34.482 UTC [msp] Setup -> DEBU 6ea MSP manager setup complete, setup 3 msps
2018-07-03 02:16:34.482 UTC [policies] NewManagerImpl -> DEBU 6eb Proposed new policy Readers for Channel/Application/Org2MSP
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6ec Proposed new policy Writers for Channel/Application/Org2MSP
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6ed Proposed new policy Admins for Channel/Application/Org2MSP
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6ee Proposed new policy Readers for Channel/Application/Org1MSP
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6ef Proposed new policy Writers for Channel/Application/Org1MSP
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f0 Proposed new policy Admins for Channel/Application/Org1MSP
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f1 Proposed new policy Readers for Channel/Application
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f2 Proposed new policy Writers for Channel/Application
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f3 Proposed new policy Admins for Channel/Application
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f4 Proposed new policy Admins for Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f5 Proposed new policy Readers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f6 Proposed new policy Writers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f7 Proposed new policy Readers for Channel/Orderer
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f8 Proposed new policy Writers for Channel/Orderer
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6f9 Proposed new policy BlockValidation for Channel/Orderer
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6fa Proposed new policy Admins for Channel/Orderer
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6fb Proposed new policy Admins for Channel
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6fc Proposed new policy Readers for Channel
2018-07-03 02:16:34.486 UTC [policies] NewManagerImpl -> DEBU 6fd Proposed new policy Writers for Channel
2018-07-03 02:16:34.486 UTC [common/configtx] addToMap -> DEBU 6fe Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.486 UTC [common/configtx] addToMap -> DEBU 6ff Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.486 UTC [common/configtx] addToMap -> DEBU 700 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 701 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 702 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 703 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 704 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 705 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 706 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 707 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 708 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 709 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 70a Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 70b Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 70c Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.487 UTC [common/configtx] addToMap -> DEBU 70d Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 70e Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 70f Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 710 Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 711 Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 712 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 713 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 714 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 715 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 716 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 717 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 718 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 719 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 71a Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 71b Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 71c Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 71d Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 71e Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 71f Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 720 Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 721 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 722 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 723 Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.488 UTC [common/configtx] addToMap -> DEBU 724 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.489 UTC [common/configtx] addToMap -> DEBU 725 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.489 UTC [common/configtx] addToMap -> DEBU 726 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.489 UTC [common/channelconfig] LogSanityChecks -> DEBU 727 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:34.489 UTC [common/channelconfig] LogSanityChecks -> DEBU 728 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 729 Manager Channel looking up path [Application]
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 72a Manager Channel has managers Application
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 72b Manager Channel has managers Orderer
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 72c Manager Channel/Application looking up path []
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 72d Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 72e Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:34.489 UTC [common/channelconfig] LogSanityChecks -> DEBU 72f As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:34.489 UTC [common/channelconfig] LogSanityChecks -> DEBU 730 As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:34.489 UTC [common/channelconfig] LogSanityChecks -> DEBU 731 As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 732 Manager Channel looking up path [Orderer]
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 733 Manager Channel has managers Orderer
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 734 Manager Channel has managers Application
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 735 Manager Channel/Orderer looking up path []
2018-07-03 02:16:34.489 UTC [policies] Manager -> DEBU 736 Manager Channel/Orderer has managers OrdererOrg
2018-07-03 02:16:34.489 UTC [common/channelconfig] LogSanityChecks -> DEBU 737 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:34.489 UTC [common/capabilities] Supported -> DEBU 738 Orderer capability V1_1 is supported and is enabled
2018-07-03 02:16:34.489 UTC [common/capabilities] Supported -> DEBU 739 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:34.489 UTC [msp] GetLocalMSP -> DEBU 73a Returning existing local MSP
2018-07-03 02:16:34.489 UTC [msp] GetDefaultSigningIdentity -> DEBU 73b Obtaining default signing identity
2018-07-03 02:16:34.489 UTC [msp] GetLocalMSP -> DEBU 73c Returning existing local MSP
2018-07-03 02:16:34.489 UTC [msp] GetDefaultSigningIdentity -> DEBU 73d Obtaining default signing identity
2018-07-03 02:16:34.489 UTC [msp/identity] Sign -> DEBU 73e Sign: plaintext: 0AC7060A1508011A060882B9EBD90522...73422621392269ACDB78D37DFA7A7EC5 
2018-07-03 02:16:34.489 UTC [msp/identity] Sign -> DEBU 73f Sign: digest: 2D0DC945CBA6169B92E1654F0EE607F2A8478D6124D9AAB1B2D7BB1CF1DE1CC5 
2018-07-03 02:16:34.489 UTC [policies] Evaluate -> DEBU 740 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers ==
2018-07-03 02:16:34.489 UTC [policies] Evaluate -> DEBU 741 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.489 UTC [policies] Evaluate -> DEBU 742 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers ==
2018-07-03 02:16:34.489 UTC [policies] Evaluate -> DEBU 743 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.489 UTC [policies] Evaluate -> DEBU 744 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers ==
2018-07-03 02:16:34.489 UTC [msp] DeserializeIdentity -> INFO 745 Obtaining identity
2018-07-03 02:16:34.490 UTC [msp/identity] newIdentity -> DEBU 746 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICDDCCAbOgAwIBAgIRAJfx3UkvJOVuBw3NB8Qul3swCgYIKoZIzj0EAwIwaTEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt
cGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFgxCzAJBgNV
BAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp
c2NvMRwwGgYDVQQDExNvcmRlcmVyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYI
KoZIzj0DAQcDQgAE/5xLZ92JWTiSM4i2ggFAuYbhu6u8rIagftwUtMv3jPQszoz8
nPjWsYFeYEHzx899PWfIUyOIfnVBwoyz6ak/Y6NNMEswDgYDVR0PAQH/BAQDAgeA
MAwGA1UdEwEB/wQCMAAwKwYDVR0jBCQwIoAg6DQr5VJxBqKs94jESmTBkbKyM/7h
YqJ0bMTCKaFf5jEwCgYIKoZIzj0EAwIDRwAwRAIgL3MXJWUnZ9LWe1OdJVUiUp4B
bxS7GTHIjIW6LIuNd90CIFDQDGssEWLfj3kBRBJqouol121+ktRe5rU9FcyUK3aD
-----END CERTIFICATE-----
2018-07-03 02:16:34.490 UTC [cauthdsl] func1 -> DEBU 747 0xc42000e808 gate 1530584194490155026 evaluation starts
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 748 0xc42000e808 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 749 0xc42000e808 processing identity 0 with bytes of 0a0a4f7264657265724d53501281062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434444434341624f674177494241674952414a667833556b764a4f56754277334e423851756c337377436759494b6f5a497a6a3045417749776154454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784644415342674e5642416f54433256345957317762475575593239744d52637746515944565151444577356a5953356c654746740a6347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c614d466778437a414a42674e560a42415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d52597746415944565151484577315459573467526e4a68626d4e700a63324e764d527777476759445651514445784e76636d526c636d56794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159490a4b6f5a497a6a304441516344516741452f35784c5a39324a575469534d3469326767464175596268753675387249616766747755744d76336a5051737a6f7a380a6e506a57735946655945487a783839395057664955794f49666e5642776f797a36616b2f59364e4e4d45737744675944565230504151482f42415144416765410a4d41774741315564457745422f7751434d4141774b7759445652306a42435177496f41673644517235564a7842714b7339346a45536d54426b624b794d2f37680a59714a30624d54434b614666356a4577436759494b6f5a497a6a30454177494452774177524149674c334d584a57556e5a394c5765314f644a565569557034420a62785337475448496a4957364c49754e64393043494644514447737345574c666a336b4252424a716f756f6c3132312b6b74526535725539466379554b3361440a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 74a 0xc42000e808 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected Org2MSP, got OrdererMSP)
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 74b 0xc42000e808 principal evaluation fails
2018-07-03 02:16:34.490 UTC [cauthdsl] func1 -> DEBU 74c 0xc42000e808 gate 1530584194490155026 evaluation fails
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 74d Signature set did not satisfy policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 74e == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 74f == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers ==
2018-07-03 02:16:34.490 UTC [cauthdsl] func1 -> DEBU 750 0xc42000e818 gate 1530584194490279233 evaluation starts
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 751 0xc42000e818 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 752 0xc42000e818 processing identity 0 with bytes of 0a0a4f7264657265724d53501281062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434444434341624f674177494241674952414a667833556b764a4f56754277334e423851756c337377436759494b6f5a497a6a3045417749776154454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784644415342674e5642416f54433256345957317762475575593239744d52637746515944565151444577356a5953356c654746740a6347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c614d466778437a414a42674e560a42415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d52597746415944565151484577315459573467526e4a68626d4e700a63324e764d527777476759445651514445784e76636d526c636d56794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159490a4b6f5a497a6a304441516344516741452f35784c5a39324a575469534d3469326767464175596268753675387249616766747755744d76336a5051737a6f7a380a6e506a57735946655945487a783839395057664955794f49666e5642776f797a36616b2f59364e4e4d45737744675944565230504151482f42415144416765410a4d41774741315564457745422f7751434d4141774b7759445652306a42435177496f41673644517235564a7842714b7339346a45536d54426b624b794d2f37680a59714a30624d54434b614666356a4577436759494b6f5a497a6a30454177494452774177524149674c334d584a57556e5a394c5765314f644a565569557034420a62785337475448496a4957364c49754e64393043494644514447737345574c666a336b4252424a716f756f6c3132312b6b74526535725539466379554b3361440a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 753 0xc42000e818 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected Org1MSP, got OrdererMSP)
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 754 0xc42000e818 principal evaluation fails
2018-07-03 02:16:34.490 UTC [cauthdsl] func1 -> DEBU 755 0xc42000e818 gate 1530584194490279233 evaluation fails
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 756 Signature set did not satisfy policy /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 757 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.490 UTC [policies] func1 -> DEBU 758 Evaluation Failed: Only 0 policies were satisfied, but needed 1 of [ Org2MSP.Writers Org1MSP.Writers ]
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 759 Signature set did not satisfy policy /Channel/Application/Writers
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 75a == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Writers
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 75b == Evaluating *policies.implicitMetaPolicy Policy /Channel/Orderer/Writers ==
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 75c This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.490 UTC [policies] Evaluate -> DEBU 75d == Evaluating *cauthdsl.policy Policy /Channel/Orderer/OrdererOrg/Writers ==
2018-07-03 02:16:34.490 UTC [cauthdsl] func1 -> DEBU 75e 0xc42000e820 gate 1530584194490411327 evaluation starts
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 75f 0xc42000e820 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.490 UTC [cauthdsl] func2 -> DEBU 760 0xc42000e820 processing identity 0 with bytes of 0a0a4f7264657265724d53501281062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434444434341624f674177494241674952414a667833556b764a4f56754277334e423851756c337377436759494b6f5a497a6a3045417749776154454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784644415342674e5642416f54433256345957317762475575593239744d52637746515944565151444577356a5953356c654746740a6347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c614d466778437a414a42674e560a42415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d52597746415944565151484577315459573467526e4a68626d4e700a63324e764d527777476759445651514445784e76636d526c636d56794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159490a4b6f5a497a6a304441516344516741452f35784c5a39324a575469534d3469326767464175596268753675387249616766747755744d76336a5051737a6f7a380a6e506a57735946655945487a783839395057664955794f49666e5642776f797a36616b2f59364e4e4d45737744675944565230504151482f42415144416765410a4d41774741315564457745422f7751434d4141774b7759445652306a42435177496f41673644517235564a7842714b7339346a45536d54426b624b794d2f37680a59714a30624d54434b614666356a4577436759494b6f5a497a6a30454177494452774177524149674c334d584a57556e5a394c5765314f644a565569557034420a62785337475448496a4957364c49754e64393043494644514447737345574c666a336b4252424a716f756f6c3132312b6b74526535725539466379554b3361440a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.490 UTC [msp] SatisfiesPrincipal -> DEBU 761 Checking if identity satisfies MEMBER role for OrdererMSP
2018-07-03 02:16:34.490 UTC [msp] Validate -> DEBU 762 MSP OrdererMSP validating identity
2018-07-03 02:16:34.491 UTC [cauthdsl] func2 -> DEBU 763 0xc42000e820 principal matched by identity 0
2018-07-03 02:16:34.491 UTC [msp/identity] Verify -> DEBU 764 Verify: digest = 00000000  2d 0d c9 45 cb a6 16 9b  92 e1 65 4f 0e e6 07 f2  |-..E......eO....|
00000010  a8 47 8d 61 24 d9 aa b1  b2 d7 bb 1c f1 de 1c c5  |.G.a$...........|
2018-07-03 02:16:34.491 UTC [msp/identity] Verify -> DEBU 765 Verify: sig = 00000000  30 45 02 21 00 ba ff 4d  b2 47 87 19 5d 65 30 f4  |0E.!...M.G..]e0.|
00000010  30 14 56 37 20 3a 6b 6b  2d 01 40 6b 87 e3 96 aa  |0.V7 :kk-.@k....|
00000020  c5 60 af dd 14 02 20 3f  70 36 97 d4 ac c3 b1 14  |.`.... ?p6......|
00000030  f4 21 f2 e3 16 68 2a d0  a8 c2 19 e7 32 55 ad 7d  |.!...h*.....2U.}|
00000040  c4 ab 2c 66 7a 52 f2                              |..,fzR.|
2018-07-03 02:16:34.491 UTC [cauthdsl] func2 -> DEBU 766 0xc42000e820 principal evaluation succeeds for identity 0
2018-07-03 02:16:34.491 UTC [cauthdsl] func1 -> DEBU 767 0xc42000e820 gate 1530584194490411327 evaluation succeeds
2018-07-03 02:16:34.491 UTC [policies] Evaluate -> DEBU 768 Signature set satisfies policy /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.491 UTC [policies] Evaluate -> DEBU 769 == Done Evaluating *cauthdsl.policy Policy /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.491 UTC [policies] Evaluate -> DEBU 76a Signature set satisfies policy /Channel/Orderer/Writers
2018-07-03 02:16:34.491 UTC [policies] Evaluate -> DEBU 76b == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Orderer/Writers
2018-07-03 02:16:34.491 UTC [policies] Evaluate -> DEBU 76c Signature set satisfies policy /Channel/Writers
2018-07-03 02:16:34.491 UTC [policies] Evaluate -> DEBU 76d == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Writers
2018-07-03 02:16:34.491 UTC [orderer/common/broadcast] Handle -> DEBU 76e [channel: mychannel] Broadcast has successfully enqueued message of type CONFIG_UPDATE from 172.18.0.7:42730
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 76f Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 770 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 771 Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 772 Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 774 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.491 UTC [orderer/common/broadcast] Handle -> DEBU 773 Received EOF from 172.18.0.7:42730, hangup
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 775 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.491 UTC [orderer/common/server] func1 -> DEBU 776 Closing Broadcast stream
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 777 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 778 Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 779 Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 77a Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.491 UTC [common/configtx] addToMap -> DEBU 77b Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.492 UTC [common/configtx] addToMap -> DEBU 77c Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.492 UTC [common/configtx] addToMap -> DEBU 77d Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.492 UTC [common/configtx] addToMap -> DEBU 77e Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.492 UTC [common/configtx] addToMap -> DEBU 77f Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.492 UTC [common/configtx] verifyDeltaSet -> DEBU 780 Processing change to key: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.492 UTC [common/configtx] policyForItem -> DEBU 781 Getting policy for item Org2MSP with mod_policy Admins
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 782 Manager Channel looking up path [Application]
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 783 Manager Channel has managers Application
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 784 Manager Channel has managers Orderer
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 785 Manager Channel/Application looking up path []
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 786 Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 787 Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 788 Manager Channel/Application looking up path [Org2MSP]
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 789 Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 78a Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:34.492 UTC [policies] Manager -> DEBU 78b Manager Channel/Application/Org2MSP looking up path []
2018-07-03 02:16:34.492 UTC [policies] Evaluate -> DEBU 78c == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Admins ==
2018-07-03 02:16:34.492 UTC [cauthdsl] func1 -> DEBU 78d 0xc42000eef8 gate 1530584194492273355 evaluation starts
2018-07-03 02:16:34.492 UTC [cauthdsl] func2 -> DEBU 78e 0xc42000eef8 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.492 UTC [cauthdsl] func2 -> DEBU 78f 0xc42000eef8 processing identity 0 with bytes of 0a074f7267324d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b6a4343416447674177494241674952414d4c6c5861304f4c3949585a62544a3739557179664577436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a49755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a49755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42734d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a45504d4130474131554543784d47593278705a5735304d523877485159445651514444425a425a473170626b42760a636d63794c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a304441516344516741454b685675674975530a7069483568466f78514e5354482b49413465622b4b47465a322b34383654723170744e38446a64584964434b5142334a43346159706a347a4a326f54546977720a2f2b796d3948374e31536b36504b4e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759440a5652306a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a490a7a6a304541774944527741775241496766334f4c6b64635a41776b747269366b4867494a6c326a4572644c67374c66454c645a683478583676714d4349484a410a5a7a6b654942347742304f35397046396f4330664f47757a6d47687a366d424146414b38516b2b430a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.492 UTC [msp] SatisfiesPrincipal -> DEBU 790 Checking if identity satisfies ADMIN role for Org2MSP
2018-07-03 02:16:34.492 UTC [cauthdsl] func2 -> DEBU 791 0xc42000eef8 principal matched by identity 0
2018-07-03 02:16:34.492 UTC [msp/identity] Verify -> DEBU 792 Verify: digest = 00000000  48 90 f7 60 1d 05 d1 24  25 f2 3b cd 40 5e 35 82  |H..`...$%.;.@^5.|
00000010  b6 5c f2 64 bb d2 dd a8  e1 35 38 30 2c 2a 12 03  |.\.d.....580,*..|
2018-07-03 02:16:34.492 UTC [msp/identity] Verify -> DEBU 793 Verify: sig = 00000000  30 45 02 21 00 c6 a2 62  27 ae 84 0d 02 49 dc 00  |0E.!...b'....I..|
00000010  b7 da 64 71 81 66 c9 c1  e1 f9 46 9f d4 81 b8 48  |..dq.f....F....H|
00000020  78 2e 78 5b f1 02 20 0f  c5 34 fc 1e af 72 93 98  |x.x[.. ..4...r..|
00000030  da e3 ce 92 b6 92 33 fd  b6 ff fd 05 d8 f3 c3 59  |......3........Y|
00000040  f7 40 13 eb 48 a3 af                              |.@..H..|
2018-07-03 02:16:34.492 UTC [cauthdsl] func2 -> DEBU 794 0xc42000eef8 principal evaluation succeeds for identity 0
2018-07-03 02:16:34.492 UTC [cauthdsl] func1 -> DEBU 795 0xc42000eef8 gate 1530584194492273355 evaluation succeeds
2018-07-03 02:16:34.492 UTC [policies] Evaluate -> DEBU 796 Signature set satisfies policy /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.492 UTC [policies] Evaluate -> DEBU 797 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.492 UTC [common/configtx] verifyDeltaSet -> DEBU 798 Processing change to key: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 799 Setting policy for key Admins to 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 79a Setting policy for key Readers to 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 79b Setting policy for key Writers to 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 79c Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 79d Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\013\022\t\n\007Org1MSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 79e Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\r\022\013\n\007Org1MSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 79f Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 7a0 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 7a1 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.492 UTC [common/configtx] recurseConfigMap -> DEBU 7a2 Setting policy for key Admins to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\020\022\016\n\nOrdererMSP\020\001" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a3 Setting policy for key Readers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a4 Setting policy for key Writers to policy:<type:1 value:"\022\010\022\006\010\001\022\002\010\000\032\016\022\014\n\nOrdererMSP" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a5 Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a6 Setting policy for key BlockValidation to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a7 Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a8 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7a9 Setting policy for key Readers to policy:<type:3 value:"\n\007Readers" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7aa Setting policy for key Writers to policy:<type:3 value:"\n\007Writers" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/configtx] recurseConfigMap -> DEBU 7ab Setting policy for key Admins to policy:<type:3 value:"\n\006Admins\020\002" > mod_policy:"Admins" 
2018-07-03 02:16:34.493 UTC [common/channelconfig] NewStandardValues -> DEBU 7ac Initializing protos for *channelconfig.ChannelProtos
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7ad Processing field: HashingAlgorithm
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7ae Processing field: BlockDataHashingStructure
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7af Processing field: OrdererAddresses
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7b0 Processing field: Consortium
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7b1 Processing field: Capabilities
2018-07-03 02:16:34.493 UTC [common/channelconfig] NewStandardValues -> DEBU 7b2 Initializing protos for *channelconfig.ApplicationProtos
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7b3 Processing field: Capabilities
2018-07-03 02:16:34.493 UTC [common/channelconfig] NewStandardValues -> DEBU 7b4 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7b5 Processing field: AnchorPeers
2018-07-03 02:16:34.493 UTC [common/channelconfig] NewStandardValues -> DEBU 7b6 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.493 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7b7 Processing field: MSP
2018-07-03 02:16:34.493 UTC [common/channelconfig] Validate -> DEBU 7b8 Anchor peers for org Org1MSP are anchor_peers:<host:"peer0.org1.example.com" port:7051 > 
2018-07-03 02:16:34.493 UTC [common/channelconfig] validateMSP -> DEBU 7b9 Setting up MSP for org Org1MSP
2018-07-03 02:16:34.493 UTC [msp] newBccspMsp -> DEBU 7ba Creating BCCSP-based MSP instance
2018-07-03 02:16:34.493 UTC [msp] New -> DEBU 7bb Creating Cache-MSP instance
2018-07-03 02:16:34.493 UTC [msp] Setup -> DEBU 7bc Setting up MSP instance Org1MSP
2018-07-03 02:16:34.493 UTC [msp/identity] newIdentity -> DEBU 7bd Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQzCCAemgAwIBAgIQNN53IDSKbZj63SE2s8RppzAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcxLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcxLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
QjmQjz8p8ZrM8rqlpgmxeXzHTyppVzwvBbA4HdANqmdKkhl3++ek7nGu1OSO3U+k
kp/ymOxjAEaoYdfTSNslXKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgWQf0CilwFHOe1hgWV3dj
4zF3oPvlaN4qVn2w6yNXPxMwCgYIKoZIzj0EAwIDSAAwRQIhANLNA9OpEaMdd1e1
EAnaShpea/sSnvNFfExiMx0xpdfaAiAuE3eo8FTtAdfU1D+kCuMlAnK901gVpIDo
JaPsTQzNKw==
-----END CERTIFICATE-----
2018-07-03 02:16:34.494 UTC [msp/identity] newIdentity -> DEBU 7be Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKTCCAdCgAwIBAgIQb9OtXXJnXkMzXTLRqUj27TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMS5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMS5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MGwxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMQ8wDQYDVQQLEwZjbGllbnQxHzAdBgNVBAMMFkFkbWluQG9y
ZzEuZXhhbXBsZS5jb20wWTATBgcqhkjOPQIBBggqhkjOPQMBBwNCAAQdRq06O6yf
KtsHBZWIUwS89CYgRRxg53vNyrfeGgurd456XI99nOaJGVyrReLSIfc+Eu+guk0p
cOjtc3lc5gZro00wSzAOBgNVHQ8BAf8EBAMCB4AwDAYDVR0TAQH/BAIwADArBgNV
HSMEJDAigCBZB/QKKXAUc57WGBZXd2PjMXeg++Vo3ipWfbDrI1c/EzAKBggqhkjO
PQQDAgNHADBEAiAmuV7O1UkAUtXsBSIs9nyo5TfAoyswweaJQDgsH32kxAIgVHN2
SNL3R81NJsrz/uMaB9rKdHKecQ6nEE9nYqc2zGM=
-----END CERTIFICATE-----
2018-07-03 02:16:34.494 UTC [msp] SatisfiesPrincipal -> DEBU 7bf Checking if identity satisfies role [CLIENT] for Org1MSP
2018-07-03 02:16:34.494 UTC [msp] Validate -> DEBU 7c0 MSP Org1MSP validating identity
2018-07-03 02:16:34.494 UTC [msp] getCertificationChain -> DEBU 7c1 MSP Org1MSP getting certification chain
2018-07-03 02:16:34.494 UTC [msp] hasOURole -> DEBU 7c2 MSP Org1MSP checking if the identity is a client
2018-07-03 02:16:34.494 UTC [msp] getCertificationChain -> DEBU 7c3 MSP Org1MSP getting certification chain
2018-07-03 02:16:34.494 UTC [common/channelconfig] NewStandardValues -> DEBU 7c4 Initializing protos for *channelconfig.ApplicationOrgProtos
2018-07-03 02:16:34.494 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7c5 Processing field: AnchorPeers
2018-07-03 02:16:34.494 UTC [common/channelconfig] NewStandardValues -> DEBU 7c6 Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.494 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7c7 Processing field: MSP
2018-07-03 02:16:34.494 UTC [common/channelconfig] Validate -> DEBU 7c8 Anchor peers for org Org2MSP are anchor_peers:<host:"peer0.org2.example.com" port:7051 > 
2018-07-03 02:16:34.495 UTC [common/channelconfig] validateMSP -> DEBU 7c9 Setting up MSP for org Org2MSP
2018-07-03 02:16:34.495 UTC [msp] newBccspMsp -> DEBU 7ca Creating BCCSP-based MSP instance
2018-07-03 02:16:34.495 UTC [msp] New -> DEBU 7cb Creating Cache-MSP instance
2018-07-03 02:16:34.495 UTC [msp] Setup -> DEBU 7cc Setting up MSP instance Org2MSP
2018-07-03 02:16:34.495 UTC [msp/identity] newIdentity -> DEBU 7cd Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICQjCCAemgAwIBAgIQFZFYX0qNyHABwzPvR3dr7TAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MHMxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMRkwFwYDVQQKExBvcmcyLmV4YW1wbGUuY29tMRwwGgYDVQQD
ExNjYS5vcmcyLmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAE
1DpMrWDLZixGudn+YGOx17mGq++gGXFwzylp5g0Dss8+yUc2kcpgnrldo/7KHYnn
b3Y2JL6A4MIogGm8OR8gOKNfMF0wDgYDVR0PAQH/BAQDAgGmMA8GA1UdJQQIMAYG
BFUdJQAwDwYDVR0TAQH/BAUwAwEB/zApBgNVHQ4EIgQgY+8FVhpy2+cdbjPQhM7d
b+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0EAwIDRwAwRAIgYywGI3wiVcUCEWVl
TmGch4APmRk6KOIoFNsi/Lwj7N0CID5eu4EM/wBFlb4uAAHVS82VwZvAKQ3qwE13
G4VS/ZlT
-----END CERTIFICATE-----
2018-07-03 02:16:34.495 UTC [msp/identity] newIdentity -> DEBU 7ce Creating identity instance for cert -----BEGIN CERTIFICATE-----
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
2018-07-03 02:16:34.495 UTC [msp] SatisfiesPrincipal -> DEBU 7cf Checking if identity satisfies role [CLIENT] for Org2MSP
2018-07-03 02:16:34.495 UTC [msp] Validate -> DEBU 7d0 MSP Org2MSP validating identity
2018-07-03 02:16:34.498 UTC [common/deliver] Handle -> WARN 7d1 Error reading from 172.18.0.7:42728: rpc error: code = Canceled desc = context canceled
2018-07-03 02:16:34.498 UTC [orderer/common/server] func1 -> DEBU 7d2 Closing Deliver stream
2018-07-03 02:16:34.498 UTC [grpc] Printf -> DEBU 7d3 transport: http2Server.HandleStreams failed to read frame: read tcp 172.18.0.4:7050->172.18.0.7:42730: read: connection reset by peer
2018-07-03 02:16:34.498 UTC [msp] getCertificationChain -> DEBU 7d4 MSP Org2MSP getting certification chain
2018-07-03 02:16:34.499 UTC [msp] hasOURole -> DEBU 7d5 MSP Org2MSP checking if the identity is a client
2018-07-03 02:16:34.499 UTC [msp] getCertificationChain -> DEBU 7d6 MSP Org2MSP getting certification chain
2018-07-03 02:16:34.499 UTC [common/channelconfig] NewStandardValues -> DEBU 7d7 Initializing protos for *channelconfig.OrdererProtos
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7d8 Processing field: ConsensusType
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7d9 Processing field: BatchSize
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7da Processing field: BatchTimeout
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7db Processing field: KafkaBrokers
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7dc Processing field: ChannelRestrictions
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7dd Processing field: Capabilities
2018-07-03 02:16:34.499 UTC [common/channelconfig] NewStandardValues -> DEBU 7de Initializing protos for *channelconfig.OrganizationProtos
2018-07-03 02:16:34.499 UTC [common/channelconfig] initializeProtosStruct -> DEBU 7df Processing field: MSP
2018-07-03 02:16:34.499 UTC [common/channelconfig] validateMSP -> DEBU 7e0 Setting up MSP for org OrdererOrg
2018-07-03 02:16:34.499 UTC [msp] newBccspMsp -> DEBU 7e1 Creating BCCSP-based MSP instance
2018-07-03 02:16:34.499 UTC [msp] New -> DEBU 7e2 Creating Cache-MSP instance
2018-07-03 02:16:34.500 UTC [msp] Setup -> DEBU 7e3 Setting up MSP instance OrdererMSP
2018-07-03 02:16:34.500 UTC [msp/identity] newIdentity -> DEBU 7e4 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICLzCCAdWgAwIBAgIQT9BR71O0WiqB22Q4gJAeWjAKBggqhkjOPQQDAjBpMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEUMBIGA1UEChMLZXhhbXBsZS5jb20xFzAVBgNVBAMTDmNhLmV4YW1w
bGUuY29tMB4XDTE4MDUzMTAzMzcwOVoXDTI4MDUyODAzMzcwOVowaTELMAkGA1UE
BhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBGcmFuY2lz
Y28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFtcGxlLmNv
bTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABBNUAqmM44BVDenb0uBaxucARQcn
Hpr3wFRMXBm0RgV+rqnsOTqOL3t9dL/2/7TBU12XBxFh7VXfTN0cc6IHWQqjXzBd
MA4GA1UdDwEB/wQEAwIBpjAPBgNVHSUECDAGBgRVHSUAMA8GA1UdEwEB/wQFMAMB
Af8wKQYDVR0OBCIEIOg0K+VScQairPeIxEpkwZGysjP+4WKidGzEwimhX+YxMAoG
CCqGSM49BAMCA0gAMEUCIQCrzERmN5HFZUELtCb1Lbrm3jWw8NRldPLSv6zoKxJj
ZgIgCuRkj6SxZ4FbHQwTmxcoU5uanbcNgBBhAj0QjNvl0XQ=
-----END CERTIFICATE-----
2018-07-03 02:16:34.500 UTC [msp/identity] newIdentity -> DEBU 7e5 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICCzCCAbGgAwIBAgIRAM2MQguj0oQ7kO1TNSQAlHkwCgYIKoZIzj0EAwIwaTEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xFDASBgNVBAoTC2V4YW1wbGUuY29tMRcwFQYDVQQDEw5jYS5leGFt
cGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDlaMFYxCzAJBgNV
BAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1TYW4gRnJhbmNp
c2NvMRowGAYDVQQDDBFBZG1pbkBleGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqG
SM49AwEHA0IABIf2xS47mO+KmTh6S+NPhKyRoeJBCZO5vU4wJJ4s0tjEnEyPgahh
cUP/m8bKuT4377HRG4JKbhk8R2Jl66VLWuSjTTBLMA4GA1UdDwEB/wQEAwIHgDAM
BgNVHRMBAf8EAjAAMCsGA1UdIwQkMCKAIOg0K+VScQairPeIxEpkwZGysjP+4WKi
dGzEwimhX+YxMAoGCCqGSM49BAMCA0gAMEUCIQDztaPJ+SggqCqb0fHoedA95TQX
/iUjtxExDKqf6yYq8gIgQ3l606/hzPDbDa9qi6ElaOXHWD6xXqtiNInf9PXOXUs=
-----END CERTIFICATE-----
2018-07-03 02:16:34.501 UTC [msp] Validate -> DEBU 7e6 MSP OrdererMSP validating identity
2018-07-03 02:16:34.501 UTC [msp] Setup -> DEBU 7e7 Setting up the MSP manager (3 msps)
2018-07-03 02:16:34.501 UTC [msp] Setup -> DEBU 7e8 MSP manager setup complete, setup 3 msps
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7e9 Proposed new policy Admins for Channel/Application/Org2MSP
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7ea Proposed new policy Readers for Channel/Application/Org2MSP
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7eb Proposed new policy Writers for Channel/Application/Org2MSP
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7ec Proposed new policy Readers for Channel/Application/Org1MSP
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7ed Proposed new policy Writers for Channel/Application/Org1MSP
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7ee Proposed new policy Admins for Channel/Application/Org1MSP
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7ef Proposed new policy Writers for Channel/Application
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f0 Proposed new policy Admins for Channel/Application
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f1 Proposed new policy Readers for Channel/Application
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f2 Proposed new policy Admins for Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f3 Proposed new policy Readers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f4 Proposed new policy Writers for Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f5 Proposed new policy Writers for Channel/Orderer
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f6 Proposed new policy BlockValidation for Channel/Orderer
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f7 Proposed new policy Admins for Channel/Orderer
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f8 Proposed new policy Readers for Channel/Orderer
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7f9 Proposed new policy Admins for Channel
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7fa Proposed new policy Readers for Channel
2018-07-03 02:16:34.501 UTC [policies] NewManagerImpl -> DEBU 7fb Proposed new policy Writers for Channel
2018-07-03 02:16:34.501 UTC [common/configtx] addToMap -> DEBU 7fc Adding to config map: [Group]  /Channel
2018-07-03 02:16:34.501 UTC [common/configtx] addToMap -> DEBU 7fd Adding to config map: [Group]  /Channel/Application
2018-07-03 02:16:34.501 UTC [common/configtx] addToMap -> DEBU 7fe Adding to config map: [Group]  /Channel/Application/Org2MSP
2018-07-03 02:16:34.501 UTC [common/configtx] addToMap -> DEBU 7ff Adding to config map: [Value]  /Channel/Application/Org2MSP/MSP
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 800 Adding to config map: [Value]  /Channel/Application/Org2MSP/AnchorPeers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 801 Adding to config map: [Policy] /Channel/Application/Org2MSP/Admins
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 802 Adding to config map: [Policy] /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 803 Adding to config map: [Policy] /Channel/Application/Org2MSP/Writers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 804 Adding to config map: [Group]  /Channel/Application/Org1MSP
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 805 Adding to config map: [Value]  /Channel/Application/Org1MSP/MSP
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 806 Adding to config map: [Value]  /Channel/Application/Org1MSP/AnchorPeers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 807 Adding to config map: [Policy] /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 808 Adding to config map: [Policy] /Channel/Application/Org1MSP/Writers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 809 Adding to config map: [Policy] /Channel/Application/Org1MSP/Admins
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 80a Adding to config map: [Value]  /Channel/Application/Capabilities
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 80b Adding to config map: [Policy] /Channel/Application/Writers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 80c Adding to config map: [Policy] /Channel/Application/Admins
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 80d Adding to config map: [Policy] /Channel/Application/Readers
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 80e Adding to config map: [Group]  /Channel/Orderer
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 80f Adding to config map: [Group]  /Channel/Orderer/OrdererOrg
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 810 Adding to config map: [Value]  /Channel/Orderer/OrdererOrg/MSP
2018-07-03 02:16:34.502 UTC [common/configtx] addToMap -> DEBU 811 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Readers
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 812 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Writers
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 813 Adding to config map: [Policy] /Channel/Orderer/OrdererOrg/Admins
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 814 Adding to config map: [Value]  /Channel/Orderer/ConsensusType
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 815 Adding to config map: [Value]  /Channel/Orderer/BatchSize
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 816 Adding to config map: [Value]  /Channel/Orderer/BatchTimeout
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 817 Adding to config map: [Value]  /Channel/Orderer/ChannelRestrictions
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 818 Adding to config map: [Value]  /Channel/Orderer/Capabilities
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 819 Adding to config map: [Policy] /Channel/Orderer/Writers
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 81a Adding to config map: [Policy] /Channel/Orderer/BlockValidation
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 81b Adding to config map: [Policy] /Channel/Orderer/Admins
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 81c Adding to config map: [Policy] /Channel/Orderer/Readers
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 81d Adding to config map: [Value]  /Channel/HashingAlgorithm
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 81e Adding to config map: [Value]  /Channel/BlockDataHashingStructure
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 81f Adding to config map: [Value]  /Channel/OrdererAddresses
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 820 Adding to config map: [Value]  /Channel/Capabilities
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 821 Adding to config map: [Value]  /Channel/Consortium
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 822 Adding to config map: [Policy] /Channel/Writers
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 823 Adding to config map: [Policy] /Channel/Admins
2018-07-03 02:16:34.503 UTC [common/configtx] addToMap -> DEBU 824 Adding to config map: [Policy] /Channel/Readers
2018-07-03 02:16:34.503 UTC [common/channelconfig] LogSanityChecks -> DEBU 825 As expected, current configuration has policy '/Channel/Readers'
2018-07-03 02:16:34.503 UTC [common/channelconfig] LogSanityChecks -> DEBU 826 As expected, current configuration has policy '/Channel/Writers'
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 827 Manager Channel looking up path [Application]
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 828 Manager Channel has managers Application
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 829 Manager Channel has managers Orderer
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 82a Manager Channel/Application looking up path []
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 82b Manager Channel/Application has managers Org1MSP
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 82c Manager Channel/Application has managers Org2MSP
2018-07-03 02:16:34.503 UTC [common/channelconfig] LogSanityChecks -> DEBU 82d As expected, current configuration has policy '/Channel/Application/Readers'
2018-07-03 02:16:34.503 UTC [common/channelconfig] LogSanityChecks -> DEBU 82e As expected, current configuration has policy '/Channel/Application/Writers'
2018-07-03 02:16:34.503 UTC [common/channelconfig] LogSanityChecks -> DEBU 82f As expected, current configuration has policy '/Channel/Application/Admins'
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 830 Manager Channel looking up path [Orderer]
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 831 Manager Channel has managers Application
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 832 Manager Channel has managers Orderer
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 833 Manager Channel/Orderer looking up path []
2018-07-03 02:16:34.503 UTC [policies] Manager -> DEBU 834 Manager Channel/Orderer has managers OrdererOrg
2018-07-03 02:16:34.503 UTC [common/channelconfig] LogSanityChecks -> DEBU 835 As expected, current configuration has policy '/Channel/Orderer/BlockValidation'
2018-07-03 02:16:34.503 UTC [common/capabilities] Supported -> DEBU 836 Orderer capability V1_1 is supported and is enabled
2018-07-03 02:16:34.503 UTC [common/capabilities] Supported -> DEBU 837 Channel capability V1_1 is supported and is enabled
2018-07-03 02:16:34.503 UTC [msp] GetLocalMSP -> DEBU 838 Returning existing local MSP
2018-07-03 02:16:34.503 UTC [msp] GetDefaultSigningIdentity -> DEBU 839 Obtaining default signing identity
2018-07-03 02:16:34.503 UTC [msp] GetLocalMSP -> DEBU 83a Returning existing local MSP
2018-07-03 02:16:34.503 UTC [msp] GetDefaultSigningIdentity -> DEBU 83b Obtaining default signing identity
2018-07-03 02:16:34.503 UTC [msp/identity] Sign -> DEBU 83c Sign: plaintext: 0A90060A0A4F7264657265724D535012...F54F0EE7A8CC73B5AFFE211AA00E0B4E 
2018-07-03 02:16:34.503 UTC [msp/identity] Sign -> DEBU 83d Sign: digest: 543C5BB3A72A8491FC1E133E0BEA41878B84F25CC38045C80F1DEB29BC6E7633 
2018-07-03 02:16:34.503 UTC [orderer/commmon/multichannel] addLastConfigSignature -> DEBU 83e [channel: mychannel] Detected lastConfigSeq transitioning from 2 to 3, setting lastConfigBlockNum from 1 to 2
2018-07-03 02:16:34.503 UTC [msp] GetLocalMSP -> DEBU 83f Returning existing local MSP
2018-07-03 02:16:34.503 UTC [msp] GetDefaultSigningIdentity -> DEBU 840 Obtaining default signing identity
2018-07-03 02:16:34.503 UTC [orderer/commmon/multichannel] addLastConfigSignature -> DEBU 841 [channel: mychannel] About to write block, setting its LAST_CONFIG to 2
2018-07-03 02:16:34.503 UTC [msp] GetLocalMSP -> DEBU 842 Returning existing local MSP
2018-07-03 02:16:34.503 UTC [msp] GetDefaultSigningIdentity -> DEBU 843 Obtaining default signing identity
2018-07-03 02:16:34.503 UTC [msp/identity] Sign -> DEBU 844 Sign: plaintext: 08020A90060A0A4F7264657265724D53...F54F0EE7A8CC73B5AFFE211AA00E0B4E 
2018-07-03 02:16:34.503 UTC [msp/identity] Sign -> DEBU 845 Sign: digest: 1B3A94D966B4B8EB2C68A46AEEAE3AFBF14B093796663053FE8B68C95DED1DE3 
2018-07-03 02:16:34.506 UTC [fsblkstorage] indexBlock -> DEBU 846 Indexing block [blockNum=2, blockHash=[]byte{0x22, 0x8d, 0x20, 0xe, 0xe2, 0x5c, 0xa0, 0x3c, 0xd0, 0x74, 0xe9, 0x2d, 0x10, 0x62, 0xf4, 0xb8, 0x5c, 0x9, 0x54, 0xb6, 0x3d, 0xb0, 0x60, 0x23, 0x3b, 0xa0, 0xe3, 0x9b, 0x27, 0xfa, 0xf6, 0xa8} txOffsets=
txId= locPointer=offset=71, bytesLength=15669
]
2018-07-03 02:16:34.507 UTC [fsblkstorage] updateCheckpoint -> DEBU 847 Broadcasting about update checkpointInfo: latestFileChunkSuffixNum=[0], latestFileChunksize=[50658], isChainEmpty=[false], lastBlockNumber=[2]
2018-07-03 02:16:34.507 UTC [orderer/commmon/multichannel] commitBlock -> DEBU 848 [channel: mychannel] Wrote block 2
2018-07-03 02:16:34.507 UTC [fsblkstorage] waitForBlock -> DEBU 849 Came out of wait. maxAvailaBlockNumber=[2]
2018-07-03 02:16:34.507 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 84a Remaining bytes=[17533], Going to peek [8] bytes
2018-07-03 02:16:34.507 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 84b Returning blockbytes - length=[17530], placementInfo={fileNum=[0], startOffset=[33125], bytesOffset=[33128]}
2018-07-03 02:16:34.507 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 84d blockbytes [17530] read from file [0]
2018-07-03 02:16:34.507 UTC [fsblkstorage] waitForBlock -> DEBU 84c Came out of wait. maxAvailaBlockNumber=[2]
2018-07-03 02:16:34.507 UTC [policies] Evaluate -> DEBU 84f == Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers ==
2018-07-03 02:16:34.507 UTC [policies] Evaluate -> DEBU 850 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.507 UTC [policies] Evaluate -> DEBU 851 == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers ==
2018-07-03 02:16:34.507 UTC [policies] Evaluate -> DEBU 852 This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.507 UTC [policies] Evaluate -> DEBU 853 == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers ==
2018-07-03 02:16:34.507 UTC [msp] DeserializeIdentity -> INFO 854 Obtaining identity
2018-07-03 02:16:34.507 UTC [msp/identity] newIdentity -> DEBU 855 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICJzCCAc6gAwIBAgIQYJ1nWgjjFK2QEuiX09MP/jAKBggqhkjOPQQDAjBzMQsw
CQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMNU2FuIEZy
YW5jaXNjbzEZMBcGA1UEChMQb3JnMi5leGFtcGxlLmNvbTEcMBoGA1UEAxMTY2Eu
b3JnMi5leGFtcGxlLmNvbTAeFw0xODA1MzEwMzM3MDlaFw0yODA1MjgwMzM3MDla
MGoxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlhMRYwFAYDVQQHEw1T
YW4gRnJhbmNpc2NvMQ0wCwYDVQQLEwRwZWVyMR8wHQYDVQQDExZwZWVyMC5vcmcy
LmV4YW1wbGUuY29tMFkwEwYHKoZIzj0CAQYIKoZIzj0DAQcDQgAEt4lTLAuzDRm0
4g/cHsw1603B8pUvX35Aciske9dRJBXlFUS2NDBd4mvtqlvBRQVTKAFu4L8P9C+P
JSbSlO9haaNNMEswDgYDVR0PAQH/BAQDAgeAMAwGA1UdEwEB/wQCMAAwKwYDVR0j
BCQwIoAgY+8FVhpy2+cdbjPQhM7db+sxI8YSJyFmYEFfv/qg2BowCgYIKoZIzj0E
AwIDRwAwRAIgWn6JQhLZCLMX46tZWRG3tzTwh2smyTL4PTwUznqI63ACID3drmjG
DqkCmDra/7bjgFvX4x6xWmVfuS7DnSqrrJdW
-----END CERTIFICATE-----
2018-07-03 02:16:34.507 UTC [cauthdsl] func1 -> DEBU 856 0xc42000f508 gate 1530584194507835772 evaluation starts
2018-07-03 02:16:34.507 UTC [cauthdsl] func2 -> DEBU 857 0xc42000f508 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.507 UTC [cauthdsl] func2 -> DEBU 858 0xc42000f508 processing identity 0 with bytes of 0a074f7267324d535012a6062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434a7a4343416336674177494241674951594a316e57676a6a464b32514575695830394d502f6a414b42676771686b6a4f50515144416a427a4d5173770a435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e5532467549455a790a5957356a61584e6a627a455a4d4263474131554543684d5162334a6e4d69356c654746746347786c4c6d4e76625445634d426f474131554541784d54593245750a62334a6e4d69356c654746746347786c4c6d4e7662544165467730784f4441314d7a45774d7a4d334d446c61467730794f4441314d6a67774d7a4d334d446c610a4d476f78437a414a42674e5642415954416c56544d524d77455159445651514945777044595778705a6d3979626d6c684d5259774641594456515148457731540a59573467526e4a68626d4e7063324e764d513077437759445651514c457752775a5756794d523877485159445651514445785a775a5756794d433576636d63790a4c6d56345957317762475575593239744d466b77457759484b6f5a497a6a3043415159494b6f5a497a6a3044415163445167414574346c544c41757a44526d300a34672f63487377313630334238705576583335416369736b653964524a42586c465553324e444264346d7674716c7642525156544b414675344c385039432b500a4a5362536c4f396861614e4e4d45737744675944565230504151482f42415144416765414d41774741315564457745422f7751434d4141774b7759445652306a0a42435177496f4167592b384656687079322b6364626a5051684d3764622b7378493859534a79466d59454666762f716732426f77436759494b6f5a497a6a30450a417749445277417752414967576e364a51684c5a434c4d583436745a57524733747a54776832736d79544c34505477557a6e71493633414349443364726d6a470a44716b436d4472612f37626a6746765834783678576d5666755337446e537172724a64570a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.507 UTC [msp] SatisfiesPrincipal -> DEBU 859 Checking if identity satisfies MEMBER role for Org2MSP
2018-07-03 02:16:34.507 UTC [msp] Validate -> DEBU 85a MSP Org2MSP validating identity
2018-07-03 02:16:34.507 UTC [msp] getCertificationChain -> DEBU 85b MSP Org2MSP getting certification chain
2018-07-03 02:16:34.508 UTC [cauthdsl] func2 -> DEBU 85c 0xc42000f508 principal matched by identity 0
2018-07-03 02:16:34.508 UTC [msp/identity] Verify -> DEBU 85d Verify: digest = 00000000  66 61 32 f5 ba 5a b5 09  52 1d 96 75 aa e7 c9 58  |fa2..Z..R..u...X|
00000010  86 50 5b 37 8f a9 09 46  b0 8f 25 a6 95 b5 1b 51  |.P[7...F..%....Q|
2018-07-03 02:16:34.508 UTC [msp/identity] Verify -> DEBU 85e Verify: sig = 00000000  30 44 02 20 7c 2a ff 3d  ee 03 db 71 c4 19 63 c7  |0D. |*.=...q..c.|
00000010  9f 8a ae 35 5f 92 be 6f  63 e0 50 dc e1 63 ff d2  |...5_..oc.P..c..|
00000020  8a 18 ca 9d 02 20 72 af  fb 12 82 41 be c0 51 3b  |..... r....A..Q;|
00000030  0d 7b 9f dc 09 ca 88 25  05 34 71 dc 1f 20 cd 51  |.{.....%.4q.. .Q|
00000040  bc 33 58 04 97 aa                                 |.3X...|
2018-07-03 02:16:34.508 UTC [cauthdsl] func2 -> DEBU 85f 0xc42000f508 principal evaluation succeeds for identity 0
2018-07-03 02:16:34.508 UTC [cauthdsl] func1 -> DEBU 860 0xc42000f508 gate 1530584194507835772 evaluation succeeds
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 861 Signature set satisfies policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 862 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 863 Signature set satisfies policy /Channel/Application/Readers
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 864 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 865 Signature set satisfies policy /Channel/Readers
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 866 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers
2018-07-03 02:16:34.508 UTC [common/deliver] deliverBlocks -> DEBU 867 [channel: mychannel] Delivering block for (0xc420a96660) for 172.18.0.2:55226
2018-07-03 02:16:34.507 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 84e Remaining bytes=[17533], Going to peek [8] bytes
2018-07-03 02:16:34.508 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 868 Returning blockbytes - length=[17530], placementInfo={fileNum=[0], startOffset=[33125], bytesOffset=[33128]}
2018-07-03 02:16:34.508 UTC [fsblkstorage] nextBlockBytesAndPlacementInfo -> DEBU 869 blockbytes [17530] read from file [0]
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 86a == Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers ==
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 86b This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 86c == Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers ==
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 86d This is an implicit meta policy, it will trigger other policy evaluations, whose failures may be benign
2018-07-03 02:16:34.508 UTC [policies] Evaluate -> DEBU 86f == Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers ==
2018-07-03 02:16:34.508 UTC [msp] DeserializeIdentity -> INFO 870 Obtaining identity
2018-07-03 02:16:34.508 UTC [msp/identity] newIdentity -> DEBU 871 Creating identity instance for cert -----BEGIN CERTIFICATE-----
MIICKDCCAc+gAwIBAgIRAJtiEX85zYg6nslTt+qSSbgwCgYIKoZIzj0EAwIwczEL
MAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG
cmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh
Lm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5
WjBqMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN
U2FuIEZyYW5jaXNjbzENMAsGA1UECxMEcGVlcjEfMB0GA1UEAxMWcGVlcjAub3Jn
MS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABGgf4MnrbbDo
iVuZtmSyeLTZoI8AkYnDFT62fmL7SkSbpFvS6NgVVzzIqjvk7neds7lb7GQkZg7Y
YAPe9UxKxtijTTBLMA4GA1UdDwEB/wQEAwIHgDAMBgNVHRMBAf8EAjAAMCsGA1Ud
IwQkMCKAIFkH9AopcBRzntYYFld3Y+Mxd6D75WjeKlZ9sOsjVz8TMAoGCCqGSM49
BAMCA0cAMEQCIDdYm3WxVcK61cl3u0Wt5M/twcmqoSIJ6IeoDEBJHkMtAiBkucyT
80H7y+3ojQYsd6Wi8fUvh6+h9NkFKSoWsgMDRw==
-----END CERTIFICATE-----
2018-07-03 02:16:34.508 UTC [cauthdsl] func1 -> DEBU 872 0xc420800040 gate 1530584194508919108 evaluation starts
2018-07-03 02:16:34.508 UTC [cauthdsl] func2 -> DEBU 873 0xc420800040 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.509 UTC [cauthdsl] func2 -> DEBU 874 0xc420800040 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b44434341632b674177494241674952414a7469455838357a5967366e736c54742b715353626777436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a45755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a45755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42714d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a454e4d4173474131554543784d456347566c636a45664d4230474131554541784d576347566c636a417562334a6e0a4d53356c654746746347786c4c6d4e766254425a4d424d4742797147534d34394167454743437147534d3439417745484130494142476766344d6e726262446f0a6956755a746d5379654c545a6f4938416b596e4446543632666d4c37536b536270467653364e6756567a7a49716a766b376e656473376c623747516b5a6737590a594150653955784b7874696a5454424c4d41344741315564447745422f775145417749486744414d42674e5648524d4241663845416a41414d437347413155640a4977516b4d434b4149466b4839416f706342527a6e745959466c6433592b4d786436443735576a654b6c5a39734f736a567a38544d416f4743437147534d34390a42414d43413063414d455143494464596d33577856634b3631636c3375305774354d2f7477636d716f53494a3649656f4445424a486b4d744169426b756379540a38304837792b336f6a515973643657693866557668362b68394e6b464b536f5773674d4452773d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.509 UTC [cauthdsl] func2 -> DEBU 875 0xc420800040 identity 0 does not satisfy principal: the identity is a member of a different MSP (expected Org2MSP, got Org1MSP)
2018-07-03 02:16:34.509 UTC [cauthdsl] func2 -> DEBU 876 0xc420800040 principal evaluation fails
2018-07-03 02:16:34.509 UTC [cauthdsl] func1 -> DEBU 877 0xc420800040 gate 1530584194508919108 evaluation fails
2018-07-03 02:16:34.509 UTC [policies] Evaluate -> DEBU 878 Signature set did not satisfy policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.509 UTC [policies] Evaluate -> DEBU 879 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org2MSP/Readers
2018-07-03 02:16:34.509 UTC [policies] Evaluate -> DEBU 87a == Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Readers ==
2018-07-03 02:16:34.509 UTC [cauthdsl] func1 -> DEBU 87b 0xc4208000b0 gate 1530584194509409781 evaluation starts
2018-07-03 02:16:34.509 UTC [cauthdsl] func2 -> DEBU 87c 0xc4208000b0 signed by 0 principal evaluation starts (used [false])
2018-07-03 02:16:34.509 UTC [cauthdsl] func2 -> DEBU 87d 0xc4208000b0 processing identity 0 with bytes of 0a074f7267314d535012aa062d2d2d2d2d424547494e2043455254494649434154452d2d2d2d2d0a4d4949434b44434341632b674177494241674952414a7469455838357a5967366e736c54742b715353626777436759494b6f5a497a6a304541774977637a454c0a4d416b474131554542684d4356564d78457a415242674e5642416754436b4e6862476c6d62334a7561574578466a415542674e564241635444564e68626942470a636d467559326c7a593238784754415842674e5642416f54454739795a7a45755a586868625842735a53356a623230784844416142674e5642414d5445324e680a4c6d39795a7a45755a586868625842735a53356a623230774868634e4d5467774e544d784d444d7a4e7a41355768634e4d6a67774e5449344d444d7a4e7a41350a576a42714d517377435159445651514745774a56557a45544d4245474131554543424d4b5132467361575a76636d3570595445574d4251474131554542784d4e0a5532467549455a795957356a61584e6a627a454e4d4173474131554543784d456347566c636a45664d4230474131554541784d576347566c636a417562334a6e0a4d53356c654746746347786c4c6d4e766254425a4d424d4742797147534d34394167454743437147534d3439417745484130494142476766344d6e726262446f0a6956755a746d5379654c545a6f4938416b596e4446543632666d4c37536b536270467653364e6756567a7a49716a766b376e656473376c623747516b5a6737590a594150653955784b7874696a5454424c4d41344741315564447745422f775145417749486744414d42674e5648524d4241663845416a41414d437347413155640a4977516b4d434b4149466b4839416f706342527a6e745959466c6433592b4d786436443735576a654b6c5a39734f736a567a38544d416f4743437147534d34390a42414d43413063414d455143494464596d33577856634b3631636c3375305774354d2f7477636d716f53494a3649656f4445424a486b4d744169426b756379540a38304837792b336f6a515973643657693866557668362b68394e6b464b536f5773674d4452773d3d0a2d2d2d2d2d454e442043455254494649434154452d2d2d2d2d0a
2018-07-03 02:16:34.509 UTC [msp] SatisfiesPrincipal -> DEBU 87e Checking if identity satisfies MEMBER role for Org1MSP
2018-07-03 02:16:34.509 UTC [msp] Validate -> DEBU 87f MSP Org1MSP validating identity
2018-07-03 02:16:34.508 UTC [fsblkstorage] waitForBlock -> DEBU 86e Going to wait for newer blocks. maxAvailaBlockNumber=[2], waitForBlockNum=[3]
2018-07-03 02:16:34.509 UTC [msp] getCertificationChain -> DEBU 880 MSP Org1MSP getting certification chain
2018-07-03 02:16:34.509 UTC [cauthdsl] func2 -> DEBU 881 0xc4208000b0 principal matched by identity 0
2018-07-03 02:16:34.509 UTC [msp/identity] Verify -> DEBU 882 Verify: digest = 00000000  50 db 9a 16 fa d5 f2 40  0e 28 23 28 eb 6d 12 be  |P......@.(#(.m..|
00000010  1e 88 9f 8c 1b 55 f7 a0  90 b3 d7 14 1e 4c 3f 0f  |.....U.......L?.|
2018-07-03 02:16:34.509 UTC [msp/identity] Verify -> DEBU 883 Verify: sig = 00000000  30 45 02 21 00 b7 20 ad  28 a2 ed 0e d6 fb 92 a9  |0E.!.. .(.......|
00000010  c5 45 05 5b d9 08 b6 33  5d 95 0f 6c e7 a7 6b 5a  |.E.[...3]..l..kZ|
00000020  35 0d f1 5e e9 02 20 7c  1c 0e 66 eb c4 88 f9 6b  |5..^.. |..f....k|
00000030  d5 28 02 2f 9d 19 79 09  f6 93 1f 7c aa b4 63 38  |.(./..y....|..c8|
00000040  16 3e bb 2d 8f 56 cb                              |.>.-.V.|
2018-07-03 02:16:34.510 UTC [cauthdsl] func2 -> DEBU 884 0xc4208000b0 principal evaluation succeeds for identity 0
2018-07-03 02:16:34.510 UTC [cauthdsl] func1 -> DEBU 885 0xc4208000b0 gate 1530584194509409781 evaluation succeeds
2018-07-03 02:16:34.510 UTC [policies] Evaluate -> DEBU 886 Signature set satisfies policy /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.510 UTC [policies] Evaluate -> DEBU 887 == Done Evaluating *cauthdsl.policy Policy /Channel/Application/Org1MSP/Readers
2018-07-03 02:16:34.510 UTC [policies] Evaluate -> DEBU 888 Signature set satisfies policy /Channel/Application/Readers
2018-07-03 02:16:34.510 UTC [policies] Evaluate -> DEBU 889 == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Application/Readers
2018-07-03 02:16:34.510 UTC [policies] Evaluate -> DEBU 88a Signature set satisfies policy /Channel/Readers
2018-07-03 02:16:34.510 UTC [policies] Evaluate -> DEBU 88b == Done Evaluating *policies.implicitMetaPolicy Policy /Channel/Readers
2018-07-03 02:16:34.510 UTC [common/deliver] deliverBlocks -> DEBU 88c [channel: mychannel] Delivering block for (0xc420c243c0) for 172.18.0.6:54766
2018-07-03 02:16:34.531 UTC [fsblkstorage] waitForBlock -> DEBU 88d Going to wait for newer blocks. maxAvailaBlockNumber=[2], waitForBlockNum=[3]


