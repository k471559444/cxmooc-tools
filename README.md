[![Build Status](https://www.travis-ci.org/CodFrm/cxmooc-tools.svg?branch=master)](https://www.travis-ci.org/CodFrm/cxmooc-tools)

# 超星慕课小工具
> 一个快速学习超星慕课的chrome扩展工具(੧ᐛ੭挂科模式,启动)
>
> 初次开发chrome扩展,有兴趣的朋友可以一起来哦

## Build
环境:
* Node.js
* webpack
```
npm install
npm run build
```
## Server
搭配了一个服务器程序,这个服务器将会记录你正确的答题答案,并不会记录你的任何账号信息

并且接口没有任何权限,全由插件提交上传,还请大家不要故意上传错误的答案 (๑• . •๑)

因为超新慕课是https的原因,所以服务器配置需要https

环境:
* Node.js
* Mongodb
```
npm install
npm run server
```

## 安装

### Chrome:

#### 方法1:

能够体验到最新的功能,需要安装环境,可能有bug

Build->扩展程序->开启开发者模式->加载已解压的扩展程序->目录:build/cxmooc-tools

#### 方法2:

比较稳定的版本,无需安装环境,下载即用

[https://github.com/CodFrm/cxmooc-tools/releases](https://github.com/CodFrm/cxmooc-tools/releases)

下载发布的版本cxmooc-tools.crx文件

扩展程序->开启开发者模式->解压cxmooc-tools.crx文件->加载已解压的扩展程序->目录:cxmooc-tools(刚刚解压到的目录)

### 其他chrome系浏览器:

例如:360极速浏览器,QQ浏览器等...(内核为chrome)
[https://github.com/CodFrm/cxmooc-tools/releases](https://github.com/CodFrm/cxmooc-tools/releases)

下载发布版本cxmooc-tools.crx文件,直接拖入浏览器安装

## 说明
PC打开超星慕课课程页面,在视频上方将会显示一个按钮,单击按钮即可直接将视频看完,但是有一定的风险

开始挂机需要先播放视频后,再点击,还在优化中

挂机模式2,还在测试中,不知道有什么样的风险,欢迎反馈,如果能成功,将在全自动挂机迈出一大步^_^

![](/build/cxmooc-tools/img/soft/soft_01.png)

## 其他
如果有兴趣的可以来一起开发,完善功能

GitHub项目地址:[https://github.com/CodFrm/cxmooc-tools](https://github.com/CodFrm/cxmooc-tools)

Blog地址:[http://blog.icodef.com/2018/01/25/1304](http://blog.icodef.com/2018/01/25/1304)
