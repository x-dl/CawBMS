# CawBMS - 锂电池管理系统

## 🕹 简介

CawBMS是一套基于STM32F103和BQ76920的锂电池管理系统。

所有设计资料基于MIT协议开源，欢迎大家复刻，可做商业用途。

**请保留PCB、源码文件中的作者及Logo的相关信息。**

![https://github.com/fake-rick/caw-drive/blob/master/Docs/imgs/g20231004124547.png](https://github.com/fake-rick/caw-bms/blob/master/Docs/imgs/20231230223442.png)

![https://github.com/fake-rick/caw-bms/blob/master/Docs/imgs/20231230223503.png](https://github.com/fake-rick/caw-bms/blob/master/Docs/imgs/20231230223503.png)

## 🛠 功能

| 名称      | 开发状态 | 测试状态 |
| ------- | ---- | ---- |
| 初始化     | ✔    | ✔    |
| 短路保护    | ✔    | ❌    |
| 过流保护    | ✔    | ✔    |
| 过压保护    | ✔    | ✔    |
| 欠压保护    | ✔    | ✔    |
| 单节电压监测  | ✔    | ✔    |
| 电池组电压监测 | ✔    | ✔    |
| 电流监测    | ✔    | ✔    |
| SOC     | ❌    | ❌    |
| SOH     | ❌    | ❌    |
| 充电被动均衡  | ✔    |      |

## 📰 目录

* Docs: 项目相关文档

* GUI：上位机软件

* PCB：硬件设计

* Shell：相关外壳设计

* Firmware：固件
