# RDA8955

## About SoC

RDA8955L is a high performance, highly integrated system-on-chip solution for low cost, low power, GSM/GPRS application. Integrating all essential electronic components, including baseband, quad band RF transceiver, power management onto a single system on chip.

Built around a cost effective 32-bit XCPU RISC core running at up to 312MHz with 4k of Instruction cache and 4k of Data cache, RDA8955L offers plenty of processing power for multimedia applications. A high-performance proprietary 16/32-bit digital signal processing engine can further improve overall performance and user experience when performing complex multimedia tasks.

It is also packed with impressive connectivity for easy scalability of the system, allowing glue less interfaces to camera and multimedia companion chips, SDMMC Memory Cards and SPI devices, LCD modules and USB (slave, full speed).

RDA8955L is GPRS Class 12 enabled, and supports Full Rate (FR), Half Rate (HR), Enhanced Full Rate (EFR) voice coders. It also supports simultaneous dual network operation and integrates a SIM controller with integrated level shifters that can support two SIM cards

### Features

* Integrated power management unit, base-band, GSM transceiver, and audio module
* MCU subsystem
* RDA RISC Core
* 4 kByte Instruction Cache
* 4 kByte Data Cache with write back policy
* High-performance multi-layer AHB bus

## Supported Modules

* AiThinker A9/A9G
* Neoway M590
* Quectel MC65/MC25

More modules to be added soon.

## Flashing Instruction

Use coolwatcher to flash core firmware lod file.

## Device/Module Activation Instruction

Once the core firmware is flashed, Logicrom needs to be activated to run application firmware.

Following are simple steps to activate your device.

1. Register account on [waybyte.in](https://waybyte.in/register)
2. Click on [Register Free Device](https://waybyte.in/devices/register) from left menu
3. Enter device details
4. Flash Logicrom core firmware
5. Put a valid SIM card in device
6. Turn on the device, It should accquire the license\
   If device fail to do so, run "getlic" command from device console Port (USB Port 0 or Main UART) to try again.

If you face any issue, Please feel free to contact us @ support@waybyte.in or post your issue on github:

## See Also

* [Quick start guide](https://docs.logicrom.com/en/latest/book/quick_start.html)
* [API Documentation](https://docs.logicrom.com/en/latest/)
* [Code Examples](https://github.com/waybyte/platform-logicrom/tree/master/examples)
* [Free Logicrom License](https://waybyte.in/devices/register)
* [PlatformIO IDE](https://platformio.org/platformio-ide)
