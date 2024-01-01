```
$ curl https://verson.vercel.app -I
HTTP/2 200 
accept-ranges: bytes
access-control-allow-origin: *
age: 157
alt-svc: webteleport="k1s.io:443"
cache-control: public, max-age=0, must-revalidate
content-disposition: inline
content-type: text/html; charset=utf-8
customkey: customvalue
date: Mon, 01 Jan 2024 11:06:52 GMT
etag: "b37786e832cdd640d20948d021c188f8"
server: Vercel
strict-transport-security: max-age=63072000; includeSubDomains; preload
x-vercel-cache: HIT
x-vercel-id: pdx1::tgwkj-1704107212877-4f9d3d302e4f
content-length: 13
```

```
$ ufo gos https://verson.vercel.app
2024/01/01 11:04:46 utils.go:44: INFO 🛸 listening on https://2.k1s.io
2024/01/01 11:04:46 utils.go:47: INFO 🔓 publicly accessible without a password
45.77.173.40 - - [01/Jan/2024:11:04:54 +0000] "GET / HTTP/1.1" 200 86
45.77.173.40 - - [01/Jan/2024:11:04:59 +0000] "GET /favicon.ico HTTP/1.1" 404 43
```
