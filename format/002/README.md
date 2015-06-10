---
category: wrong/format/002
author: xiaojian
datetime: 2015-04-23
---

## summary

sdk发送的client-request是无法解析的json串

## detail

1. 修改config.yaml文件,发送的文件格式不是json,修改Content-Type字段为application/data
2. 编写request文件

## changelog

- 2015-04-23: 初始版本
- 2015-04-23: 初始版本