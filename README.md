
scrambled openvpn server deb installer for Raspberry PI
Raspberry PI running 2014-01-07-wheezy-raspbian

Usage 

wget http://snapshot.debian.org/archive/debian-ports/20110407T130234Z/pool-armhf/main/o/openssl098/libssl0.9.8_0.9.8o-7_armhf.deb

sudo dpkg -i libssl0.9.8_0.9.8o-7_armhf.deb

sudo apt-get install openssl-blacklist openvpn-blacklist liblzo2-dev libpam0g-dev libpkcs11-helper1-dev -y

sudo dpkg -i openvpn_2.3.2-Scramblevpn-raspbian_armhf.deb




