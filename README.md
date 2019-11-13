# Vue高仿饿了么APP
> 使用vue@2.0开发的高仿饿了么APP（用户端）

## 主要依赖
- 基于vue@2.0
- 使用vue-cli@2.0搭建项目框架
- 使用vue-router@2.1进行页面路由切换
- 使用vue-resource@1.0.1进行http请求获取数据
- mock假数据存储在本地
- 使用stylus编写样式
- 使用eslint进行js代码的规范、
- 使用[better-scroll](https://github.com/ustbhuangyi/better-scroll)进行联动滑动

## Build Setup

# install dependencies
$ npm install

# serve with hot reload at localhost:8088
$ npm run dev

# build for production with minification
$ npm run build

```



- Mac下安装基于vue@1.x的vue-cli脚手架时报错`not matches webpack#1.0`

	答：因为"#"在zsh中是特殊字符，所以需要在webpack#1.0外加双引号，即使用`vue init "webpack#1.0" <project-name>`。
- Stylus中文文档

	答：http://www.zhangxinxu.com/jq/stylus/
- es6入门学习

	答：http://es6.ruanyifeng.com/

- eslint规则

	答：http://eslint.org/docs/rules/
- 设备像素比

	答：http://www.zhangxinxu.com/wordpress/2012/08/window-devicepixelratio/
	
- Flex弹性布局

	答：http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html?utm_source=tuicool
- 移动端1px边框的实现

	答：先给需要添加1像素边框的元素设置一个1像素的伪类，然后根据手机屏幕的dpi大小对伪类进行相应的缩减，从而达到手机端1像素边框的实现。
- CSS Sticky footer

	答：[CSS秘密花园:Sticky footers](http://www.w3cplus.com/css3/css-secrets/sticky-footers.html)
- better-scroll实现联动

	答：https://github.com/ustbhuangyi/better-scroll

