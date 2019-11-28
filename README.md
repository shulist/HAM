# Home Automation and Monitoring (HAM)
## Overview
This whole effort was inspired by https://github.com/computourist/RFM69-MQTT-client
This set of applications is intended to provide a networked solution to the problem of home automation and monitoring. The Three main applications that will accomplish this will be the following;

|Item| Application|Description|Hardware|Communications|
|-----------|----------|-------------|----------|------------|
|1| OpenHAB| using an MQTT binding| <b>Raspberry Pi</b>|Ethernet|
|2| Gateway| running Gateway_2.5| <b>Arduino</b>| both RFM69 radio and Ethernet|
|3| Nodes| running node compatible with G_2.5| <b>Arduino</b>| using RFM69 radio|

## Setting up the devices and Testing Communications
[Test scripts for the Arduinos](https://github.com/andySigler/RFm69-Examples)

###Steps to get the Arduinos up and running
- [ ] obtain all technical components
- [ ] make up radio and Arduinos
- [ ] install the Arduino software
- [ ] test the radio functions
- [ ] expand test to simple sensors
