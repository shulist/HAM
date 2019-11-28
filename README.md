# Home Automation and Monitoring (HAM)
## Overview
This whole effort was inspired by https://github.com/computourist/RFM69-MQTT-client
This set of applications is intended to provide a networked solution to the problem of home automation and monitoring. The Three main applications that will accomplish this will be the following;
|Item| Application|Description|Hardware|Communications|
|-----------|----------|-------------|----------|------------|
|1| OpenHAB| using an MQTT binding| <b>Raspberry Pi</b>|Ethernet|
|2| Gateway| running| <b>Arduino</b>| both radio and Ethernet|
|3| Nodes| running| <b>Arduino</b>| using radio|
