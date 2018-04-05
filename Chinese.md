## [English Doc](https://github.com/CarGod/openvpn-install/blob/master/README.md)

OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) 支持平台： Debian, Ubuntu, CentOS.

即使你从来没有使用过OpenVPN，这个脚本也可以让你在一分钟之内在服务器上完成搭建。在没有这个脚本之前，我们可能需要一个多小时的搭建，搭建完成以后还可能存在各种各样的问题。有了这个脚本，这种痛苦再也不存在了，只需要根据提示，即可自动完成安装。

### 安装
在你的服务器的root权限运行下面的命令，并根据命令行提示信息进行输入：

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

一旦运行结束，你可以再次运行它来添加更多的VPN用户，删除其中的一些用户，或者完全卸载OpenVPN。

### 假如你还没有一台服务器
你可以购买这个非常便宜的主机： $2.5/月 [Vultr](https://www.vultr.com/?ref=7137562).

如果你是中国的用户，那么我建议你购买日本地区的主机，仅需要5美元一个月。

**建议创建 Ubuntu 16.04 版本的主机。**

### 使用

一切安装完成后，需要把生成的证书文件从远程服务器下载到本地，就是 **.ovpn** 文件，然后使用对应平台的客户端，导入证书，连接即可。

#### 客户端下载地址

Mac: https://tunnelblick.net/downloads.html

Windows: https://openvpn.net/index.php/open-source/downloads.html

如果地址无法访问，可以在这里下载：

Mac: https://github.com/CarGod/openvpn-install/blob/master/Tunnelblick_3.7.5a_build_5011.dmg

Windows: https://github.com/CarGod/openvpn-install/blob/master/openvpn-install-2.4.5-I601.exe

Android 或 iPhone 可以在应用市场搜索 OpenVPN 自己选择合适的下载。

### 捐赠

如果你想要捐赠我，可以通过下面的PayPal连接，选择合适的金额，建议一次捐赠不要超过10美元： [PayPal](https://www.paypal.me/cargod)

