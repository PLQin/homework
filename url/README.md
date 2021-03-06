整理域名
========

## 问题描述

有若干个域名，比如：

* a.com
* a.b.com
* a.io
* c.a.b.com
* *.a.io

现在需要对它们进行整理，输出一个新的数组，符合：

1. 同一域名只出现一次
2. 按照主域名进行排序
3. 如果出现 b.a.io, a.io, *.a.io，则只保留 *.a.io

## 要求

1. 使用 JS
2. 完成一个独立文件，命名为 'url.js'，使用 ES6 modules
3. 安装依赖 `npm i`
4. 运行 `./node_modules/.bin/mocha --require babel-register url/test.js` 完成测试

## 奖励和讲解

奖励截止时间：2018-03-25 20
讲解时间：2018-03-25 21:30

1. 第一位完整完成的同学，奖励一本《CSS世界》
2. 其他所有完成的同学，抽一本《深入理解ES6》
