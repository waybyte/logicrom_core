# Quectel EC100Y-CN-AA

## About Module

EC100Y-CN is the latest LTE Cat 1 wireless communication module launched by Mobile Communication, which supports a maximum downlink rate of 10 Mbps and a maximum uplink rate of 5 Mbps

It has high cost performance; At the same time, the package is compatible with LTE Cat 1/Cat 4 EG91 and EG95 series modules, LTE Cat M1/Cat NB1

BG36 module and UMTS/HSPA+UG35/UG96 module realize seamless switching between 3G and 4G networks.

## Features

* LTE Cat 1 module optimized for M2M and IoT applications
* Worldwide LTE, GSM/GPRS coverage
* Support FOTA remote upgrade function*
* Super high cost performance
* Rich multimedia hardware interfaces to meet intelligent applications

### Frequency Bands

* LTE-FDD: B1/B3/B5/B8
* LTE-TDD: B34/B38/B39/B40/B41
* GSM: 900/1800 MHz

## Flashing Instruction

Use logicrom Flasher, Aboot or Flashtool provided by module vendor to flash Logicrom core zip file.

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
