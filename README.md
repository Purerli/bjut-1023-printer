# Hp1020-laserJet-1020 printer

打印机地址: **172.25.19.164**（一般不会改变，尽量不要关闭服务器，服务器和打印机在李继工位）


需要在校园网内网状态下，可以浏览器打开以下链接，可以打开说明连接正常：
http://172.25.19.164:631/printers/Hewlett-Packard-HP-LaserJet-1020

## win客户端安装步骤：

### 1. win 驱动安装

首次安装时需要安装驱动，系统需要包含git软件，下载地址：https://git-scm.com/download/win

下载安装好之后打开cmd或是git bash：
git clone https://github.com/Purerli/bjut-1023-printer.git
克隆下载该仓库，在driver文件下有个驱动安装包，如下图所示
![Img](https://git.poker/Purerli/bjut-1023-printer/blob/main/images/image.oo9d5kbq4ls.webp?raw=true)
等待安装完成

### 2. win添加打印机

1. ![image](https://raw.githubusercontent.com/Purerli/image/main/images/printer.4u0lap0zj480.webp)
2. ![image](https://raw.githubusercontent.com/Purerli/image/main/images/printer.5pnx2h6zv8w0.webp)
3. ![image](https://raw.githubusercontent.com/Purerli/image/main/images/2767a57bb0365261d39f849d6a63c1b.6r5d8m0tqm40.webp)
4. ![image](https://git.poker/Purerli/bjut-1023-printer/blob/main/images/image.36t539k38qk0.webp?raw=true)
5. ![image](https://raw.githubusercontent.com/Purerli/image/main/images/6bb286ba1d0891c7ab431bf5dc1a655.53ukib162b80.webp)

## 驱动地址：

在本仓库的driver里面有两个驱动
.exe文件结尾是windows端（客户端）驱动
.run文件结尾是ubuntu端（服务端）驱动

## 常见问题：

1. ip变了，尝试ping一下172.25.19.164这个地址，如果ip变了。原因有俩：1.服务器重启，2.服务器关机
2. 服务端驱动损坏。修复过程：连接ssh lj@172.25.19.164，密码私聊问我，登录上之后有一个driver文件夹,复制执行./hplip-3.21.10.run（已给权限，该账户没有管理员权限），等待安装完成，再次尝试打印。
