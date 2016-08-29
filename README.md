## 一个es6 转化 es5的空包
可用于测试es6转化为es5的测试
## 环境要求
node+npm+git+webpack+babel
```npm
$ npm install webpack --save-dev
$ npm install babel-loader --save-dev
```
```npm
npm install babel-core babel-preset-es2015 --save-dev
```
##新建一个文件.babelrc
```babelrc
{ "presets": ["es2015"] }
```
