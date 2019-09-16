Q2
cURL is a computer software project providing a library and command-line tool for transferring data using various protocols. 
It was first released in 1997. The name stands for "Client URL". The original author and lead developer is the Swedish developer Daniel Stenberg.

Q3
Http Request
> GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*

Http Response
< HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Mon, 16 Sep 2019 09:32:33 GMT

Q4
< HTTP/1.1 301 Moved Permanently
< Date: Mon, 16 Sep 2019 09:59:05 GMT
< Server: Apache
< Location: https://www.jmarshall.com/easy/http/
< Content-Length: 244
< Content-Type: text/html; charset=iso-8859-1
<
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>301 Moved Permanently</title>
</head><body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="https://www.jmarshall.com/easy/http/">here</a>.</p>
</body></html>
* Connection #0 to host www.jmarshall.com left intact

Q5
< HTTP/1.1 301 Moved Permanently
< Server: nginx
< Date: Mon, 16 Sep 2019 10:10:28 GMT
< Content-Type: text/html
< Content-Length: 162
< Connection: keep-alive
< Location: https://duckduckgo.com/
< X-Frame-Options: SAMEORIGIN
< Content-Security-Policy: default-src https: blob: data: 'unsafe-inline' 'unsafe-eval'; frame-ancestors 'self'
< X-XSS-Protection: 1;mode=block
< X-Content-Type-Options: nosniff
< Referrer-Policy: origin
< Expect-CT: max-age=0
< Expires: Tue, 15 Sep 2020 10:10:28 GMT
< Cache-Control: max-age=31536000

Q6