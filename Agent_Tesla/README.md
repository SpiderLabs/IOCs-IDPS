# Agent Tesla

# Links:
https://app.any.run/tasks/be91d210-8e84-49ac-9b4d-f49edc1eedb3/

# Protocols:
TCP
DNS
SMTP

# Ports:
80
53
587

# Sample:

```
220-wcp1.prored.es ESMTP Exim 4.92 #2 Tue, 09 Jul 2019 20:38:36 +0200 
220-We do not authorize the use of this system to transport unsolicited, 
220 and/or bulk e-mail.
EHLO User-PC
250-wcp1.prored.es Hello User-PC [185.183.107.227]
250-SIZE 52428800
250-8BITMIME
250-PIPELINING
250-AUTH PLAIN LOGIN
250-STARTTLS
250 HELP
STARTTLS
220 TLS go ahead



GET / HTTP/1.1
Host: checkip.amazonaws.com
Connection: Keep-Alive

HTTP/1.1 200 OK
Date: Tue, 09 Jul 2019 18:39:57 GMT
Server: lighttpd/1.4.41
Content-Length: 16
Connection: keep-alive

185.183.107.227
```
