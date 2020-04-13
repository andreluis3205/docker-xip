## docker-xip

This is a fork of the [xip-pdns](https://github.com/basecamp/xip-pdns) project. This docker will setup a pdns pipe backend,
copy over the xip pdns script, and launch the pipe backend.

Example run:
```
docker run -p 53:53/udp -e "XIP_DOMAIN=xip.mydomain.com" --name=xip honzahommer/xip
```

#### Environment variables
```
XIP_DOMAIN
XIP_ADMIN
XIP_ROOT_ADDRESSES
XIP_NS_ADDRESSES
XIP_NS_SERVERS
XIP_TTL
```
