Cloud_AD
==============================================
post your ad to arudino via raspberry pi
----------------------------------------------
项目说明


NOTE:

当前阶段：
服务器主函数基本写完，命令行参数解析完成。
正在重新按照面向对象的编程方法进行实现。目前进行代码结构重构。
准备迁移打桩工具到google mock。
实现并测试远端功能。
编写终端守护进程。CS架构程序设计。

已完成：
服务器简单架构初步完成。服务器makefile基本写好。
完成测试串口模块交叉编译，发现交叉编译库名字错误，已修正。
重要进度：完成交叉变异实验。serial库交叉编译完成。
交叉编译环境脚本开关。
代码结构重构思路完成，按照对象即功能控制块的想法进行重构。
简单学习google mock。
完成简单ut脚本以及环境设置。
组建gitlab ci环境，并且将项目添加到gitlab的ci环境中。组建完成，准备尝试ut
版本管理迁移到gitlab
完成UT结构设计。
学习关于DNS解析的网络编程。
DDNS解析链接函数完成，UT编写MAKEFILE完成。
DNS解析链接函数调试完成，UT测试常规测试通过。
NS解析用gethostbyname，学习使用！
树梅派安装完成，SSH测试完成。
arudino远端功能测试数据包type 1,2,8
串口测试。
串口编程学习。

准备基本完成。

项目目标：
制作基于1602液晶屏的“云广告”板。
通过wordpress等html端的整合对广告板所显示内容进行管理。
广告板部署之后更改数据非常容易，通过网页即可～～
