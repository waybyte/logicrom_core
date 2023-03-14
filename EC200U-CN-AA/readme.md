# Quectel EC200U-CN-AA

## About Module

Quectel EC200U series is a series of the latest LTE Cat 1 module optimized specially for M2M and IoT applications. It delivers maximum data rates up to 10 Mbps downlink and 5 Mbps uplink.

### Features

* LTE Cat 1 module optimized for M2M and IoT applications
* Worldwide LTE, GSM/GPRS coverage
* Abundant functional interfaces
* Support analog audio
* Built-in GNSS
* Bluetooth
* DFOTA
* High performance

### Frequency Bands of EC200U-CN QuecOpen Module

* LTE-FDD: B1/B3/B5/B8
* LTE-TDD: B34/B38/B39/B40/B41
* GSM: 900 MHz/1800 MHz
* GNSS: GPS, BeiDou
* Bluetooth 4.2

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
