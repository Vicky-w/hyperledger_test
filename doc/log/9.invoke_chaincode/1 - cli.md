Sending invoke transaction on peer0.org1...
CORE_PEER_TLS_ROOTCERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/ca.crt
CORE_PEER_TLS_KEY_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.key
CORE_PEER_LOCALMSPID=Org1MSP
CORE_VM_ENDPOINT=unix:///host/var/run/docker.sock
CORE_PEER_TLS_CERT_FILE=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/peers/peer0.org1.example.com/tls/server.crt
CORE_PEER_TLS_ENABLED=true
CORE_PEER_MSPCONFIGPATH=/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp
CORE_PEER_ID=cli
CORE_LOGGING_LEVEL=DEBUG
CORE_PEER_ADDRESS=peer0.org1.example.com:7051
+ peer chaincode invoke -o orderer.example.com:7050 --tls true --cafile /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/ordererOrganizations/example.com/orderers/orderer.example.com/msp/tlscacerts/tlsca.example.com-cert.pem -C mychannel -n mycc -c '{"Args":["invoke","a","b","10"]}'
+ res=0
+ set +x
2018-07-03 05:22:44.633 UTC [msp] GetLocalMSP -> DEBU 001 Returning existing local MSP
2018-07-03 05:22:44.633 UTC [msp] GetDefaultSigningIdentity -> DEBU 002 Obtaining default signing identity
2018-07-03 05:22:44.639 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 003 Using default escc
2018-07-03 05:22:44.639 UTC [chaincodeCmd] checkChaincodeCmdParams -> INFO 004 Using default vscc
2018-07-03 05:22:44.639 UTC [chaincodeCmd] getChaincodeSpec -> DEBU 005 java chaincode enabled
2018-07-03 05:22:44.639 UTC [msp/identity] Sign -> DEBU 006 Sign: plaintext: 0ABF070A6708031A0C08A490ECD90510...696E766F6B650A01610A01620A023130 
2018-07-03 05:22:44.639 UTC [msp/identity] Sign -> DEBU 007 Sign: digest: 729D6D0E7B9CAB0917DD909A47EBE3000DCD1C438AAA0A5C42DCF743ABE8455C 
2018-07-03 05:22:44.658 UTC [msp/identity] Sign -> DEBU 008 Sign: plaintext: 0ABF070A6708031A0C08A490ECD90510...3A56D20FF88075341735087FA2D26038 
2018-07-03 05:22:44.658 UTC [msp/identity] Sign -> DEBU 009 Sign: digest: 7B4A8D6FD3D1D40AF53F102B5B6D10B3F843B4B57120058637E72A473B79A973 
2018-07-03 05:22:44.662 UTC [chaincodeCmd] chaincodeInvokeOrQuery -> DEBU 00a ESCC invoke result: version:1 response:<status:200 message:"OK" > payload:"\n \3160\244\023\257jqL\362r\177\214s\224\014w\214\251\0338!\250\271Q\331R\023\215\006\344k,\022Y\nE\022\024\n\004lscc\022\014\n\n\n\004mycc\022\002\010\003\022-\n\004mycc\022%\n\007\n\001a\022\002\010\007\n\007\n\001b\022\002\010\007\032\007\n\001a\032\00250\032\010\n\001b\032\003250\032\003\010\310\001\"\013\022\004mycc\032\0031.0" endorsement:<endorser:"\n\007Org1MSP\022\252\006-----BEGIN CERTIFICATE-----\nMIICKDCCAc+gAwIBAgIRAJtiEX85zYg6nslTt+qSSbgwCgYIKoZIzj0EAwIwczEL\nMAkGA1UEBhMCVVMxEzARBgNVBAgTCkNhbGlmb3JuaWExFjAUBgNVBAcTDVNhbiBG\ncmFuY2lzY28xGTAXBgNVBAoTEG9yZzEuZXhhbXBsZS5jb20xHDAaBgNVBAMTE2Nh\nLm9yZzEuZXhhbXBsZS5jb20wHhcNMTgwNTMxMDMzNzA5WhcNMjgwNTI4MDMzNzA5\nWjBqMQswCQYDVQQGEwJVUzETMBEGA1UECBMKQ2FsaWZvcm5pYTEWMBQGA1UEBxMN\nU2FuIEZyYW5jaXNjbzENMAsGA1UECxMEcGVlcjEfMB0GA1UEAxMWcGVlcjAub3Jn\nMS5leGFtcGxlLmNvbTBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABGgf4MnrbbDo\niVuZtmSyeLTZoI8AkYnDFT62fmL7SkSbpFvS6NgVVzzIqjvk7neds7lb7GQkZg7Y\nYAPe9UxKxtijTTBLMA4GA1UdDwEB/wQEAwIHgDAMBgNVHRMBAf8EAjAAMCsGA1Ud\nIwQkMCKAIFkH9AopcBRzntYYFld3Y+Mxd6D75WjeKlZ9sOsjVz8TMAoGCCqGSM49\nBAMCA0cAMEQCIDdYm3WxVcK61cl3u0Wt5M/twcmqoSIJ6IeoDEBJHkMtAiBkucyT\n80H7y+3ojQYsd6Wi8fUvh6+h9NkFKSoWsgMDRw==\n-----END CERTIFICATE-----\n" signature:"0D\002 kB\272\304\271VG\256\231J5\336\016\3118@nP\345-7\220\365\226\255\247#\353\247\304\002\304\002 T\237i\303\024\365\221\035\377s\000\340\203\245A[:V\322\017\370\200u4\0275\010\177\242\322`8" > 
2018-07-03 05:22:44.662 UTC [chaincodeCmd] chaincodeInvokeOrQuery -> INFO 00b Chaincode invoke successful. result: status:200 
2018-07-03 05:22:44.662 UTC [main] main -> INFO 00c Exiting.....

