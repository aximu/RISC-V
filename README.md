# RISC-V

记录有意思的RISC-V开源项目

### RISC-V SOC

1. zqh_riscv
 https://github.com/zhouqinghua/zqh_riscv
 zqh_riscv是一套开源SoC开发平台，核心部分包含处理器core、cache、片内互联总线、中断控制器、memory控制器、片内总线slave接口、片内总线master接口、片内总线device、片外总线device、时钟复位控制器、  debug控制器。还包含了SOC功能验证/仿真相关的脚本程序和测试用例。除了可以运行电路仿真，平台还提供了ASIC综合脚本，可以对生成的电路做逻辑综合。

### RISC-V模块

1. FPU
https://github.com/pulp-platform/fpnew
FPnew - New Floating-Point Unit with Transprecision Capabilities  
参数化浮点单元，支持标准RISC-V格式和操作以及转译格式，用SystemVerilog编写。允许为各种用例生成FP硬件单元。尽管 FPU 主要设计用于 RISC-V 处理器，但 FPU 或其子模块可以很容易地用于其他环境。我们的设计旨在符合IEEE 754-2008标准

### 平台

1. PULP Platform
 https://github.com/pulp-platform  https://pulp-platform.org/index.html
　open hardware

### ISA 扩展

1. CONV23　卷积运算指令
*https://github.com/QmppmQ/riscv
基于riscv指令集处理器ri5cy(https://github.com/openhwgroup/cv32e40p)
通过添加自定义卷积指令加速卷积运算。
Artical:"Customized Instruction on RISC-V for Winograd-Based Convolution Acceleration"
2. AES
   https://github.com/mjosaarinen/lwaes_isa
   "A Lightweight ISA Extension for AES and SM4"


### RISC-V Simulator

1. GVSoC
   https://github.com/pulp-platform/pulp-sdk
   GVSoC: A Highly Configurable, Fast and Accurate Full-Platform Simulator for RISC-V based IoT Processors
