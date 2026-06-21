# 每日嵌入式学习播客文稿和文档

从纯软件工程师到软硬一体嵌入式产品工程师的每日学习记录。

每天介绍一个 GitHub 嵌入式开源项目，包含源码陪读、概念解析、动手任务和豆包播客文稿。

## 项目目录

| 日期 | 项目 | 说明 |
|------|------|------|
| 2026-06-21 | [Bluejay](./Bluejay/) | Bluejay 是一套面向多旋翼无人机的数字电调（ESC）固件，运行在 SiLabs EFM8BB Busy Bee 微控制器上，用汇编语言实现无刷电机的高精度控制。 |
| 2026-06-20 | [WLED](./WLED/) | WLED 是一套在 ESP32/ESP8266 上控制可寻址 RGB LED 灯带、2D 点阵屏和 HUB75 面板的固件 |
| 2026-06-19 | [CherryUSB](./CherryUSB/) | CherryUSB 是一个轻量、高性能、可移植的嵌入式 USB 主机与设备协议栈，帮助 MCU 开发者以极小的代码量实现 USB 通信功能（如串口、U盘、键盘、音视频等）。 |
| 2026-06-18 | [QP_C](./QP_C/) | QP/C 是一个为 ARM Cortex-M 微控制器量身定制的轻量级实时事件框架，实现了异步事件驱动的活动对象/Actor 模型，结合了层次状态机。 |
| 2026-06-17 | [SimpleFOC](./SimpleFOC/) | SimpleFOC 是一个跨平台 Arduino 库，让任何 Arduino/STM32/ESP32 开发者只用几行代码就能给无刷直流电机和步进电机实现磁场定向控制。 |
| 2026-06-16 | [littlefs](./littlefs/) | littlefs 是 ARM 为微控制器设计的一个轻量、掉电安全、自带动态磨损均衡的文件系统，专为 SPI NOR Flash 等嵌入式存储介质而生。 |
| 2026-06-15 | [Klipper](./Klipper/) | Klipper 是一个把 3D 打印机运动规划放到通用计算机上、把精确定时执行留给一个或多个微控制器的 3D 打印固件项目。 |
| 2026-06-14 | [cib](./cib/) | cib 是一个 C++ 头文件库，它把嵌入式固件的组件注册、服务组合和回调绑定从运行期搬到编译期，用 constexpr/consteval 消除传统固件中"先初始化再使用"的运行时开销。 |
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
