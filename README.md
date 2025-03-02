# segway-battery-diagnostics-V3
A segway battery diagnostics with GUI V2 version Forked from [martinbogo/pt-battery-diagnostics](https://github.com/martinbogo/pt-battery-diagnostics)

所需设备：
1、Arduino（UNO或mega 2560均可，我选的2560是因为它可以把3.5寸TFT彩屏直接插到主板上，而且我设计的3D外壳也是mega2560的尺寸）

2、一块TFT的3.5寸彩屏，我给出了Arduino的Library，是因为我选的屏幕原生库的字体和线条不好看，我为了更换字体和圆角，所以选了我这个Library。如果你自己购买的TFT屏幕也是直插的，请自己跟卖家沟通，要库或者针脚定义。

3、一个12V的DC电源，供电电流最好在3A左右，任何形式均可。这次更新V3版本主要是取消了从segway的电池取电，变成用DC供电的方式给segway电池的bms主板供电，这样会更稳定！

4、一些铜针脚，还有一些接线，按键开关等。
