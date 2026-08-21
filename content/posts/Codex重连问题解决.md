---
title: Codex重连问题解决
date: 2026-08-21T23:00:00+08:00
categories:
 - 技术探索 
draf: false



---

解决代理非Tun模式下的Reconnecting问题

**代码**如下
```
setx HTTP_PROXY "http://127.0.0.1:10808"
setx HTTPS_PROXY "http://127.0.0.1:10808"
```
复制上面代码并Powershell中运行便可永久解决

**注**：上述的10808是我的端口号，我将展示如何查看端口号,查询相对应的端口号并替换
## v2rayN
![v2rayN端口查询](/images/mixed1.jpg)

## clash verge
![clash-verge端口查询](/images/mixed2.jpg)

## 其他客户端
找关键词mixed旁边的数字就是端口号
