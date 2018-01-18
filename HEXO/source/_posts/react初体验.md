---
title: react初体验
date: 2018-01-17 15:27:39
tags:
---
## 前言  
现在前端的三大框架react，angular，vue,react权限问题  
##react全家桶  
自从有了node做服务器，webpack做自动化构建工具了之后感觉开车不漂一个二十迈都有点对不起这俩个工具。
###  
为了快速地进行构建使用 React 的项目，FaceBook 官方发布了一个无需配置的、用于快速构建开发环境的脚手架工具 create-react-app。  
### 安装   
### 安装React-cli(快速上手脚手架 )  
	$cnpm install -g create-react-app  
没有 cnpm 的同学可以去看一下这篇文章安装一下[前后端分离与Node和NPM的那些事](http://www.jqpblog.site/2016/08/22/%E5%89%8D%E5%90%8E%E7%AB%AF%E5%88%86%E7%A6%BB%E4%B8%8ENode%E5%92%8CNPM%E7%9A%84%E9%82%A3%E4%BA%9B%E4%BA%8B/)
<!--more-->  
### 创建项目 
	$create-react-app appname 
### 进入项目 
	$cd appname
### 初始化下载所有项目 
	$cnpm install
### 开启服务 
	$npm run start  
**打开[http://localhost:3000/](http://localhost:3000/)就可以看到hellow react的初始页面了**  
## react-router4.0   
### 在DOM中先渲染，哪里用到哪里link调，相当于vue的router.js，exact排他默认这个路由显示
	<Router >
          <div className="App">
            <Route exact path="/" component={Home}/>
            <Route path="/My" component={My}/>
            <Route path="/Login" component={Login}/>
            <Route path="/Register" component={Register}/>
          </div>
	</Router>  
## create-react-app 脚手架中webpack端口和跨域处理  
### 更改端口  
在node_model->react-script  -> scripts ->  utils-> start.js中搜索3000修改成自己需要的，我这里修改为8080  
### 处理跨域  
在package.json文件最后加上  "proxy": "http://localhost:8080/"就好了。

