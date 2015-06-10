---
category: wrong/format/003
author: xiaojian
datetime: 2015-04-23
---

## summary

sdk发送的Client-request中没有指明Content-Type为application/json

## detail

1. 修改config.yaml文件,修改Content-Type字段的value值为空
2. 编写request文件

## changelog

- 2015-04-23: 初始版本
- 2015-04-23: 初始版本