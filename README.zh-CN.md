# 你好，我是 Archi

[English](README.md)

**嵌入式系统 · PCB 设计 · 无线通信**

## 代表项目

| 项目 | 实际成果 | 审阅入口 |
| --- | --- | --- |
| [ESP32 毫米波盲区监测](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/blob/main/README.zh-CN.md) | 完成 60 GHz 雷达、双层 PCB 焊接和安卓客户端。安卓原始截图显示两个目标，左侧预警等级为 4/5。 | [演示](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/blob/main/demo/README.zh-CN.md) · [PCB 文件](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/blob/main/hardware/README.zh-CN.md) |
| [STM32 光伏板参数监测](https://github.com/YohtHill/pv-panel-monitor/blob/main/README.zh-CN.md) | 面包板原型在 10 kΩ 负载下显示 1.395 V，换算电流为 139 µA。CubeIDE 固件已通过构建。 | [接线与烧录](https://github.com/YohtHill/pv-panel-monitor/blob/main/README.zh-CN.md#最小复现) · [标定计划](https://github.com/YohtHill/pv-panel-monitor/blob/main/docs/validation.zh-CN.md) |
| [MPI + OpenMP Mandelbrot 并行渲染](https://github.com/YohtHill/mandelbrot-mpi-openmp/blob/main/README.zh-CN.md) | 原 4 vCPU 虚拟机渲染 800 × 600 图像，串行用时 0.725 s，四线程动态调度平均用时 0.1823 s，加速比 3.98 倍。 | [复现图像](https://github.com/YohtHill/mandelbrot-mpi-openmp/blob/main/README.zh-CN.md#复现默认图像) · [基准测试方法](https://github.com/YohtHill/mandelbrot-mpi-openmp/blob/main/README.zh-CN.md#9-结果) |

[<img src="https://raw.githubusercontent.com/YohtHill/esp32-bsd-radar-monitor-public/main/demo/assets/assembled-front-redacted.png" alt="已通电的 ESP32 雷达原型，屏幕和模块安装在手工焊接的 PCB 上" width="460">](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/blob/main/README.zh-CN.md#焊接完成的实物照片)

## 硬件与嵌入式项目

- STM32F103 采集温湿度和光照，由 Node-RED 看板显示。[STM32 物联网监测](https://github.com/YohtHill/iot-stm32-dht11-project/blob/main/README.zh-CN.md)
- 学习仓库记录 C 和微控制器外设练习，其中有 13 个可独立构建的 STM32F0 实验。[嵌入式学习索引](https://github.com/YohtHill/Embedded_Learning/blob/master/Software/STM32F0/README.md)

## 仿真与信号处理

- 300 MHz 十一单元八木模型的仿真实现增益为 13.26 dBi，前后比为 12.15 dB。仓库附 NEC-2 模型、扫参数据和方向图。[天线仿真](https://github.com/YohtHill/dipole-yagi-nec2-study/blob/main/README.zh-CN.md)
- 完成模拟均衡器七段仿真与三段面包板原型，附交流扫频和约 1 kHz 的实物示波器记录。[模拟图示均衡器](https://github.com/YohtHill/multisim-graphic-equalizer/blob/main/README.zh-CN.md)

## 技术栈

- **固件**涵盖 C/C++、STM32、ESP32、FreeRTOS 和外设驱动。
- **硬件**涵盖原理图、PCB 布线、焊接和板级调试。
- **系统联调**使用 BLE、UWB、Wi-Fi、Android 和 Node-RED，借助串口日志、示波器和逻辑分析仪验证接口。

## 目前在做

我的毕业设计是基于 STM32 的 UWB/BLE 低功耗接入系统，涉及自制 PCB、测距和无线授权。我就读于福建师范大学与哈德斯菲尔德大学合作的电子信息工程项目。实习期间参与过指纹模组原理图与 PCB 设计、电源纹波测量和硬件测试。

## 联系方式

[LinkedIn](https://www.linkedin.com/in/jiakun-pi-170277393)
