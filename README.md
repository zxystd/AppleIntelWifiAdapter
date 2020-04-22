### Intel Wifi adapter on MacOS, the code is rewrite from Linux `iwlwifi` open source code. As of the last commit, the card initial routine is done.

## This repo will not be update, Intel Wifi team is continuing develope this project [AppleIntelWifi](https://github.com/AppleIntelWifi). My New Intel WiFi driver project is here [itlwm](https://github.com/zxystd/itlwm).


****
针对Apple未公开的AirPort程序进行的研究

目前基于10.15api

闲暇时间鼓捣。。。

## 使用方法，
xcode编译完成后
``` Bash
sudo chown -R root:wheel AppleIntelWifiAdapterV2.kext/
sudo kextload -v AppleIntelWifiAdapterV2.kext/
``` 

![图片1](https://github.com/zxystd/AppleIntelWifiAdapter/raw/master/img/QQ20191102-195821.png)  
![图片2](https://github.com/zxystd/AppleIntelWifiAdapter/raw/master/img/QQ20191102-195905.png)  
