# Graftor Stealer Loader

# Protocols:
HTTP
DNS
TLS

# Ports:
80
53

# Sample:

```
POST /suicide HTTP/1.1
Accept: text/html, application/xml;q=0.9, application/xhtml+xml, image/png, image/jpeg, image/gif, image/x-xbitmap, */*;q=0.1
Accept-Language: ru-RU,ru;q=0.9,en;q=0.8
Accept-Charset: iso-8859-1, utf-8, utf-16, *;q=0.1
Accept-Encoding: deflate, gzip, x-gzip, identity, *;q=0
Content-Type: multipart/form-data; boundary=1BEF0A57BE110FD467A
Content-Length: 25
Host: 90551.prohoster.biz
Connection: Keep-Alive
Cache-Control: no-cache

--1BEF0A57BE110FD467A--
HTTP/1.1 200 OK
Server: nginx/1.14.1
Date: Sun, 28 Apr 2019 16:06:19 GMT
Content-Type: text/html; charset=UTF-8
Transfer-Encoding: chunked
Connection: keep-alive
X-Powered-By: PHP/5.4.16

9
ZmFsc2U=

0

POST /msgbox HTTP/1.1
Accept: text/html, application/xml;q=0.9, application/xhtml+xml, image/png, image/jpeg, image/gif, image/x-xbitmap, */*;q=0.1
Accept-Language: ru-RU,ru;q=0.9,en;q=0.8
Accept-Charset: iso-8859-1, utf-8, utf-16, *;q=0.1
Accept-Encoding: deflate, gzip, x-gzip, identity, *;q=0
Content-Type: multipart/form-data; boundary=1BEF0A57BE110FD467A
Content-Length: 25
Host: 90551.prohoster.biz
Connection: Keep-Alive
Cache-Control: no-cache

--1BEF0A57BE110FD467A--
HTTP/1.1 200 OK
Server: nginx/1.14.1
Date: Sun, 28 Apr 2019 16:06:21 GMT
Content-Type: text/html; charset=UTF-8
Transfer-Encoding: chunked
Connection: keep-alive
X-Powered-By: PHP/5.4.16

4
b2Zm
0

GET /selfDel HTTP/1.1
Accept: text/html, application/xml;q=0.9, application/xhtml+xml, image/png, image/jpeg, image/gif, image/x-xbitmap, */*;q=0.1
Accept-Language: ru-RU,ru;q=0.9,en;q=0.8
Accept-Charset: iso-8859-1, utf-8, utf-16, *;q=0.1
Accept-Encoding: deflate, gzip, x-gzip, identity, *;q=0
Host: 90551.prohoster.biz
Connection: Keep-Alive

HTTP/1.1 200 OK
Server: nginx/1.14.1
Date: Sun, 28 Apr 2019 16:06:21 GMT
Content-Type: text/html; charset=UTF-8
Transfer-Encoding: chunked
Connection: keep-alive
X-Powered-By: PHP/5.4.16

8
dHJ1ZQ==
0
```
