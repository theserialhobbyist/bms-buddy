# BMS Buddy

A cross-platform Battery Management System monitor for Bluetooth-enabled LiFePO4 batteries.

![BMS Buddy](Screenshots/Screenshot_20260110-143320.png)

## Features

- **Bluetooth Scanning** - Automatically discovers BMS devices nearby
- **Real-time Monitoring** - Live updates of battery status every 3 seconds
- **State of Charge** - Visual gauge showing battery percentage and voltage
- **Temperature Sensors** - Monitor battery and MOSFET temperatures (C/F toggle)
- **Cell Voltages** - Individual cell monitoring with min/max indicators
- **MOSFET Status** - View charge/discharge MOSFET states
- **Device Info** - BMS version and serial number

## Screenshots

| Scan Screen | Device Found | Battery Status | Cell Details |
|-------------|--------------|----------------|--------------|
| ![Scan](Screenshots/Screenshot_20260110-143320.png) | ![Found](Screenshots/Screenshot_20260110-143328.png) | ![Status](Screenshots/Screenshot_20260110-143344.png) | ![Cells](Screenshots/Screenshot_20260110-143352.png) |

## Downloads

### Android
- [bms_buddey_v0.5.apk](Android/bms_buddey_v0.5.apk) - Direct install APK
- [bms_buddy_v0.5.aab](Android/bms_buddy_v0.5.aab) - Android App Bundle

### Windows
- [Windows/](Windows/) - Windows executable and dependencies

## Installation

### Android
1. Download the APK file
2. Enable "Install from unknown sources" if prompted
3. Open the APK to install

### Windows
1. Download the entire Windows folder
2. Run `bms_monitor.exe`

## Compatibility

Works with Bluetooth-enabled BMS units that use the standard Modbus protocol, including many Chinese LiFePO4 BMS brands (JBD, Daly, JIKONG, etc.).

## Permissions Required

- **Bluetooth** - To scan and connect to BMS devices
- **Location** - Required by Android for Bluetooth scanning

## License

This software is provided as-is for personal use.
