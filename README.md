## Updating the firmware
- Download the Voltaic BMS update tool by clicking
[here](https://github.com/Dev-Voltaic/Voltaic_BMS_Firmware/raw/main/Voltaic_BMS_Update_v0_1.zip)
- Unzip the downloaded file
- Follow the instructions of the file **How_to_update_firmware** which can be found in the unzipped folder

## Changelog 0.0.0 -> 0.1.0
- Precharge checks the output for a broken connection to the motor controller
- Precharge is now interruptable by alerts
- Precharge safety improvements in general
- Multiple alerts are now able to be displayed at the same time
- More specific hardware faults
- Added serial number to board info
- Added support for custom battery pack voltage range
- Reliability improvements 

## Changelog 0.1.0 -> 0.2.0
- Implemented OTA ("Over The Air") updates

## Changelog 0.2.0 -> 0.2.1
- Fixed issue where multiple BLE connections to the same BMS were possible under certain circumstances
- Biggest possible shunt value takes enabled channels into account

## Changelog 0.2.1 -> 0.2.2
- Added automatic confirmation of OTA updates on BMS side
