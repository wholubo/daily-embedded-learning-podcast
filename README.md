# 每日嵌入式学习

从纯软件工程师到软硬一体嵌入式产品工程师的每日学习记录。

由 Hermes Agent 每日定时任务自动生成，每天介绍一个 GitHub 嵌入式开源项目，包含源码陪读、概念解析、动手任务和豆包播客文稿。

> 🔒 本仓库为私有仓库，仅供个人学习使用。

## 项目目录

| 日期 | 项目 | 说明 |
|------|------|------|
| 2026-06-09 | [probe-rs](./probe-rs/) | Rust 嵌入式调试工具集，替代 OpenOCD |
| 2026-06-08 | [PX4 Autopilot](./PX4_Autopilot/) | 开源无人机飞控固件 |
| 2026-06-07 | [Apache NuttX](./Apache_NuttX/) | 类 POSIX 实时操作系统 |
| 2026-06-06 | [Zephyr](./Zephyr/) | Linux 基金会 RTOS |
| 2026-06-05 | [Embassy](./Embassy/) | Rust 异步嵌入式框架 |
| 2026-06-04 | [Tasmota](./Tasmota/) | ESP 系列开源固件 |
| 2026-06-03 | [Marlin](./Marlin/) | 3D 打印机固件 |
| 2026-06-02 | [esp-hal](./esp-hal/) | ESP32 硬件抽象层 |
| 2026-06-01 | [OpenBLT](./OpenBLT/) | 开源 Bootloader |
| 2026-05-31 | [FrameworkEmbeddedController](./FrameworkEmbeddedController/) | Framework 笔记本嵌入式控制器 |
| 2026-05-30 | [OpenSK](./OpenSK/) | Rust FIDO2 安全密钥 |
| 2026-05-29 | [Ariel OS](./Ariel_OS/) | Rust IoT 操作系统 |
| 2026-05-28 | [TinyUSB](./TinyUSB/) | 嵌入式 USB 协议栈 |
| 2026-05-27 | [RMK](./RMK/) | Rust 机械键盘固件 |
| 2026-05-26 | [InfiniTime](./InfiniTime/) | PineTime 智能手表固件 |
| 2026-05-25 | [ZMK](./ZMK/) | ZMK 蓝牙键盘固件 |
| 2026-05-24 | [ZSWatch](./ZSWatch/) | Zephyr 智能手表 |
| 2026-05-23 | [Meshtastic firmware](./Meshtastic_firmware/) | LoRa 去中心化通信固件 |
| 2026-05-22 | [Meshtastic firmware](./Meshtastic_firmware/) | LoRa 去中心化通信固件 |
| 2026-05-21 | [Trice](./Trice/) | 嵌入式超轻量 printf 调试工具 |

### 实践项目

| 日期 | 项目 |
|------|------|
| 2026-06-06 | [串口日志系统 + Ring Buffer](./串口日志系统_RingBuffer/) |

### 学习复盘

| 日期 | 内容 |
|------|------|
| 2026-06-07 | [每周嵌入式学习复盘](./每周复盘/) |

## 文件说明

每个项目文件夹包含：
- `YYYY-MM-DD_学习报告.md` — 包含 GitHub 链接、技术架构分析、源码陪读、10 个概念卡片、动手任务
- `YYYY-MM-DD_豆包播客稿.txt` — 基于学习报告改写的中文口播文稿，可直接用于豆包 AI 生成播客

### 原始记录

[cron-output-raw/](./cron-output-raw/) — Hermes cron 任务的原始运行输出，包含 prompt 指令和完整响应。

## 自动化

本仓库内容由 [Hermes Agent](https://hermes-agent.nousresearch.com) 每日定时任务自动生成：

- **每日嵌入式学习** — 每天 20:30 生成学习报告和播客稿
- **每周实践项目** — 每周六 09:30 启动周末动手项目
- **每周学习复盘** — 每周日 20:00 生成本周学习复盘

文件通过 Telegram + Weixin 双通道推送，同时归档至本仓库。
