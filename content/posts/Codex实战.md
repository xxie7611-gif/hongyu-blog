---
title: Codex 实战成果
date: 2026-08-18T23:00:00+08:00
categories:
  - 技术探索
draft: false
---

这是我使用 Codex 通过 Vibe Coding 完成的一个自动更换壁纸小工具。

程序每小时自动更换一次壁纸，壁纸来源于 Bing 每日壁纸。

[下载小程序](https://wwbox.lanzoul.com/b00oe44k8b)

下载并安装后，程序会随 Windows 启动自动运行，无需额外配置。

密码：123

# 1. 项目背景

不想频繁手动更换壁纸，又对长期使用同一张桌面背景感到厌倦，所以我想做一个可以自动更换壁纸的小工具。

# 2. 实现思路

程序会定时获取 Bing 每日壁纸，下载到本地，并自动设置为 Windows 桌面背景。

# 3. Codex 开发过程

完整的 Vibe Coding 开发过程可以点击下面的链接查看。

[Codex 开发过程](codex://threads/01a0155c-e4fb-7392-aa5b-5cc2c7fe53d8)

# 4. 遇到的问题

一开始我使用 PowerShell 脚本进行安装，但后来这种下载方式因不明原因失效，因此改成了 EXE 安装程序。

# 5. 最终效果

如置顶链接