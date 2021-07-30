```shell
kali$ date +%s.%N && nmap -A -p- 172.16.174.0/24 && date +%s.%N
1627491670.805018320
Starting Nmap 7.91 ( https://nmap.org ) at 2021-07-28 12:20 UTC
Nmap scan report for 172.16.174.129
Host is up (0.000056s latency).
Not shown: 65534 closed ports
PORT   STATE SERVICE VERSION
80/tcp open  http    Apache httpd 2.4.25 ((Debian))
| http-cookie-flags: 
|   /: 
|     PHPSESSID: 
|_      httponly flag not set
| http-robots.txt: 1 disallowed entry 
|_/
|_http-server-header: Apache/2.4.25 (Debian)
| http-title: Login :: Damn Vulnerable Web Application (DVWA) v1.10 *Develop...
|_Requested resource was login.php
MAC Address: 02:42:AC:11:00:03 (Unknown)
Device type: general purpose
Running: Linux 4.X|5.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5
OS details: Linux 4.15 - 5.6
Network Distance: 1 hop

TRACEROUTE
HOP RTT     ADDRESS
1   0.06 ms 172.16.174.129

Nmap scan report for 172.16.174.131
Host is up (0.000019s latency).
Not shown: 65534 closed ports
PORT     STATE SERVICE VERSION
3000/tcp open  ppp?
| fingerprint-strings: 
|   DNSStatusRequestTCP, DNSVersionBindReqTCP, Help, NCP, RPCCheck, RTSPRequest: 
|     HTTP/1.1 400 Bad Request
|     Connection: close
|   GetRequest: 
|     HTTP/1.1 200 OK
|     Access-Control-Allow-Origin: *
|     X-Content-Type-Options: nosniff
|     X-Frame-Options: SAMEORIGIN
|     Feature-Policy: payment 'self'
|     Accept-Ranges: bytes
|     Cache-Control: public, max-age=0
|     Last-Modified: Wed, 28 Jul 2021 09:42:51 GMT
|     ETag: W/"784-17aec7ecdb2"
|     Content-Type: text/html; charset=UTF-8
|     Content-Length: 1924
|     Vary: Accept-Encoding
|     Date: Wed, 28 Jul 2021 12:20:25 GMT
|     Connection: close
|     <!--
|     Copyright (c) 2014-2021 Bjoern Kimminich.
|     SPDX-License-Identifier: MIT
|     <!doctype html>
|     <html lang="en">
|     <head>
|     <meta charset="utf-8">
|     <title>OWASP Juice Shop</title>
|     <meta name="description" content="Probably the most modern and sophisticated insecure web application">
|     <meta name="viewport" content="width=device-width, initial-scale=1">
|     <link id="favicon" rel="icon" type="image/x-icon" href="assets/public/favicon_js.ico">
|     <link rel="stylesheet" type
|   HTTPOptions: 
|     HTTP/1.1 204 No Content
|     Access-Control-Allow-Origin: *
|     Access-Control-Allow-Methods: GET,HEAD,PUT,PATCH,POST,DELETE
|     Vary: Access-Control-Request-Headers
|     Content-Length: 0
|     Date: Wed, 28 Jul 2021 12:20:25 GMT
|_    Connection: close
1 service unrecognized despite returning data. If you know the service/version, please submit the following fingerprint at https://nmap.org/cgi-bin/submit.cgi?new-service :
SF-Port3000-TCP:V=7.91%I=7%D=7/28%Time=61014B89%P=x86_64-pc-linux-gnu%r(Ge
SF:tRequest,923,"HTTP/1\.1\x20200\x20OK\r\nAccess-Control-Allow-Origin:\x2
SF:0\*\r\nX-Content-Type-Options:\x20nosniff\r\nX-Frame-Options:\x20SAMEOR
SF:IGIN\r\nFeature-Policy:\x20payment\x20'self'\r\nAccept-Ranges:\x20bytes
SF:\r\nCache-Control:\x20public,\x20max-age=0\r\nLast-Modified:\x20Wed,\x2
SF:028\x20Jul\x202021\x2009:42:51\x20GMT\r\nETag:\x20W/\"784-17aec7ecdb2\"
SF:\r\nContent-Type:\x20text/html;\x20charset=UTF-8\r\nContent-Length:\x20
SF:1924\r\nVary:\x20Accept-Encoding\r\nDate:\x20Wed,\x2028\x20Jul\x202021\
SF:x2012:20:25\x20GMT\r\nConnection:\x20close\r\n\r\n<!--\n\x20\x20~\x20Co
SF:pyright\x20\(c\)\x202014-2021\x20Bjoern\x20Kimminich\.\n\x20\x20~\x20SP
SF:DX-License-Identifier:\x20MIT\n\x20\x20-->\n\n<!doctype\x20html>\n<html
SF:\x20lang=\"en\">\n<head>\n\x20\x20<meta\x20charset=\"utf-8\">\n\x20\x20
SF:<title>OWASP\x20Juice\x20Shop</title>\n\x20\x20<meta\x20name=\"descript
SF:ion\"\x20content=\"Probably\x20the\x20most\x20modern\x20and\x20sophisti
SF:cated\x20insecure\x20web\x20application\">\n\x20\x20<meta\x20name=\"vie
SF:wport\"\x20content=\"width=device-width,\x20initial-scale=1\">\n\x20\x2
SF:0<link\x20id=\"favicon\"\x20rel=\"icon\"\x20type=\"image/x-icon\"\x20hr
SF:ef=\"assets/public/favicon_js\.ico\">\n\x20\x20<link\x20rel=\"styleshee
SF:t\"\x20type")%r(Help,2F,"HTTP/1\.1\x20400\x20Bad\x20Request\r\nConnecti
SF:on:\x20close\r\n\r\n")%r(NCP,2F,"HTTP/1\.1\x20400\x20Bad\x20Request\r\n
SF:Connection:\x20close\r\n\r\n")%r(HTTPOptions,EA,"HTTP/1\.1\x20204\x20No
SF:\x20Content\r\nAccess-Control-Allow-Origin:\x20\*\r\nAccess-Control-All
SF:ow-Methods:\x20GET,HEAD,PUT,PATCH,POST,DELETE\r\nVary:\x20Access-Contro
SF:l-Request-Headers\r\nContent-Length:\x200\r\nDate:\x20Wed,\x2028\x20Jul
SF:\x202021\x2012:20:25\x20GMT\r\nConnection:\x20close\r\n\r\n")%r(RTSPReq
SF:uest,2F,"HTTP/1\.1\x20400\x20Bad\x20Request\r\nConnection:\x20close\r\n
SF:\r\n")%r(RPCCheck,2F,"HTTP/1\.1\x20400\x20Bad\x20Request\r\nConnection:
SF:\x20close\r\n\r\n")%r(DNSVersionBindReqTCP,2F,"HTTP/1\.1\x20400\x20Bad\
SF:x20Request\r\nConnection:\x20close\r\n\r\n")%r(DNSStatusRequestTCP,2F,"
SF:HTTP/1\.1\x20400\x20Bad\x20Request\r\nConnection:\x20close\r\n\r\n");
MAC Address: 02:42:AC:11:00:04 (Unknown)
Device type: general purpose
Running: Linux 4.X|5.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5
OS details: Linux 4.15 - 5.6
Network Distance: 1 hop

TRACEROUTE
HOP RTT     ADDRESS
1   0.02 ms 172.16.174.131

Nmap scan report for 172.16.174.130
Host is up (0.000035s latency).
Not shown: 65533 closed ports
PORT     STATE SERVICE VERSION
80/tcp   open  http    Apache httpd 2.4.7 ((Ubuntu))
| http-cookie-flags: 
|   /: 
|     PHPSESSID: 
|_      httponly flag not set
| http-git: 
|   172.16.174.130:80/.git/
|     Git repository found!
|     Repository description: Unnamed repository; edit this file 'description' to name the...
|     Remotes:
|_      https://github.com/fermayo/hello-world-lamp.git
| http-robots.txt: 5 disallowed entries 
|_/ /admin/ /documents/ /images/ /passwords/
|_http-server-header: Apache/2.4.7 (Ubuntu)
| http-title: bWAPP - Login
|_Requested resource was login.php
3306/tcp open  mysql   MySQL (blocked - too many connection errors)
MAC Address: 02:42:AC:11:00:05 (Unknown)
Device type: general purpose
Running: Linux 4.X|5.X
OS CPE: cpe:/o:linux:linux_kernel:4 cpe:/o:linux:linux_kernel:5
OS details: Linux 4.15 - 5.6
Network Distance: 1 hop

TRACEROUTE
HOP RTT     ADDRESS
1   0.04 ms 172.16.174.130

OS and Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 256 IP addresses (3 hosts up) scanned in 43.65 seconds
1627491714.492984948
```

