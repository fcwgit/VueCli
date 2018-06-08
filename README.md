# VueCli
1、检查是否安装npm
npm -v

2、安装vue-cli
npm install vue-cli -g

3、检查vue-cli是否安装成功
vue -V
注意：是大写的  V

4、使用脚手架搭建环境
vue init <template-name> <project-name>

<template-name>：表示模板名称，vue-cli官方为我们提供了5种模板，
    webpack-一个全面的webpack+vue-loader的模板，功能包括热加载，linting,检测和CSS扩展。
    webpack-simple-一个简单webpack+vue-loader的模板，不包含其他功能，让你快速的搭建vue的开发环境。
    browserify-一个全面的Browserify+vueify 的模板，功能包括热加载，linting,单元检测。
    browserify-simple-一个简单Browserify+vueify的模板，不包含其他功能，让你快速的搭建vue的开发环境。
    simple-一个最简单的单页应用模板。
<project-name>：标识项目名称，这个你可以根据自己的项目来起名字。
在实际开发中，一般我们都会使用webpack这个模板

5、运行
npm run dev
http://localhost:8080正常访问，则说明正常启动了


=======================目录结构============================
1、build：项目构建的代码，与webpack有关的基本都在这个目录
2、config：项目开发相关配置
.
|-- build                            // 项目构建(webpack)相关代码
|   |-- build.js                     // 生产环境构建代码
|   |-- check-version.js             // 检查node、npm等版本
|   |-- dev-client.js                // 热重载相关
|   |-- dev-server.js                // 构建本地服务器
|   |-- utils.js                     // 构建工具相关
|   |-- webpack.base.conf.js         // webpack基础配置
|   |-- webpack.dev.conf.js          // webpack开发环境配置
|   |-- webpack.prod.conf.js         // webpack生产环境配置
|-- config                           // 项目开发环境配置
|   |-- dev.env.js                   // 开发环境变量
|   |-- index.js                     // 项目一些配置变量
|   |-- prod.env.js                  // 生产环境变量
|   |-- test.env.js                  // 测试环境变量
|-- src                              // 源码目录
|   |-- components                     // vue公共组件
|   |-- store                          // vuex的状态管理
|   |-- App.vue                        // 页面入口文件
|   |-- main.js                        // 程序入口文件，加载各种公共组件
|-- static                           // 静态文件，比如一些图片，json数据等
|   |-- data                           // 群聊分析得到的数据用于数据可视化
|-- .babelrc                         // ES6语法编译配置
|-- .editorconfig                    // 定义代码格式
|-- .gitignore                       // git上传需要忽略的文件格式
|-- README.md                        // 项目说明
|-- favicon.ico 
|-- index.html                       // 入口页面
|-- package.json                     // 项目基本信息






















