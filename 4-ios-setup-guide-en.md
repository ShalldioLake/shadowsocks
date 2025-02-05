# Shadowsocks Setup Guide for iOS

## About Shadowsocks
>* Shadowsocks is an open-source encrypted proxy project, Typically, the client software will open a socks5 proxy on the machine it is run, which internet traffic can then be directed towards, similarly to an SSH tunnel.
>* Shadowsocks uses a self-designed protocol for secure communications. The encryption algorithms include AES, Blowfish, IDEA, and RC4. No handshaking is needed except for creating a TCP connection. Each request only forwards one connection and does not need to maintain the state of “always connected”, so it is relatively power-efficient on mobile devices. All traffic is algorithmically encrypted, allowing you to choose your own algorithm.
>* Clients are available on multiple major operating systems and platforms, including Windows, OSX, Android, Linux, and iOS systems and routers (OpenWrt).

## System Requirements
**Before you install, always make sure that your system meets the minimum system requirements.**

Shadowrocket: Requires iOS 9.0 or later.

Potatso Lite: Requires iOS 10.0 or later.

## Apps downloads

* [Potatso Lite](https://itunes.apple.com/us/app/potatso-lite/id1239860606?mt=8) (Free)
* [Shadowrocket](https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8) (US $2.99)

**The APPs on the App Store are maintained by their authors, and they are not developed by us. We have nothing to do with them. Please decide by yourself whether to purchase it.**

## Shadowsocks Configuration

#### Log in to our website (https://order.shadowsocks.se) and do the following:

* Click Services > My Services > Select your available products & services

* View your node information.

![View your node information. ](files/images-en/portal.png)

#### On your device, do the following:

Below are the instructions for setting up your Potatso Lite to your iPhone.
* Open Potatso Lite app after downloading from the App Store.

![Open Potatso Lite after installation from the App Store](files/images-en/ios-step1.png)

* Click "Get Started" > "Add Now".

![Use Now](files/images-en/ios-step2.png)

**Scan code configuration**

* Click "QR code" > "Potatso Lite Would like to Access the Camera" window, select "OK" > Scan your node's QR code and the node will be added automatically.

![Select QR Code](files/images-en/ios-step3.png)

**Manual configuration**

* Click "Add" > fill in the blank.

![manual proxy](files/images-en/ios-step3-2.png)

* Select "Type" (select Shadowsocks)> fill in "server" (Node addresses
)> fill in "port" (for your Service Port)> select "Encryption" > fill in "Password"> Fill in "Remarks" (It is optional, recommended to fill in the node location)> Click "✔" in the top left corner to complete the setting.

![fills in the blank](files/images-en/ios-step4.png)

* Click "Start" > Select "Allow" > Enable "Smart Routing".

> When you see the word VPN appear in the upper corner, the connection is successful.

![Agent fills in](files/images-en/ios-step5.png)

![Agent fills in](files/images-en/ios-step6.png)

![Agent fills in](files/images-en/ios-step7.png)
