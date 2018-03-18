## openvpn-install
OpenVPN [road warrior](http://en.wikipedia.org/wiki/Road_warrior_%28computing%29) installer for Debian, Ubuntu and CentOS.

This script will let you setup your own VPN server in no more than a minute, even if you haven't used OpenVPN before. It has been designed to be as unobtrusive and universal as possible.

## About this fork
Forked from [Nyr/openvpn-install](https://github.com/Nyr/openvpn-install)

This fork asks whether you want to use tls-crypt instead of tls-auth, for better obfuscation on control channel. Requires appropriate support on clients.

This fork also adds the feature **(opt-in)** to move configuration files directly to an accessible URL. This will allow the fastest access to your OpenVPN server. **Please be aware of the risks, and delete the file at /var/www/html afterwards.**

Please uninstall previous installations if there are any.

### Installation
To install this modified fork, please run

`wget https://raw.githubusercontent.com/pluush/openvpn-install/tls-crypt/openvpn-install.sh -O openvpn-install.sh && bash openvpn-install.sh`
