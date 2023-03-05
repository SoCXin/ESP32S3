# [ESP32-S3](https://doc.soc.xin/ESP32-S3)

[![Build Status](https://github.com/SoCXin/ESP32S3/workflows/idf/badge.svg)](https://github.com/SoCXin/ESP32S3/actions/workflows/idf.yml)

* [Espressif](https://www.espressif.com/): [Xtensa LX7](https://docs.soc.xin/espressif/index.html#esp-lx7)
* [L3R3](https://github.com/SoCXin/Level): 2x 240 MHz (1181.6 CoreMark) , [￥10.39 (QFN56)](https://item.szlcsc.com/3198290.html)

## [简介](https://github.com/SoCXin/ESP32S3/wiki)

[ESP32S3](https://github.com/SoCXin/ESP32S3) 是一款集成 2.4 GHz Wi-Fi 和 Bluetooth 5 (LE) 的 MCU 芯片，支持远距离模式 (Long Range)。ESP32-S3 搭载 Xtensa® 32 位 LX7 双核处理器，主频高达 240 MHz，内置 512 KB SRAM (TCM)，具有 45 个可编程 GPIO 管脚和丰富的通信接口。ESP32-S3 支持更大容量的高速 Octal SPI flash 和片外 RAM，支持用户配置数据缓存与指令缓存。

[![sites](docs/ESP32-S3.png)](https://www.espressif.com/zh-hans/products/socs/ESP32-S3)


### 关键参数

* 240 MHz Xtensa® LX7 dual core
* 512 KB SRAM (TCM) + 384 KB ROM + 4/8/16/32 SPI Flash
* Wi-Fi4 + BLE 5
* USB OTG FS
* 2 × SDIO 主机
* DMA 5 接收 + 5 发送
* 44 x GPIO，JTAG 接口
* 超低功耗协处理器RISC-V (ULP)
* 硬件加密加速器可支持 AES-128/256、Hash、RSA、HMAC，RNG

ESP32-S3 芯片有 45 个物理通用输入输出管脚 (GPIO Pin)。每个管脚都可用作一个通用输入输出，或连接一个内部外设信号。利用 GPIO 交换矩阵、IO MUX 和 RTC IO MUX，可配置外设模块的输入信号来源于任何的 GPIO管脚，并且外设模块的输出信号也可连接到任意 GPIO 管脚。

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/ESP32S3)

[ESP32-S3](https://github.com/SoCXin/ESP32S3) 使用成熟的[ESP-IDF](https://github.com/espressif/esp-idf)，[Wi-Fi MCU竞品](https://doc.soc.xin/application/wifi)包括:

* Realtek Ameba [RTL8722DM](https://github.com/SoCXin/RTL8722DM)
* 320MHz RISC-V Dual Core [BK7256](https://github.com/SoCXin/BK7256)
* 320MHz RISC-V Dual Core [AC7916](https://github.com/SoCXin/AC7916)
* 320MHz RISC-V QFN56 [BL618](https://github.com/SoCXin/BL618)
* 240MHz XT804 QFN56 [W801](https://github.com/SoCXin/W801)
