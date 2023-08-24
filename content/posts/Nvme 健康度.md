---
title: 檢查Nvme健康度
date: 2023-08-15
categories:
- 筆記
tags:
- Linux
- Command
- Debug
---
檢查Nvme健康度的兩種指令:

<!--more-->

## Commands
```
nvme smart-log /dev/nvme0n1
```
```
smartctl -a /dev/nvme0n1
```
## Reference
[Using NVMe Command Line Tools to Check NVMe Flash Health (percona.com)](https://www.percona.com/blog/using-nvme-command-line-tools-to-check-nvme-flash-health/)

