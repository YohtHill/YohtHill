# Hi, I'm Archi

[简体中文](README.zh-CN.md)

**Embedded systems · PCB design · wireless communication**

## Selected projects

| Project | Result | How to review it |
| --- | --- | --- |
| [ESP32 millimeter-wave blind-spot monitor](https://github.com/YohtHill/esp32-bsd-radar-monitor-public) | Built and soldered a two-layer carrier for a 60 GHz radar and an Android client. An archived Android capture shows two targets and a left-side warning at 4/5. | [Demo](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/tree/main/demo) · [PCB files](https://github.com/YohtHill/esp32-bsd-radar-monitor-public/tree/main/hardware) |
| [STM32 photovoltaic panel monitor](https://github.com/YohtHill/pv-panel-monitor) | The breadboard display showed 1.395 V across a 10 kΩ load, with a calculated current of 139 µA. The CubeIDE firmware builds. | [Wiring and flashing](https://github.com/YohtHill/pv-panel-monitor#minimal-reproduction) · [Calibration plan](https://github.com/YohtHill/pv-panel-monitor/blob/main/docs/validation.md) |
| [MPI + OpenMP Mandelbrot renderer](https://github.com/YohtHill/mandelbrot-mpi-openmp) | The 800 × 600 render took 0.725 s with serial C and 0.1823 s on average with dynamic four-thread scheduling in the original four-vCPU VM, a 3.98× speed-up. | [Reproduce the image](https://github.com/YohtHill/mandelbrot-mpi-openmp#reproduce-the-default-image) · [Benchmark method](https://github.com/YohtHill/mandelbrot-mpi-openmp#9-results) |

[<img src="https://raw.githubusercontent.com/YohtHill/esp32-bsd-radar-monitor-public/main/demo/assets/assembled-front-redacted.png" alt="Powered ESP32 radar prototype with the displays and modules mounted on the hand-soldered PCB" width="460">](https://github.com/YohtHill/esp32-bsd-radar-monitor-public#soldered-prototype-photos)

## Embedded and hardware projects

- An STM32F103 reads temperature, humidity and light level for a Node-RED dashboard. [STM32 IoT monitor](https://github.com/YohtHill/iot-stm32-dht11-project)
- My learning repository documents C and MCU peripherals through small exercises, including 13 independently buildable STM32F0 labs. [Embedded Learning index](https://github.com/YohtHill/Embedded_Learning/blob/master/Software/STM32F0/README_EN.md)

## Simulation and signal processing

- The 11-element 300 MHz Yagi-Uda model reached 13.26 dBi simulated realized gain and a 12.15 dB front-to-back ratio. The repository includes the NEC-2 models, sweep data and plots. [Antenna study](https://github.com/YohtHill/dipole-yagi-nec2-study)
- The equalizer project includes seven-band simulation, a three-band breadboard prototype, AC sweeps and an oscilloscope capture near 1 kHz. [Analog graphic equalizer](https://github.com/YohtHill/multisim-graphic-equalizer)

## Technical skills

- **Firmware** — C/C++, STM32, ESP32, FreeRTOS and peripheral drivers.
- **Hardware** — schematic capture, PCB layout, soldering and board bring-up.
- **System integration** — BLE, UWB, Wi-Fi, Android and Node-RED. I use serial logs, oscilloscopes and logic analysers to check interfaces.

## Current work

My graduation project is an STM32-based UWB/BLE low-power access system with custom PCBs, ranging and wireless authorisation. I study Electronic Information Engineering in the joint programme between Fujian Normal University and the University of Huddersfield. My internship work has included fingerprint-module schematic and PCB design, supply-ripple measurement and hardware testing.

## Contact

[LinkedIn](https://www.linkedin.com/in/jiakun-pi-170277393)
