# 你好，我是 Archi

[English](README.md)

**嵌入式系统 · PCB 设计 · 无线通信**

我就读于福建师范大学与哈德斯菲尔德大学合作的电子信息工程项目。我的项目通常从原理图和 PCB 开始，经过固件开发、板级调试，最后验证软硬件联动。

## 代表项目

| 项目 | 技术栈 | 成果与状态 |
| --- | --- | --- |
| [ESP32 毫米波盲区监测](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/blob/main/README.zh-CN.md) | ESP32、MS60 60 GHz 雷达、嘉立创 EDA Pro、安卓蓝牙 SPP | 双层 PCB 已打板焊接。安卓原始截图显示两个目标及左侧 4/5 级预警。仓库包含 PCB 工程、Gerber 和演示。 |
| [STM32 光伏板监测](https://github.com/YohtHill/pv-panel-monitor/blob/main/README.zh-CN.md) | STM32F042、12 位 ADC、SPI ST7735、STM32CubeIDE | 面包板原型在 10 kΩ 负载下显示约 1.395 V，换算电流为 139 µA。固件已通过构建，测量精度仍待标定。 |
| [300 MHz 偶极子与八木天线](https://github.com/YohtHill/dipole-yagi-nec2-study/blob/main/README.zh-CN.md) | NEC-2、4nec2、Python | 十一单元模型在 300 MHz 的仿真实现增益为 13.26 dBi，前后比为 12.15 dB。附模型、扫参数据和方向图。 |
| [三段与七段模拟均衡器](https://github.com/YohtHill/multisim-graphic-equalizer/blob/main/README.zh-CN.md) | Multisim、LTspice、LM741 | 完成七段仿真及三段面包板原型，附交流扫频和约 1 kHz 的实物示波器记录。 |
| [MPI + OpenMP Mandelbrot 并行渲染](https://github.com/YohtHill/mandelbrot-mpi-openmp/blob/main/README.zh-CN.md) | C、MPI、OpenMP | 原四核虚拟机实验中，动态调度相对串行基线达到 3.98 倍加速。测试配置生成的图像哈希一致。 |

## 目前在做

我的毕业设计是基于 STM32 的 UWB/BLE 协同低功耗接入系统，主要涉及测距、无线授权和自制 PCB 集成。我也在 [Embedded Learning](https://github.com/YohtHill/Embedded_Learning) 记录 C、STM32 与硬件实验，其中包含 [13 个可独立构建的 STM32F0 实验](https://github.com/YohtHill/Embedded_Learning/blob/master/Software/STM32F0/README.md)。

## 工程实践

- **固件**涵盖 C/C++、STM32、ESP32、FreeRTOS 及常用 MCU 外设。
- **硬件**涵盖原理图、PCB 布线、焊接及板级调试。
- **联调**使用 BLE、UWB、Wi-Fi，并借助串口、示波器和逻辑分析仪验证链路。

实习中参与过指纹模组原理图与 PCB 设计、电源纹波测量和硬件测试。[LinkedIn](https://www.linkedin.com/in/jiakun-pi-170277393)
