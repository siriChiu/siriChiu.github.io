---
title: Linux查看日誌
date: 2023-08-15
categories:
- 筆記
tags:
- Linux
- Command
- Debug
---
Linux系統查看日誌的幾種指令:


<!--more-->
```
journalctl
```

> [journalctl︰查詢 systemd 日誌 | 管理指南 | SUSE Linux Enterprise Server 15](https://documentation.suse.com/zh-tw/sles/15-GA/html/SLES-all/cha-journalctl.html)
> 如果需要查看上一次開機的記錄訊息，請新增一個偏移參數。下面的範例將輸出上一次開機的訊息︰
> journalctl -b -1

```
dmesg
```
> [Linux dmesg 命令 | 菜鸟教程 (runoob.com)](https://www.runoob.com/linux/linux-comm-dmesg.html)

