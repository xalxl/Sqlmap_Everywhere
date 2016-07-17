#Sqlmap_Everywhere
项目概述：最新版本（1.0.7.25#dev）的无需Python环境的Sqlmap 及未来如何制作属于自己的、最新的、无需Python环境的Sqlmap的方法介绍
<br>
Sqlmap项目地址：https://github.com/sqlmapproject/sqlmap

----
###　　　　　　　　　　　　Coder:crown prince
###　　　　　　　　　 E-mail:crownprince@windpunish.net

===========================
##前言：

###这份项目实现了什么？
笔者在近日编写一款提取POST SQL注入的数据包的程序时，需要通过一些案例，验证数据包的可行性，而sqlmap是便捷及准确的方式，但由于sqlmap目前仅支持Python 2.x，笔者自己对Python 3的许多语法特性十分偏爱，于是不希望在本机上同时载有Python 2.x及Python 3.x，在虚拟机中使用Python  2.7又有一些不便，笔者便希望能制作一款无需Python环境，直接为可执行程序的Sqlmap，但在制作中发现，仅使用相关转换工具并不足以实现我们的目标，且网络上相关的资源极少，目前最新的Sqlmap免Python版也是几月前的了。
<br>
于是，在不断地探索中，笔者找到了打造无需Python环境的Sqlmap的方法，希望将程序及经验分享出来 ：） 欢迎小伙伴们一起交流

###github布局：
1.Release部分：
https://github.com/crown-prince/Sqlmap_Everywhere/tree/master/Release/Bin
在Release部分，小伙伴们可以直接下载后，同时和已编译好的run.exe放置在一起（run.exe与Bin文件夹放在一起，请勿放置于其中），直接运行run.exe，即可按照习惯的方式，使用sqlmap.exe
<br>
2.Source部分：
https://github.com/crown-prince/Sqlmap_Everywhere/tree/master/Source
在Source部分，包括了程序的所有源码，主要体现的是：https://github.com/crown-prince/Sqlmap_Everywhere/blob/master/Source/run.cpp
run.exe的源码，这是联系sqlmap与使用者的桥梁

###程序截图：
1.运行截图：
![](https://github.com/crown-prince/Sqlmap_Everywhere/blob/master/%E7%A8%8B%E5%BA%8F%E6%88%AA%E5%9B%BE/1.png)

2.存在漏洞

##意见与建议：

----

欢迎大家在使用过程中提出各种宝贵的意见和建议，以及各种bug，不胜感激

反馈邮箱crownprince@windpunish.net

