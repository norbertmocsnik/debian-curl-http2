# debian-curl-http2
Docker image that builds curl with nghttp2 &amp; OpenSSL 1.0.2 in debian:jessie.

```
# curl --version
curl 7.56.1 (x86_64-pc-linux-gnu) libcurl/7.56.1 OpenSSL/1.0.2l zlib/1.2.8 libssh2/1.4.3 nghttp2/1.27.0
Release-Date: 2017-10-23
Protocols: file ftp ftps http https scp sftp 
Features: AsynchDNS IPv6 Largefile NTLM NTLM_WB SSL libz TLS-SRP HTTP2 UnixSockets HTTPS-proxy 
```

Primarily built for connecting to Apple Push Notification Service (APNS) through HTTP/2.

See https://hub.docker.com/r/norbertm/debian-curl-http2/
