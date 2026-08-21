---
title: Codex reconnecting解决方法
date: 2026-08-19T10:00:00+08:00
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
**注**：上述的10808是我的端口号，我将展示如何查看端口号,查询相对应的端口号并替换
# v2rayN
[v2rayN端口查询](/images/mixed1.jpg)

# clash verge
[clash-verge端口查询](/images/mixed2.jpg)

