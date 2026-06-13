# 每日嵌入式学习播客文稿和文档

从纯软件工程师到软硬一体嵌入式产品工程师的每日学习记录。

每天介绍一个 GitHub 嵌入式开源项目，包含源码陪读、概念解析、动手任务和豆包播客文稿。

## 项目目录

| 日期 | 项目 | 说明 |
|------|------|------|
| 2026-06-13 | [MCUboot](./MCUboot/) | MCUboot 是一个为 32 位微控制器设计的通用安全引导加载程序，让设备可以在运行时安全地升级固件，同时验证启动镜像的完整性和真实性，防止被篡改或被刷入恶意固件。 |
| 2026-06-11 | [RIOT_OS](./RIOT_OS/) | RIOT OS 是一个面向物联网与微控制器设备的开源实时操作系统，目标是在 8 位、16 位、32 位 MCU 上提供统一、低功耗、模块化、带网络能力的嵌入式软件平台。 |
| 2026-06-10 | [MicroPython](./MicroPython/) | Python 3 的嵌入式微控制器实现 |
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
