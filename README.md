# VPS ROOT 用户密码登录、自定义SSH端口一键脚本

支持CentOS、Debian、Ubuntu等系统的各大厂商的VPS。一个命令，修改登录方式为root+密码、自定义SSH端口

如对脚本不放心，可使用此沙箱先测一遍再使用：https://killercoda.com/playgrounds/scenario/ubuntu

## 使用方法

首先使用`sudo -i`登录root用户（如果登录用户为非root时），然后执行以下命令

```shell
wget -N --no-check-certificate https://raw.githubusercontents.com/hoontoo/root-kay/master/root.sh && bash root.sh
```

最后设置SSH端口和密码即可

重启服务器
reboot

连接CF WARP为服务器添加IPv4/IPv6网络
wget -N https://raw.githubusercontent.com/fscarmen/warp/main/menu.sh && bash menu.sh [option] [lisence]

再次运行
warp [option] [lisence]

设置warp Teams的专属通道
文件管理器打开 /etc/wireguard 目录，修改warp 文件

Private key: vWDyz6VK/fK2IalsG02wGtNdPuhQ3n4+iBaXpT30aZA=
Public key: bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo= 
Address IPv4: 172.16.0.2/32 
Address IPv6: fd01:5ca1:ab1e:8a54:563e:ddf3:ffa4:9ebc/128 

x-ui修改面版
wget -N https://raw.githubusercontents.com/hoontoo/x-ui-yg/main/install.sh && bash install.sh

