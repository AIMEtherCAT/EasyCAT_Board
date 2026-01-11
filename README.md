<div align="center">
  <img src="EasyCAT_logo.png" width="300" alt="EasyCAT Logo">
</div>

# EasyCAT

[English](#english) | [中文](#chinese)

`<a name="english"></a>`

## 🇬🇧 English

**EasyCAT** aims to provide **simple**, **low-cost**, **easy-to-use** EtherCAT development boards designed for **rapid development**.

Hardware technical support is provided by **HyperBot Robotics** and **Inpulse Electronic Technology**.

### Products

#### 1. PiCAT

PiCAT is an EtherCAT baseboard designed to match the form factor of the Raspberry Pi and other single-board computers.

* **Form Factor**: Matches Raspberry Pi size.
* **Connectivity**: 40 GPIOs available.
* **ESC Chip**: Uses the **AX58100** EtherCAT Slave Controller.
* **Modular Core**: Features a replaceable **STM32 core** module using the **NVMe 2230** connection standard.
* **Expansions**: Optional modules include a Power Supply Board, IMU Expansion Board, and Servo Control Board.

#### 2. MicroCAT

MicroCAT is a miniaturized version of the PiCAT, designed for compact applications.

* **Design**: Features a high-quality **aluminum case**.
* **Features**: Compact size (derived from PiCAT).
* **Note**: Does not include expandable GPIOs.

### Repository Structure

* `PiCAT_AX58100/` - Resources for the PiCAT board.
* `MicroCAT_AX58100/` - Resources for the MicroCAT board.
* `STM32_CORE/` - Firmware and design files for the removable STM32 core module.

### Maintainer
*   **Email**: fuhua.jia [at] outlook [dot] com

---

`<a name="chinese"></a>`

## 🇨🇳 中文

**EasyCAT** 旨在提供**简单的**、**低成本的**、**易用的**、便于**快速开发**的 EtherCAT 开发板。

本项目由 **海博柔科机器人** 和 **因铂斯电子科技公司** 提供硬件技术支持。

### 主要产品

#### 1. PiCAT

PiCAT 是一款 EtherCAT 底板，设计大小与树莓派（Raspberry Pi）等单板机一致。

* **外形尺寸**: 与树莓派等单板机大小一致。
* **扩展性**: 具有 40 个 GPIO。
* **ESC 方案**: 使用 **AX58100** 作为 EtherCAT 从站控制器芯片。
* **模块化核心**: 可更换 **STM32 核心**，核心板采用 **NVMe 2230** 硬盘规格接口，方便更换与升级。
* **可选配件**: 提供供电板、IMU 扩展板以及舵机控制板等多种扩展选择。

#### 2. MicroCAT

MicroCAT 是 PiCAT 的微型化版本，专为紧凑型应用设计。

* **设计**: 配备优质**铝合金外壳**。
* **特点**: 体积小巧。
* **注意**: 不具备可扩展的 GPIO。

### 仓库结构

* `PiCAT_AX58100/` - PiCAT 开发板相关资源。
* `MicroCAT_AX58100/` - MicroCAT 开发板相关资源。
* `STM32_CORE/` - 可更换 STM32 核心模块的固件与设计文件。

### 维护人
*   **邮箱**: fuhua.jia [at] outlook [dot] com
