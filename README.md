# 简介

## 1.项目描述

1. 此项目为一个前后端分离的外卖 Web App (SPA) 项目
2. 使用了 Vue 全家桶+ES6+Webpack 等前端技术
3. 包括商家, 商品, 购物车, 用户等多个功能子模块
4. 采用模块化、组件化、工程化的模式开发

## 2.项目所学

### 2.1项目开发流程及开发方法

1. 熟悉一个项目的开发流程
2. 学会组件化、模块化、工程化的开发模式
3. 掌握使用 vue-cli 脚手架初始化 Vue.js 项目
4. 学会模拟 json 后端数据，实现前后端分离开发
5. 学会 ES6+eslint 的开发方式
6. 掌握一些项目优化技巧

### 2.2 Vue 插件或第三方库

1. 学会使用 vue-router 开发SPA单页应用
2. 学会使用 axios/vue-resource 与后端进行数据交互
3. 学会使用 vuex 管理应用组件状态
4. 学会使用 better-scroll/vue-scroller 实现页面滑动效果
5. 学会使用 mint-ui 组件库构建界面
6. 学会使用 vue-lazyload 实现图片惰加载
7. 学会使用 mockjs 模拟后台数据接口

### 2.3 样式/布局/效果相关

1. 学会使用 stylus 编写模块化的 CSS
2. 学会使用 Vue.js 的过渡编写酷炫的交互动画
3. 学会制作并使用图标字体
4. 学会解决移动端 1px 边框问题
5. 学会移动端经典的 css sticky footer 布局
6. 学会 flex 弹性布局

## 3.API接口文档

[项目API接口文档](https://github.com/Sunflowerkdy/shop-takeOut/blob/main/serve/API文档.md)

## 4.运行项目

#### 启动服务器，再打开项目

由于本项目使用MongoDB数据库，使用前先安装，并成功打开数据库连接

**server文件夹下cmd命令：**

1. `npm install`
2. `npm start`

**工程根目录下cmd命令：**

1. `npm install`
2. `npm start`

**登陆**

1. 手机号登陆，需要自己注册容联云通讯后先添加一个测试账号，然后在server\util\sms_util.js中修改相应个人配置，之后输入符合格式的手机号即可
2. 密码登陆，默认用户名abc，密码123