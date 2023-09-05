# FlipperZero_Annoying_Apple
1. 首先要先下载官方框架代码
```
git clone https://github.com/flipperdevices/flipperzero-firmware.git
```
2. 更新“gap.c”文件，然后编译更新的固件。
```
./fbt COMPACT=1 DEBUG=0 VERBOSE=1 updater_package
```
