# Verilog HDL

# 简介：什么是Verilog HDL?

简介：Verilog HDL是一种硬件描述语言，以文本形式来描述数字系统硬件的结构和行为的语言，用它可以表示逻辑电路图、逻辑表达式，还可以表示数字逻辑系统所完成的逻辑功能。Verilog HDL和VHDL是世界上最流行的两种硬件描述语言，都是在20世纪80年代中期开发出来的。两种HDL均为IEEE标准。（摘自[百度百科](https://baike.baidu.com/item/Verilog%20HDL/596353)）



# 使用软件

- [Vivado](https://china.xilinx.com/support/download.html) （Xilinx，现被AMD收购）或者[Quartus](https://www.intel.com/content/www/us/en/collections/products/fpga/software/downloads.html)（Altera，现被Intel收购）+[Modelsim](https://eda.sw.siemens.com/en-US/products/ic/modelsim/)（Mentor Graphics，现被Siemens收购）

- [VSCode](https://code.visualstudio.com/) （或者任何便于写代码的文本编辑器，vivado自带的代码界面不太好用）



# 学习资源

- ~~B站大学~~：资源不少，推荐一个 [Verilog硬件描述语言 西安电子科技大学 蔡觉平等主讲](https://www.bilibili.com/video/BV12y4y1v7V3/)

- [HDLbits](http://hdlbits.01xz.net)（教程兼刷题网站，入门强推）

- [菜鸟教程](https://www.runoob.com/w3cnote/verilog-tutorial.html)

- [菜鸟教程（进阶篇）](https://www.runoob.com/w3cnote/verilog2-tutorial.html)

- [中科大《数字电路实验》课程文档](https://soc.ustc.edu.cn/Digital/)



# 涉及这个知识的学校课程

集成电路与微纳电子创新学院：数字逻辑基础(H)（大二上）

# 练习

~~（其实是我们荣誉课的作业）~~

1. （组合电路）二进制码转七段显示码

2. （时序电路）4位同步计数器

(吐槽:为了看见这个计数器的效果,你要先写一个分频器,这个分频器如果不用IP核就得写一个27位同步计数器)

1. （有限状态机）自动售货机

2. （大作业1）数字系统设计
    - 交通灯
    - 电子秒表
    - VGA显示+数字系统（比如做个小游戏）
    注：一些FPGA开发板可能没有VGA接口而有HDMI接口

3. （大作业2，3人组队）RISC-CPU



