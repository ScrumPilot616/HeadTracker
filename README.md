# HeadTracker


## Features
Output selectable between
- CPPM
- Serial
- WiFi


## Hardware

### Required
- WEMOS D1 MINI / WEMOS D1 MINI PRO
- MPU9250

### Optional
- Reset button
- Voltage regulator e.g. 7805
- 3.5mm jack 4 Pin
 
### Wiring

![N|Solid](https://github.com/ScrumPilot616/HeadTracker/blob/main/images/HeadtrackerHW.png)


## Build
### Arduino IDE
Download and install the Arduino IDE (e.g. 1.8.19) and add the bordmanager for ESP8266 devices (3.1.2).
For both you can find a detailed description [here](https://arduino-esp8266.readthedocs.io/en/3.1.1/installing.html#boards-manager).

Select the board type "LOLIN(WEMOS) D1 R2 & mini".
Open the source file HeadTrackerSP.ino and compile it. 
  
### Flashing Firmware
If the compilation was successful connect your ESP device with an USB cable.
Select the correct COM port for your ESP device.
Press the upload button.


### Configuration Tool
The configuration tool runs under Windows and requires .Net runtime.
Start the configuration tool, select the correct COM port and press connect.
In the status bar color should be green with the message "Headtracker connected!"


## Setup
Setup is done by the HeadTracker configuration tool.

### Configuration
![N|Solid](https://github.com/ScrumPilot616/HeadTracker/blob/main/images/HeadTrackerConfig.png)

### Calibration
![N|Solid](https://github.com/ScrumPilot616/HeadTracker/blob/main/images/HeadTrackerCalibration.png)

![N|Solid](https://github.com/ScrumPilot616/HeadTracker/blob/main/images/HeadTrackerCalibrationTest.png)


## Used Libraries

| Library     | Author | Licence|
| ----------- | ------ |--------|
| MPU9250 |  Copyright (c) 2018 Hideaki Tai | MIT License |
| [Arduino core for ESP8266 WiFi chip](https://github.com/esp8266/Arduino) | 3.1.2 |  LGPL-2.1   |


## Example builds
### By ScrumPilot616
#### HeadTracker
![N|Solid](https://github.com/ScrumPilot616/HeadTracker/blob/main/images/Headtracker_SP_Example1.jpg)

![N|Solid](https://github.com/ScrumPilot616/HeadTracker/blob/main/images/Headtracker_SP_Example2.jpg)


#### Mounted on DJI googles

