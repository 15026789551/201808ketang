## 珠峰课堂

## 安装依赖
- react react核心包
- react-dom DOM操作相关的包，作用是把组件渲染到页面上
- react-router-dom  处理路由，根据浏览器的路径不同渲染不同的组件
- babel-loader 加载器，可以在webpack打包的时候，把es6 es7 react转译成es5
- @babel/core babel的核心包
- @babel/preset-env  转es6/es7
- @babel/preset-react 转react
- redux 核心模块 createStore 
- react-redux connect Provider实现的是react和redux的连接
- redux-logger 处理日志的
- redux-promise 处理promise
- redux-thunk 处理函数的
- react-router-redux 把路由信息同步到仓库中
- style-loader 在页面中添加style标签
- css-loader 处理CSS中的import url 
- less-loader 把less编译成css
- less less编译的核心包
- url-loader 加载二进制文件 图片 图标
- webpack webpack核心包
- webpack-cli webpack的命令行工具
- webpack-dev-server 开发服务器
- express 提供HTTP服务器
- body-parser 处理请求体，把
- express-session 处理会话
- lodash 提供 一些工具方法，比如克隆 

```js
yarn add react react-dom react-router-dom 
yarn add  babel-loader @babel/core @babel/preset-env @babel/preset-react
yarn add redux react-redux redux-logger redux-promise redux-thunk react-router-redux
yarn add  style-loader css-loader less-loader less url-loader
yarn add webpack webpack-cli webpack-dev-server
yarn add express body-parser express-session lodash
```

## 项目处理
保留二个文件，其它的全部删除
- node_modules
- package.json

## 新建webpack配置文件

