# Vue外卖App（移动端适配）
这是一款基于Vue2的外卖APP
### 写在前面
由于太久没写前端了，之前毕业的第一年在公司是用Angular+TypeScript和Java进行的全栈开发，Vue只接触过一小段时间，后来换了工作都是全后端开发，导致前端技术已经非常生疏，所以决定重拾前端。
这是一款基于 ES6 + vue2 + elementUi的外卖APP
## 项目启动：
1. 由于后续还会有多个前端项目，需要维护多个版本的node，所以使用nvm管理多个node.js版本
 [点击此处查看nvm教程](https://blog.csdn.net/qq_22182989/article/details/125387145)
2. npm install 下载安装模块
3. npm start 启动项目
## 描述：
目前是无错误的稳定版本，已将eslint的提示错误也修正了。
### 第三方库的使用：
* mintUI构建界面，better-scroll库实现页面滑动
* 使用vue-router开发单页应用
* 使用axios向后台发送请求，使用mockjs模拟后台数据接口
* 使用vuex管理组件共享数据
### 已实现的功能有：
+ 账号密码登陆或手机号验证码登陆
+ 首页轮播、商家列表及总购物车
+ 商家商品、评价、信息界面展现，实现购物车加购功能
+ 刷新购物车数据保存的功能
+ 也许还有一些错误或者可以优化的地方，欢迎和我交流，共同学习，一起改进。