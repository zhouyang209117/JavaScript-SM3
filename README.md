# JavaScript SM3

## 简介

国密 SM3 密码杂凑算法的 JavaScript 实现。目前可在服务器端环境 Node.js 以及浏览器环境使用。

## 使用

直接下载源代码将 sm3.js 拷贝到你的项目中，或者使用 [npm](https://www.npmjs.org/) 安装：

### Node.js：

```sh
npm install sm3
```

```js
const sm3 = require('sm3');
const hash = sm3('值');
```

### 浏览器：

```html
<script type='application/javascript' src='sm3.js'></script>
<script>console.log(sm3('值'));</script>
```

## 要求

没有依赖，但 Node.js 版本需要>=6.0.0，或使用 sm3-babel.js 文件（Node.js 版本>=1.0.0），
也可自行使用 [Babel](http://babeljs.io/) 对 sm3.js 文件进行转化

```sh
babel sm3.js --out-file sm3-babel.js
```

## 接口

```js
const hash = sm3('值');
```

## 参考

[SM3 密码杂凑算法](http://www.sca.gov.cn/sca/xwdt/2010-12/17/1002389/files/302a3ada057c4a73830536d03e683110.pdf)

## License

[MIT license](http://www.opensource.org/licenses/MIT).
