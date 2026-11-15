# 虚拟化技术实践

## 项目介绍

使用 VMware Workstation Pro 搭建 Windows 测试环境，实践虚拟机创建、客户机安装和基础资源配置。

## 使用技术

- VMware Workstation Pro
- Windows 11 客户机

## 实践内容

### 1. 虚拟机创建

- 创建两台虚拟机：one、tow
- 在虚拟机中安装 Windows 11 客户机系统
- 使用独立的虚拟磁盘保存客户机数据

### 2. 资源配置

| 虚拟机 | 客户机 | CPU | 内存 | 网络模式 |
| --- | --- | --- | --- | --- |
| one | Windows 11 | 4 vCPU | 8 GB | NAT |
| tow | Windows 11 | 4 vCPU | 8 GB | NAT |

- 配置虚拟机的 CPU、内存和虚拟磁盘资源

### 3. 网络使用

- 两台虚拟机的网络适配器均配置为 NAT 模式。
- 了解 NAT、桥接等常见虚拟网络模式的区别

## 实践成果

搭建 2 台 Windows 11 虚拟机的个人测试环境，用于软件测试与实验。

![VMware Workstation 中名为 one 的虚拟机正在运行 Windows 11 桌面，左侧库中列有 one 与 tow 两台虚拟机](./VMware%20Workstation%20Pro.png)

## 学习收获

掌握虚拟机创建与基础管理流程，了解虚拟化资源分配和虚拟网络的基本概念。
