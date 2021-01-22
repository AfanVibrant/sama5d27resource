# SAMA5D27 Sharing/SAMA5D27分享

* Introduction介绍
  - SAMA5D27 Key Features/SAMA5D27芯片特性
* SAMA5D2 Boot/SAMA5D2启动流程
  - Boot Sequence启动顺序
  - Boot Configuration启动配置
  - SAM-BA Mode/SAM-BA模式介绍
* SAMA5D2 IO Assignment/SAMA5D2 IO管脚分配
  - IO Pin Map Description/看懂SAMA5D2 IO管脚功能分配图
  - IO Set/IO功能分组设置
* SAMA5D2 Linux Development/搭建SAMA5D2 Linux开发环境
  - Resource Center-Linux4SAM/资源中心-Linux4SAM
  - AT91bootstrap/AT91bootstrap介绍
  - U-boot/U-boot介绍
  - Linux Kernel/Linux内核介绍
  - Cross-Development Toolchains/交叉编译工具链
* Yocto or Buildroot/选择Yocto还是Buildroot
  - Yocto Introduction/Yocto介绍
  - Buildroot Introduction/Buildroot介绍
  - Build your Yocto SDK/编译Yocto SDK
  - Build Buildroot/编译Buildroot
* Programming/烧录说明
  - Programming with SAM-BA/使用SAM-BA进行烧录
  - SAM-BA Script Introduction/SAM-BA烧录脚本说明
* Your First Linux Application with Yocto/基于Yocto开发你的第一个Linux应用程序
  - Install Yocto SDK/安装Yocto SDK
  - Eclipse Configuration/Eclipse的配置
  - Debug with GDB/使用GDB进行代码调试
* Your First Bare-metal Project/你的第一个裸跑工程
  - atmel-software package
  - Harmony 3
  - FreeRTOS demo
* uCos-III RTOS On SAMA5D2/在SAMA5D2上跑uCos-III RTOS
  - uCos-III Introduction/uCos-III介绍
  - Download Source Code/下载源码
  - Porting Guide/移植指南
* ThreadX RTOS On SAMA5D2/在SAMA5D2上跑ThreadX RTOS
  - ThreadX Introduction/ThreadX介绍
  - Download Source Code/下载源码
  - Porting Guide/移植指南
* RT-Thread RTOS On SAMA5D2/在SAMA5D2上跑RT-Thread RTOS
  - RT-Thread Introduction/ThreadX介绍
  - Download Source Code/下载源码
  - Porting Guide/移植指南
  - LWIP Porting on RT-Thread/LWIP在RT-Thread上的移植
* NuttX RTOS On SAMA5D2/在SAMA5D2上跑NuttX RTOS
  - NuttX Introduction/NuttX介绍
  - Download Source Code/下载源码
  - Cross Compile/交叉编译
  - Debug with OpenOCD/使用OpenOCD调试源码
  - Adding Maxtouch Driver/添加Maxtouch驱动
  - Running LVGL GUI on SAMA5D2/在SAMA5D2上运行LVGL GUI
  - Running GuiLite GUI on SAMA5D2/在SAMA5D2上运行GuiLite GUI
  - Running Cairo on SAMA5D2/在SAMA5D2上运行Cairo 2D图形引擎
  - Multi-Layer Display Support on SAMA5D2/SAMA5D2上多图层显示驱动支持
  - Running EtherCAT Master on SAMA5D2/在SAMA5D2上运行EtherCAT主站协议
  - Running CAN Socket on SAMA5D2/在SAMA5D2上运行socket CAN
  - Running SQLite3 on SAMA5D2/在SAMA5D2上运行SQLite3
  - Adding MicroPython Support/添加对MicroPython的支持
  - Adding Camera Support/添加摄像头驱动支持
  - Adding TensorFlow Lite Support/添加TensorFlow Lite的支持
  - TensorFlow Lite demo/TensorFlow Lite演示
  - Adding OpenMV Support/添加OpenMV的支持
  - Adding MQTT Support/添加MQTT的支持

# INTRODUCTION介绍

The SAMA5D2 series is a high-performance, ultra-low-power Arm Cortex-A5
CPU-based embedded microprocessor (MPU) running up to 500 MHz, with support
for multiple memories such as DDR2, DDR3L, LPDDR2, LPDDR3, and QSPI and
e.MMC Flash. The devices integrate powerful peripherals for connectivity
and user interface applications, and offer advanced security functions
(Arm TrustZone, tamper detection, secure data storage, etc.), as well
as high-performance crypto accelerators AES, SHA and TRNG.

## Key Features