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