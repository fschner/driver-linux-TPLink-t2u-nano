# driver-linux-TPLink-t2u-nano
Driver TP-Link AC600 Archer T2U Nano no Linux - Ubuntu


# Install
$ sudo apt update
$ sudo apt install dkms
$ git clone -b v5.6.4.2 https://github.com/aircrack-ng/rtl8812au.git
$ cd rtl8812au
$ make dkms_install
$ shutdown -r now
