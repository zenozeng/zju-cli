# ZJU CLI Tools

** Note: This repo was moved to https://github.com/QSCTech/zjunet. **

zju wlan

zju vpn -c // config

zju vpn // connect

if ip 10.189.xxx.xxx => zjuwlan => set up routes
else => set up default routes

zju vpn --zjuwlan => is zjuwlan

zju vpn -d // disconnect

https://github.com/zenozeng/zju-cli

## Usage

```
sudo zju dns
```
自动测试 DNS 可用性，并修改 resolv.conf

## 使用场景

### zju wlan

虽然已经有了很好用的浏览器在线认证以及自动登陆插件。
但是有时候比如不想开浏览器只想开终端的时候。
有时候浏览器开了全局代理，访问 net.zju.edu.cn 还要切换很麻烦。
这个时候直接敲一条命令会更方便一些。

## Features

- 不打包，以独立脚本形式存在

### VPN

- 按照 ip 自动判断所处网络是否 zjuwlan，自动设置内网静态路由

### DNS

- 自动判断 dns 可用性，在官方 dns 挂掉后切换至备用 dns

## Links

- https://github.com/visionmedia/commander.js

- https://github.com/visionmedia/commander

- [Bash Shell中Shift用法](http://www.chengyongxu.com/blog/bash-shell%E4%B8%ADshift%E7%94%A8%E6%B3%95/)

- [Unix - Shell Loop Control](http://www.tutorialspoint.com/unix/unix-loop-control.htm)
