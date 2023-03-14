# Mediatek MT2503/MT6261

### About SoC

MT2503A is a feature-rich and extremely powerful single-chip solution for high-end
GSM/GPRS capability. Based on the 32-bit ARM7EJ-STM RISC processor, MT2503A’s
superb processing power, along with high bandwidth architecture and dedicated hardware
support, provides a platform for high-performance GPRS Class 12 MODEM
application and leading-edge multimedia applications.

MT2503A also features:
* A highly integrated Bluetooth transceiver which is fully compliant with Bluetooth specification v3.0.
* A FM receiver supporting both audio broadcast de-modulation and RDS/RBDS data decoding.

MT2503 in a nutshell is MT6261 (baseband SoC) + MT3333 (GNSS SoC)

### Features

* Integrated voice-band, audio-band and base-band analog front-end
* Integrated full-featured power management unit
* ARM7EJ-S 32-bit RISC processor
* 3 UARTs with hardware flow control and supports baud rate up to 921,600 bps
* FS/LS USB 1.1 device controller
* SD/MMC Host controller
* I2C, SPI, PWM, ADC, RTC, GPIO

## Supported Modules

* Quectel MC20/MC60/MC20U
* Quectel M66/M66DS/M26
* Quectel M56
* SIMCOM SIM868

You can try this firmware on other MT2503 or MT6261 based modules.

## Flashing Instruction

Use Logicrom GSM Flasher to flash core firmware using PlatformIO IDE. For more
information refer to [core flashing guide](https://docs.logicrom.com/en/latest/book/flashing.html#core-firmware-re-flash)

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
