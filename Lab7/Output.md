> nmap -sV localhost
Starting Nmap 7.99 ( https://nmap.org ) at 2026-05-02 13:34 +0800
Nmap scan report for localhost (127.0.0.1)
Host is up (0.000024s latency).
Other addresses for localhost (not scanned): ::1
Not shown: 992 closed tcp ports (conn-refused)
PORT      STATE SERVICE       VERSION
88/tcp    open  tcpwrapped
445/tcp   open  microsoft-ds?
3000/tcp  open  ppp?
3306/tcp  open  mysql?
5000/tcp  open  rtsp
7000/tcp  open  rtsp
8021/tcp  open  tcpwrapped
10000/tcp open  tcpwrapped
4 services unrecognized despite returning data. If you know the service/version, please submit the following fingerprints at https://nmap.org/cgi-bin/submit.cgi?new-service :
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port3000-TCP:V=7.99%I=7%D=5/2%Time=69F58CD8%P=arm-apple-darwin25.3.0%r(
SF:GetRequest,126B3,"HTTP/1\.1\x20200\x20OK\r\nAccess-Control-Allow-Origin
SF::\x20\*\r\nX-Content-Type-Options:\x20nosniff\r\nX-Frame-Options:\x20SA
SF:MEORIGIN\r\nFeature-Policy:\x20payment\x20'self'\r\nX-Recruiting:\x20/#
SF:/jobs\r\nAccept-Ranges:\x20bytes\r\nCache-Control:\x20public,\x20max-ag
SF:e=0\r\nLast-Modified:\x20Sat,\x2002\x20May\x202026\x2005:32:25\x20GMT\r
SF:\nETag:\x20W/\"124fa-19de72c7b69\"\r\nContent-Type:\x20text/html;\x20ch
SF:arset=UTF-8\r\nContent-Length:\x2075002\r\nVary:\x20Accept-Encoding\r\n
SF:Date:\x20Sat,\x2002\x20May\x202026\x2005:34:16\x20GMT\r\nConnection:\x2
SF:0close\r\n\r\n<!--\n\x20\x20~\x20Copyright\x20\(c\)\x202014-2026\x20Bjo
SF:ern\x20Kimminich\x20&\x20the\x20OWASP\x20Juice\x20Shop\x20contributors\
SF:.\n\x20\x20~\x20SPDX-License-Identifier:\x20MIT\n\x20\x20-->\n\n<!docty
SF:pe\x20html>\n<html\x20lang=\"en\"\x20data-beasties-container>\n<head>\n
SF:\x20\x20<meta\x20charset=\"utf-8\">\n\x20\x20<title>OWASP\x20Juice\x20S
SF:hop</title>\n\x20\x20<meta\x20name=\"description\"\x20content=\"Probabl
SF:y\x20the\x20most\x20modern\x20and\x20sophisticated\x20insecure\x20web\x
SF:20application\">\n\x20\x20<meta\x20name=\"viewport\"\x20content=\"width
SF:=device-width,\x20initial-scale=1\">\n\x20\x20<link\x20id=\"favicon\"\x
SF:20rel=\"icon\"\x20")%r(Help,2F,"HTTP/1\.1\x20400\x20Bad\x20Request\r\nC
SF:onnection:\x20close\r\n\r\n")%r(NCP,2F,"HTTP/1\.1\x20400\x20Bad\x20Requ
SF:est\r\nConnection:\x20close\r\n\r\n")%r(HTTPOptions,EA,"HTTP/1\.1\x2020
SF:4\x20No\x20Content\r\nAccess-Control-Allow-Origin:\x20\*\r\nAccess-Cont
SF:rol-Allow-Methods:\x20GET,HEAD,PUT,PATCH,POST,DELETE\r\nVary:\x20Access
SF:-Control-Request-Headers\r\nContent-Length:\x200\r\nDate:\x20Sat,\x2002
SF:\x20May\x202026\x2005:34:16\x20GMT\r\nConnection:\x20close\r\n\r\n")%r(
SF:RTSPRequest,EA,"HTTP/1\.1\x20204\x20No\x20Content\r\nAccess-Control-All
SF:ow-Origin:\x20\*\r\nAccess-Control-Allow-Methods:\x20GET,HEAD,PUT,PATCH
SF:,POST,DELETE\r\nVary:\x20Access-Control-Request-Headers\r\nContent-Leng
SF:th:\x200\r\nDate:\x20Sat,\x2002\x20May\x202026\x2005:34:16\x20GMT\r\nCo
SF:nnection:\x20close\r\n\r\n");
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port3306-TCP:V=7.99%I=7%D=5/2%Time=69F58CD3%P=arm-apple-darwin25.3.0%r(
SF:NULL,4D,"I\0\0\0\n9\.5\.0\0J\x13\0\0eq\x0b\x1bK\^#\x05\0\xff\xff\xff\x0
SF:2\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\0\n\(zZC6v\?\]Lwa\0caching_sha2_passw
SF:ord\0")%r(GenericLines,72,"I\0\0\0\n9\.5\.0\0J\x13\0\0eq\x0b\x1bK\^#\x0
SF:5\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\0\n\(zZC6v\?\]Lwa\0
SF:caching_sha2_password\0!\0\0\x01\xff\x84\x04#08S01Got\x20packets\x20out
SF:\x20of\x20order")%r(GetRequest,72,"I\0\0\0\n9\.5\.0\0K\x13\0\0d-\.jv\x1
SF:c\n\"\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\0\x20E`aTv\r%%8
SF:/3\0caching_sha2_password\0!\0\0\x01\xff\x84\x04#08S01Got\x20packets\x2
SF:0out\x20of\x20order")%r(HTTPOptions,72,"I\0\0\0\n9\.5\.0\0L\x13\0\0\]GS
SF:f\x1fe\(c\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\0eD8nbA\x0f
SF:\+r6\)h\0caching_sha2_password\0!\0\0\x01\xff\x84\x04#08S01Got\x20packe
SF:ts\x20out\x20of\x20order")%r(RTSPRequest,72,"I\0\0\0\n9\.5\.0\0M\x13\0\
SF:0=x\x0bs\x1cs\x13\x07\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0
SF:\0\\\x11d\^\+X\x1f-\x0b\x11k\]\0caching_sha2_password\0!\0\0\x01\xff\x8
SF:4\x04#08S01Got\x20packets\x20out\x20of\x20order")%r(RPCCheck,72,"I\0\0\
SF:0\n9\.5\.0\0N\x13\0\x0011\x01\x1f;:!U\0\xff\xff\xff\x02\0\xff\xdf\x15\0
SF:\0\0\0\0\0\0\0\0\0=\^~\x0b>\*\x1ed\x1dvJs\0caching_sha2_password\0!\0\0
SF:\x01\xff\x84\x04#08S01Got\x20packets\x20out\x20of\x20order")%r(DNSVersi
SF:onBindReqTCP,72,"I\0\0\0\n9\.5\.0\0O\x13\0\0>G\x7f\x1bb\|Q\x06\0\xff\xf
SF:f\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\0\x06\x19\n9r\x0er%:\\iP\0cac
SF:hing_sha2_password\0!\0\0\x01\xff\x84\x04#08S01Got\x20packets\x20out\x2
SF:0of\x20order")%r(DNSStatusRequestTCP,72,"I\0\0\0\n9\.5\.0\0P\x13\0\0Y\?
SF:7d=Z;2\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\0q\x10&\[\x04d
SF:LG/#rT\0caching_sha2_password\0!\0\0\x01\xff\x84\x04#08S01Got\x20packet
SF:s\x20out\x20of\x20order")%r(Help,72,"I\0\0\0\n9\.5\.0\0Q\x13\0\0A\[;\x0
SF:2\x08P\tD\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0\x001gGS20e\
SF:x13\x1bd\[T\0caching_sha2_password\0!\0\0\x01\xff\x84\x04#08S01Got\x20p
SF:ackets\x20out\x20of\x20order")%r(SSLSessionReq,72,"I\0\0\0\n9\.5\.0\0R\
SF:x13\0\0UQ\x0f\x19N%g<\0\xff\xff\xff\x02\0\xff\xdf\x15\0\0\0\0\0\0\0\0\0
SF:\0\"hs`x'z9@fA\x04\0caching_sha2_password\0!\0\0\x01\xff\x84\x04#08S01G
SF:ot\x20packets\x20out\x20of\x20order");
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port5000-TCP:V=7.99%I=7%D=5/2%Time=69F58CD3%P=arm-apple-darwin25.3.0%r(
SF:GetRequest,90,"HTTP/1\.1\x20403\x20Forbidden\r\nContent-Length:\x200\r\
SF:nServer:\x20AirTunes/925\.5\.1\r\nX-Apple-ProcessingTime:\x200\r\nX-App
SF:le-RequestReceivedTimestamp:\x201516358703\r\n\r\n")%r(RTSPRequest,90,"
SF:RTSP/1\.0\x20403\x20Forbidden\r\nContent-Length:\x200\r\nServer:\x20Air
SF:Tunes/925\.5\.1\r\nX-Apple-ProcessingTime:\x200\r\nX-Apple-RequestRecei
SF:vedTimestamp:\x201516358711\r\n\r\n")%r(HTTPOptions,90,"HTTP/1\.1\x2040
SF:3\x20Forbidden\r\nContent-Length:\x200\r\nServer:\x20AirTunes/925\.5\.1
SF:\r\nX-Apple-ProcessingTime:\x200\r\nX-Apple-RequestReceivedTimestamp:\x
SF:201516363820\r\n\r\n")%r(FourOhFourRequest,90,"HTTP/1\.1\x20403\x20Forb
SF:idden\r\nContent-Length:\x200\r\nServer:\x20AirTunes/925\.5\.1\r\nX-App
SF:le-ProcessingTime:\x200\r\nX-Apple-RequestReceivedTimestamp:\x201516363
SF:823\r\n\r\n")%r(SIPOptions,A2,"RTSP/1\.0\x20403\x20Forbidden\r\nContent
SF:-Length:\x200\r\nServer:\x20AirTunes/925\.5\.1\r\nCSeq:\x2042\x20OPTION
SF:S\r\nX-Apple-ProcessingTime:\x200\r\nX-Apple-RequestReceivedTimestamp:\
SF:x201516363824\r\n\r\n");
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port7000-TCP:V=7.99%I=7%D=5/2%Time=69F58CD8%P=arm-apple-darwin25.3.0%r(
SF:RTSPRequest,90,"RTSP/1\.0\x20403\x20Forbidden\r\nContent-Length:\x200\r
SF:\nServer:\x20AirTunes/925\.5\.1\r\nX-Apple-ProcessingTime:\x200\r\nX-Ap
SF:ple-RequestReceivedTimestamp:\x201516358694\r\n\r\n")%r(GetRequest,90,"
SF:HTTP/1\.1\x20403\x20Forbidden\r\nContent-Length:\x200\r\nServer:\x20Air
SF:Tunes/925\.5\.1\r\nX-Apple-ProcessingTime:\x200\r\nX-Apple-RequestRecei
SF:vedTimestamp:\x201516363697\r\n\r\n")%r(HTTPOptions,90,"HTTP/1\.1\x2040
SF:3\x20Forbidden\r\nContent-Length:\x200\r\nServer:\x20AirTunes/925\.5\.1
SF:\r\nX-Apple-ProcessingTime:\x200\r\nX-Apple-RequestReceivedTimestamp:\x
SF:201516363707\r\n\r\n")%r(FourOhFourRequest,90,"HTTP/1\.1\x20403\x20Forb
SF:idden\r\nContent-Length:\x200\r\nServer:\x20AirTunes/925\.5\.1\r\nX-App
SF:le-ProcessingTime:\x200\r\nX-Apple-RequestReceivedTimestamp:\x201516363
SF:822\r\n\r\n")%r(SIPOptions,A2,"RTSP/1\.0\x20403\x20Forbidden\r\nContent
SF:-Length:\x200\r\nServer:\x20AirTunes/925\.5\.1\r\nCSeq:\x2042\x20OPTION
SF:S\r\nX-Apple-ProcessingTime:\x200\r\nX-Apple-RequestReceivedTimestamp:\
SF:x201516363823\r\n\r\n");

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 26.42 seconds