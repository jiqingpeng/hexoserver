---
title: 简单谈谈vue-cli
date: 2016-02-15 13:23:24
tags: 
---
# 闲言
在JavaScript领域，Angular、React.js和vue.js之间的战斗一直在持续升温！为了工作，程序员选择正确的框架和库来构建应用程序是至关重要的(真的重要吗？还不是因为水平高的人不想重复造轮子，水平低的人比如我自己0..0恨不得找个能一键构成项目的框架，不过要是那样的话我们应该也失业了)好在这个框架还是需要开发人员去操作部署的，言归正传说起vue就要简单说一下与vue并驾齐驱的另外俩假马车了对就是大家听说过的Angular和React
<!--more-->
## 先谈一谈前端目前的三大框架
### Angular
angular最开始1版本的时候自己闲来无事学习了一些，在刚开始的时候是最早的mvc框架但是后来据说走偏了然后直接推出了angular2版然后到现在发展到了五，对于新手不是很友好
### React
最稳定，社区活跃量最大，大佬扎堆的开源框架，后来据说是因为协议的问题一直有纠纷，若使用react的产品与facebook的业务存在商业竞争关系，则其授权失效。意思就是你不能用他家的东西开发抢他家生意的产品，不然就不给你用，然后百度大佬就弃用了
### Vue
大佬的评价  

Vue.js在可读性、可维护性和趣味性之间做到了很好的平衡。
Vue.js处在React和Angular 1之间，而且如果你有仔细看Vue的指南，就会发现Vue.js从其它框架借鉴了很多设计理念。
Vue.js从React那里借鉴了组件化、prop、单向数据流、性能、虚拟渲染，并意识到状态管理的重要性。
Vue.js从Angular那里借鉴了模板，并赋予了更好的语法，以及双向数据绑定（在单个组件里）。 
 
自己的评价  

好！好！好！重要的事情说三遍，我觉得他好的原因就是他是中文文档（他他么的）是中文文档，对于我们这种英语2级的码农来说这就是福利啊。
# vue全家桶的搭建
## 一、环境的搭建
首先你得有一个node   <https://nodejs.org/zh-cn/download/>  
然后我们就可以开开心心的搭建了，来傻瓜操作开始点击 **开始** 按钮在最下方的 **搜索和文件** 文本框中输入 **cmd**  
![背景1](https://user-gold-cdn.xitu.io/2017/12/22/1607caa2781584e0)  
cmd常用命令     <https://www.cnblogs.com/kekec/p/3662125.html>  
	`cd Downloads` 
因为我总是在github上面下载一些别人的代码所以就在Downloads这个目录下作为根目录
全局安装 webpack  
	`npm install -global webpack`   
全局安装 vue-cli  
	`npm install --global vue-cli`  
创建一个基于 webpack 模板的新项目  
	`vue init webpack my-project(你的项目名称)`  
然后一路回车到家,除了User Eslint to lint your code 和set up unit tests 和 setup e2e tes unit tests with Nigthwatch输入n不要问为什么快上车码完代码要去吃鸡了，有兴趣的自己查一下。  
安装依赖，走你  
	`cd my-project`  
	`npm install` 
	`npm run dev`   
**大功告成** 
