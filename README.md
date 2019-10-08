# Taro-demo
github上能找到的taro适配Android、iOS、微信小程序、H5最佳实践,主要涉及到了基础网络请求的封装、style工具样式引用替换scss的繁琐写法大幅度简化代码,同时解决了scss样式无法通过className进行属性传递的问题、自定义tabBar、全局模态对话框展示(解决了微信小程序端不能覆盖底部tabBar的问题)、展示了相同组件多端适配引用的方式、多端样式布局通过styleAssign注入flex、column、relative的方式实现统一化、演示了app的消息通信,本脚手架各端适配的比较完美适合用来进行全新项目的多端开发.

### 技术栈
typescript+eslint+redux+taro+react-native+mock


### 用法
直接clone本项目进入项目根目录执行npm install操作,然后将third_changes对应目录里面的修改项替换项目根目录node_modules里面对应的组件,react-native原生端壳子[Taro-demo-rn-shell](https://github.com/bozaigao/Taro-demo-rn-shell)

### 多端适配效果图
![效果图1](./img/show_1.jpeg)

![效果图1](./img/show_2.jpeg)

![效果图1](./img/show_3.jpeg)

![效果图1](./img/show_4.jpeg)
