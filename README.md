# ZJU CLI Tools

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
