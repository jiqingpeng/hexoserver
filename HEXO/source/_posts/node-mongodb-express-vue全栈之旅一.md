---
title: node+mongodb+express+vue全栈之旅之mongodb
date: 2018-01-17 10:48:23
tags: node
---
# mongodb
MongoDB 是目前在IT行业非常流行的一种非关系型数据库(NoSql)，其灵活的数据存储方式备受当前IT从业人员的青睐。因为对于本人对于liunx不是很熟练这里主要讲如何在windows平台下安装MongoDB。
# 安装步骤
**一  mongodb官网下载地址** 
[https://www.mongodb.com/download-center#community](https://www.mongodb.com/download-center#community)  

***二 依次点击下图标红的标签**  
  Community Server-> Windows->Download(msi)  
![mongodb下载地址](/images/mongodb.png "mongodb下载地址")  
<!--more-->    
**三 下载解压之后去配置系统环境变量**  
 右击我的电脑-> 属性->高级系统设置->属性->高级->环境变量->系统变量->编辑->path  
![mongodb下载地址](/images/mongodb1.png "mongodb下载地址")  
![mongodb下载地址](/images/mongodb2.png "mongodb下载地址")  
![mongodb下载地址](/images/mongodb3.png "mongodb下载地址")  
在path的最后面添加上我们mongodb的文件地址，可以右击mongodb查看文件地址。我的是C:\Program Files\MongoDB\Server\3.0\bin  
**四 启动mongodb数据库**  
由于c盘是系统默认盘，什么东西都放在c盘是不好的，所以我的mongdb数据库放在里D盘，在D盘根目录上新建议mongodb文件夹，中，把c盘MongoDB\Server\3.0\bin目录下的所有文件拷贝到mongodb文件夹下，新建一个data文件夹 ，data文件夹中新建一个db文件夹。新建一个 mongodb.cmd文件  
![mongodb.cmd](/images/mongodb5.png "mongodb下载地址")  
D盘mongodb目录结构如下图  
![mongodb.cmd](/images/mongodb4.png "mongodb下载地址")  
双击或者用cmd打开mongodb.cmd出现下图就说明mongodb数据库安装成功了。  
![mongodb.cmd](/images/mongodb6.png "mongodb下载地址") 
 

 
