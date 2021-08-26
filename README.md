# si4732Radio  
  
![Image text](https://github.com/bg6jji/si4732Radio/blob/main/Gerber_File/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20210825234056.png)
  
这是借鉴PU2CLR和LZ1PPL的原理图绘制的PCB,PCB打样来自于深圳嘉立创(www.sz-jlc.com) ,第一版打样仅测试了FM接收，因为没有安装全部零件未做AM 广播频率测试。  
第一版的PCB宽度是40*93，上面2个编码器是二选一，安装任意一个即可。第二版在这里公布的文件已经取消了EC11编码器，它太高了。  
第二版原理图、BOM文件、Gerber文件在下面目录中可以被下载，它是按照PU2CLR提供的文件作为参考绘制的。  
目录中的图片仅供参考。  
请您遵守开源规则，感谢您的访问！  
主要功能特点介绍：  
1、背面安装有电池插座  
2、有TP4056充电电路  
3、有CH340C 芯片，可以直接调试内置的Arduino(MEGA328)程序  
4、6个硅胶按键  
5、一个侧面安装的拨轮编码器，方便操作  
6、一个电源开关在右侧上方  
7、PAM8406DR数字双声道功放，支持立体声  
8、双扬声器接口(***提醒，PCB通电前，务必连接扬声器，如果没有连接扬声器会造成功放芯片损坏***)      
9、OLED 屏幕，尺寸为0.96寸  
10、TYPE C插口，具备充电和通讯功能  
  
参考网址：  
https://pu2clr.github.io/SI4735/  
https://www.lz1ppl.com/en/2021/04/22/si4735-all-mode-reciver/  
