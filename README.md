# Home Automation and Monitoring (HAM)
## Overview
This whole effort was inspired by https://github.com/computourist/RFM69-MQTT-client and the forum at 
https://homeautomation.proboards.com/board/2/openhab-rfm69-based-arduino
This set of applications is intended to provide a networked solution to the problem of home automation and monitoring. The Three main applications that will accomplish this will be the following;

|Item| Application|Description|Hardware|Communications|Quantity|
|-----------|----------|-------------|----------|------------|----------|
|1| OpenHAB| using an MQTT binding| <b>Raspberry Pi</b>|Ethernet|1|
|2| Gateway| running Gateway_2.5| <b>Arduino Buono 3.3volts</b>| both RFM69 radio and Ethernet|1|
|3| Nodes| running node compatible with Gateway_2.5| <b>Arduino Buono 3.3volts</b>| using RFM69 radio|multiple|

## Setting up the devices and Testing Communications


### Steps to get the Arduinos up and running
- [ ] obtain all technical components
- [ ] RFM69 [Wiring Instructions](https://github.com/shulist/HAM/blob/master/HAM_0.01/RFM%20Wiring.png)
- [ ] make up radio and Arduinos
- [ ] get [test scripts](https://github.com/andySigler/RFm69-Examples) for the Arduinos]
- [ ] install the Arduino software
- [ ] test the radio functions
- [ ] expand test to simple sensors
- [ ] set up Raspberry Pi with [OpenHab](https://www.openhab.org/download/)
- [ ] Test one node, the gateway and OpenHAB
