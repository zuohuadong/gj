# 内部加速

```
echo 'Acquire::HTTP::Proxy "http://10.0.1.212:3142";' >> /etc/apt/apt.conf.d/proxy \
 && echo 'Acquire::HTTPS::Proxy "false";' >> /etc/apt/apt.conf.d/proxy
```
