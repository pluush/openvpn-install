## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

## About this fork
Forked from [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install)
This fork uses tls-crypt instead of tls-auth, for better obfuscation on control channel.
Requires appropriate support on clients.
Please uninstall previous installations if there are any.

### Installation
To install this modified fork, please run
`wget https://raw.githubusercontent.com/pluush/openvpn-install/tls-crypt/openvpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh`
