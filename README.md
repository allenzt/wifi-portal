# WiFi-Portal([中文](https://github.com/zhaojh329/wifi-portal/blob/master/README_ZH.md))

![](https://img.shields.io/badge/license-GPLV3-brightgreen.svg?style=plastic "License")

WiFi-Portal is a very efficient captive portal solution for wireless
router which with embeded linux(LEDE/Openwrt) system. It's referenced wifidog
and apfree_wifidog, and it's a whole new one captive portal solution. Unlike
wifidog and apfree_wifidog, wifi-portal does write kernel module to implement
authentication management instead of using iptables to create firewall rules.

## features:
* Use libev
* Write kernel module to implement authentication management instead of using iptables to create firewall rules
* Support HTTPS
* Alternative openssl and mbedtls
* Support remote control and configure

# How To Contribute
Feel free to create issues or pull-requests if you have any problems.

**Please read [contributing.md](https://github.com/zhaojh329/wifi-portal/blob/master/contributing.md)
before pushing any changes.**

# Thanks for the following project
* [wifidog-gateway](https://github.com/wifidog/wifidog-gateway)
* [apfree_wifidog](https://github.com/liudf0716/apfree_wifidog)
* [mongoose](https://github.com/cesanta/mongoose)
* [libev](https://github.com/kindy/libev)

# If the project is helpful to you, please do not hesitate to star. Thank you!

