# Neoway N58

## About Module

N58 is an industrial 4G module that is developed on Spectrum chipset. Its dimensions are 30 x 28 mm x 2.6 mm. This high-performance data transmission module supports GSM, FDD-LTE, TDD-LTE (Cat 1) network modes, provides various hardware interfaces, supports audio and video functions and BT connectivity, and optionally supports GNSS. This module is easy for customers to develop applications and is applicable to AMR, in-vehicle terminals, POS, industrial routers, etc.

### Features

* Package: LCC+LGA 
* Dimension (mm): (30.0±0.15) mm × (28.0±0.15) mm × (2.6±0.2) mm
* Optimized for M2M and IoT applications
* GNSS, Audio, Bluetooth4.2, Camera, LCD, and FOTA
* Applicable to smart metering, sharing equipment, tracker, environmental monitoring, etc
* Used in most regions including China, EMEA, Latin America and SEA where LTE networks are deployed

### Frequency Bands

* N58-CA
  * LTE Cat1: B1, B3, B5, B8, B34, B39, B40, B41
  * GSM/GPRS: 900/1800 MHz
* N58-EA
  * LTE Cat1: B1, B3, B5, B7, B8, B20, B28, B38, B40, B41
  * GSM/GPRS: 900/1800 MHz
* N58-LA
  * LTE Cat1: B1, B2, B3, B4, B5, B7, B8, B28, B66, B38, B40, B41
  * GSM/GPRS: 850/900/18001900 MHz
* Bluetooth 4.2 (BR/EDR)

## Flashing Instruction

Use logicrom Flasher or Flashtool provided by module vendor to flash Logicrom core pac file.

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
