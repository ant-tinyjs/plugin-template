# <%=name%>

> <%=description%>

## 查看demo

http://tinyjs.net/#/plugins/<%=name%>/demo

## 引用方法

- 推荐作为依赖使用

  - `npm install <%=name%> --save`

- 也可以直接引用线上cdn地址，注意要使用最新的版本号，例如：

  - https://gw.alipayobjects.com/as/g/tiny-plugins/<%=name%>/0.0.1/index.js
  - https://gw.alipayobjects.com/as/g/tiny-plugins/<%=name%>/0.0.1/index.debug.js

## 起步
首先当然是要引入，推荐`NPM`方式，当然你也可以使用`CDN`或下载独立版本，先从几个例子入手吧！

##### 1、最简单的例子

引用 Tiny.js 源码
``` html
<script src="https://gw.alipayobjects.com/as/g/tiny/tiny/1.1.7/tiny.js"></script>
```
``` js
var <%=buildName%> = require('<%=name%>');
// 或者
// import <%=buildName%> from '<%=name%>';
```

## 依赖
- `Tiny.js`: [Link](http://tinyjs.net/#/docs/api)

## API文档

http://tinyjs.net/#/plugins/<%=name%>/docs
