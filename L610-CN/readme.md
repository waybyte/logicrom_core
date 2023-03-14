# Fibocom L610-CN

## About Module

Fibocom Cat 1 modules are designed for medium-rate IoT connections, covering the network frequency bands of major operators in Asia, Europe and Latin America, formed as both LCC+LGA and MiniPCIe packages. L610 is a 4G LTE Cat 1 bis wireless module for the Internet of Things applications, supporting LTE, GSM dual-mode communication, VoLTE, audio, camera, LCD, keypad and other functions. In addition, the 4G LTE Cat 1 module provides universal interfaces such as USB / UART / SPI / I2C / SDIO to meet various application demands of the IoT industry.

### Features

* Package: LCC+LGA 
* Dimension (mm): 31.0x28.0x2.35 
* Abundant functional interfaces
* Bluetooth
* DFOTA
* USB

### Frequency Bands

* LTE-FDD: Band 1/3/5/8 
* LTE-TDD: Band 34/39/40/41 
* GSM: 900/1800MHz
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
