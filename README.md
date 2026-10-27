<div align="center">

# GGYDESK 运维工具箱  

Galactic Ghost Yard   

**Windows 运维工作台 — 远程连接 · 文件排查 · 抓包分析 · 流量测试**

![Version](https://img.shields.io/badge/version-1.9.6-blue) ![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey) ![License](https://img.shields.io/badge/license-commercial-orange)

[下载最新版](../../releases/latest) · [更新日志](../../releases)

</div>

---

## 这是什么

GGYDESK 把日常运维最常用的几类操作集中到一个桌面应用里，装完即用，不需要装一堆零散工具。

## 下载安装

到 [**Releases 页面**](../../releases/latest) 下载：

| 文件 | 说明 |
|---|---|
| `GGYDesk-Setup-1.9.6.exe` | Windows 安装包（x64，向导式安装） |
| `SHA256SUMS-1.9.6.txt` | SHA256 校验和 |

安装前可校验文件完整性：

```powershell
Get-FileHash .\GGYDesk-Setup-1.9.6.exe -Algorithm SHA256
```

## 功能一览

| 模块 | 能力 |
|---|---|
| 🔌 **远程会话** | SSH（断线重连 / 跳板 / 转发）、远程桌面、SFTP、串口 Console、Telnet、终端分屏、宏录制、命令补全 |
| 🕵️ **文件定位** | 实时进程管理、文件审计（来源追溯 / 哈希取证）、启动项与注册表分析、系统日志分析、Dump / 蓝屏分析 |
| 🌐 **流量抓包** | 流量生成、PCAP 回放、网络抓包、历史记录分析 |
| 📦 **批量处理** | 命令批量执行、文件分发、Ping 探测 |
| 🗂 **内置服务** | HTTP / FTP / SFTP 文件服务、更新代理（SOCKS5 中转） |
| 🛢 **数据库** | MySQL / SQLServer / PostgreSQL 连接与 SQL 执行 |

## 系统要求

- Windows 10 / 11 / Server 2016+（x64）
- 抓包、保护目录、系统日志分析等功能需要管理员权限运行

## 授权说明

- **7 天免费试用**，无需联网激活
- 正式授权采用 **机器码 + 离线签名授权文件**，支持换机迁移
- 联系方式见软件"关于"页面

---

> 本仓库仅用于发布 GGYDESK 安装包，不含源代码。
