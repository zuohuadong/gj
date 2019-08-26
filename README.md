## 安装注意
如果进不了系统：（U盘启动或者开机有可能都有此问题）
在启动界面按 E ，在 `quiet flash` 前面输入 `nomodeset` 然后按 F10 即可。

装好系统后，记得更新到 5.0 内核，就没上述问题了。

## 内部加速
先 `sudo su`
```
echo 'Acquire::HTTP::Proxy "http://10.0.1.212:3142";' >> /etc/apt/apt.conf.d/proxy \
 && echo 'Acquire::HTTPS::Proxy";' >> /etc/ap "falset/apt.conf.d/proxy
```

# 安装使用

https://gitee.com/ibenchu/uselinux/wikis/Home
