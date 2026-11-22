# Hi, I'm Archi

[简体中文](README.zh-CN.md)

**Embedded systems · PCB design · wireless communication**

I'm an Electronic Information Engineering student in the joint programme between Fujian Normal University and the University of Huddersfield. I build connected devices from schematic and PCB through firmware, board bring-up and system validation.

## Selected projects

| Project | Stack | Result and status |
| --- | --- | --- |
| [ESP32 millimeter-wave blind-spot monitor](https://github.com/YohtHill/esp32-bsd-radar-monitor-public) | ESP32, MS60 60 GHz radar, EasyEDA Pro, Android Bluetooth SPP | Soldered two-layer prototype. An archived Android capture shows two targets and a left-side warning at 4/5. Includes PCB source, Gerbers and demo. |
| [STM32 photovoltaic panel monitor](https://github.com/YohtHill/pv-panel-monitor) | STM32F042, 12-bit ADC, SPI ST7735, STM32CubeIDE | Breadboard prototype showed approximately 1.395 V under a 10 kΩ load and a computed 139 µA. The firmware builds. Instrument accuracy still needs calibration. |
| [300 MHz dipole and Yagi-Uda study](https://github.com/YohtHill/dipole-yagi-nec2-study) | NEC-2, 4nec2, Python | The 11-element design reached 13.26 dBi simulated realized gain and 12.15 dB front-to-back ratio at 300 MHz. Models, sweep data and plots are available. |
| [Three- and seven-band audio equalizer](https://github.com/YohtHill/multisim-graphic-equalizer) | Multisim, LTspice, LM741 | Seven-band simulation and a solderless three-band prototype. Includes AC sweeps and a bench oscilloscope capture near 1 kHz. |
| [MPI + OpenMP Mandelbrot benchmark](https://github.com/YohtHill/mandelbrot-mpi-openmp) | C, MPI, OpenMP | Dynamic scheduling reached 3.98× the serial baseline in the documented four-vCPU run. The tested configurations produced matching image hashes. |

## What I'm working on

My graduation project is an STM32-based UWB/BLE low-power access system. It brings together ranging, wireless authorisation and custom PCB integration. I'm also building a [collection of C, STM32 and hardware experiments](https://github.com/YohtHill/Embedded_Learning), including [13 independently buildable STM32F0 labs](https://github.com/YohtHill/Embedded_Learning/blob/master/Software/STM32F0/README_EN.md).

## Engineering practice

- **Firmware** — C/C++, STM32, ESP32, FreeRTOS and MCU peripherals.
- **Hardware** — schematic capture, PCB layout, soldering and board bring-up.
- **Integration** — BLE, UWB and Wi-Fi, with serial, scope and logic-analyser checks.

My internship work has included fingerprint-module schematic and PCB design, supply-ripple measurement and hardware testing. [LinkedIn](https://www.linkedin.com/in/jiakun-pi-170277393)
