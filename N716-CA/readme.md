# Neoway N716

## About Module

N716 is an LTE Cat 1 module optimized specially for M2M and IoT applications. Adopting the 3GPP Rel.13 LTE technology,
it delivers 10Mbps downlink and 5Mbps uplink data rates. The N716 series can be used in regions including China, SEA
and India where LTE networks are deployed


### Features

* Package: LCC+LGA 
* Dimension (mm): 19.6 mm × 19.6 mm × 2.45 mm
* Optimized for M2M and IoT applications
* GNSS, Audio, Bluetooth4.2, Camera, LCD, and FOTA
* Applicable to smart metering, sharing equipment, tracker, environmental monitoring, etc
* Used in most regions including China, EMEA, Latin America and SEA where LTE networks are deployed

### Frequency Bands

* LTE-FDD: B1, B3, B5, B8
* LTE–TDD: B34, B39, B40, B41
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
