## 目录结构

## 第一章

src 目录

```
├─api                   // 网路请求代码、工具类函数和相关配置
├─application           // 项目核心功能
├─assets                // 字体配置及全局样式
├─baseUI                // 基础 UI 轮子
├─components            // 可复用的 UI 组件
├─routes                // 路由配置文件
└─store                 //redux 相关文件
  App.js                // 根组件
  index.js              // 入口文件
  serviceWorker.js      // PWA 离线应用配置
  style.js              // 默认样式

```

## 第二章：

### 路由配置：

```
npm install react-router react-router-dom react-router-config --save
```

- [react-router]() 
- [react-router-dom]() 
- [react-router-config](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-config) 路由鉴权，配置静态路由，其源码就是一个高阶函数 利用一个map函数生成静态路由
  - [参考资料1](https://segmentfault.com/a/1190000015282620?utm_source=channel-hottest) 



### Redux准备

安装：

```bash
npm install redux redux-thunk redux-immutable react-redux immutable --save
```

- redux
- redux-thunk
- redux-immutable 因为项目中需要用到 immutable.js 中的数据结构，所以合并不同模块 reducer 的时候需要用到 redux-immutable 中的方法。
- react-redux
- immutable



## 第三章 轮播组件开发

- css 中

```css
background: linear-gradient (hsla (0,0%,43%,.4),hsla (0,0%,100%,0));
```

- [linear-gradient](https://www.runoob.com/cssref/func-linear-gradient.html) 线性渐变
- [hsla](https://www.runoob.com/cssref/func-hsla.html) 类似于 rgba 实现透明色 ，参考资料 [rgba()和hsla()的区别](https://blog.csdn.net/qq_34567015/article/details/81359226) 