# kadai2

# ロボットシステム学課題2
## 概要
[ロボットシステム学2018第13回](https://github.com/ryuichiueda/robosys2018/blob/master/13.md)より
## 動作環境

|||
|:--:|:--:|
| Raspberry Pi | Raspberry Pi Model 3B+ |
| OS | Ubuntu16.04 |
| kernel | Linux ubuntu 4.14.58-v7+ |
| ROS | ROS kinetic |
```
## 動画URL
https://youtu.be/A2Mm7umCyK0

##  実行方法
```
$ git clone https://github.com/KentaKawamata/robosys2018_usingROS.git
$ cd robosys2018_usingROS
$ roslaunch LED LED.launch
```
LEDを点灯させる．
`$ echo 1 > /dev/myled0`
LEDを消灯させる．
`$ echo 1 > /dev/myled0`
