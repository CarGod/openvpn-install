## [中文文档](https://github.com/CarGod/openvpn-install/blob/master/Chinese.md)

OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

`wget https://git.io/vpn -O openvpn-install.sh && bash openvpn-install.sh`

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall OpenVPN.

### I want to run my own VPN but don't have a server for that
You can get a little VPS from just $2.5/month at [Vultr](https://www.vultr.com/?ref=7137562).

If you are in China, it is recommended that you create a Japanese host.

**Suggest create Ubuntu 16.04 version.**

### Use

After everything is installed, you need to download the generated certificate file from the remote server to the local computer, which is the **.ovpn** file. Then use the client of the corresponding platform to import the certificate and connect it.

#### Client Download Address

Mac: https://tunnelblick.net/downloads.html

Windows: https://openvpn.net/index.php/open-source/downloads.html

If the address is inaccessible, you can download it here:

Mac: https://github.com/CarGod/openvpn-install/blob/master/Tunnelblick_3.7.5a_build_5011.dmg

Windows: https://github.com/CarGod/openvpn-install/blob/master/openvpn-install-2.4.5-I601.exe

Android or iPhone can search OpenVPN in the app market to choose the right download.

### Donations

If you want to show your appreciation, you can donate via [PayPal](https://www.paypal.me/cargod)
