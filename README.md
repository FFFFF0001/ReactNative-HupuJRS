# React-Native-HupuJRS

这是一个 React Native 版虎扑论坛第三方客户端，个人学习作品，可同时兼容Android/iOS平台，共用几乎99%的代码
目前提供最基本的看帖子的功能，后续可考虑增加登录与回帖功能，
该App仅供学习交流React Native技术使用，请勿用于商业用途，欢迎Star和Fork，欢迎提PR和Issues

## 下载


## 界面  How does it look like?

* 主页



* 选择子论坛



* 侧边栏


* 帖子列表

* 帖子详情

* 回复

## 运行  How to run

### installation step by step:
1.install nvm

2.install nodejs > 9.0

3.npm install -g react-native-cli

4.project folder: yarn install

5.project folder: yarn add babel-plugin-transform-decorators-legacy

6.project folder: react-native link

### run on simulator(android might be not work):

android:react-native run-android
ios:react-native run-ios

### run on real device:

android:

1.adb reverse tcp:8081 tcp:8081

2.run app on androidstudio

ios:

1.change the project signature to the valid apple developer account

2.run app on xcode

~~* package bundle for release:~~

~~react-native bundle --entry-file index.js --platform ios --dev false --bundle-output ios/main.jsbundle --assets-dest ios
react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res/~~

### Release on IDE:

for ios:

1.change schema to "release"

2.AppDelegate.m: change jsCodeLocation to Production

3.build archive and export

for android:

1.setup sign cert file

2.gradle build

## 开源组件 Related content

在项目中使用的React Native社区组件:

## TODO

1. ~~优化子论坛列表样式~~ (done)
2. 登录功能
3. 我的帖子(需要登录)
4. 回帖
5. RN项目踩坑过程分享

## License

This project is available under the MIT license.
