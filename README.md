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





























