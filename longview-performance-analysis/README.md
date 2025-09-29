# longview-performance-analysis

If you’re interested in learning more about real-world LoRaWAN IoT systems and/or data analysis of real-world IoT systems, and/or exercising critical thinking skills, then this GitHub repository folder might be for you. 

Longview is a LoRaWAN IoT system with 7 devices and 1 IoT gateway. The Longview system is in Starkville, Mississippi and uses The Things Industries as a LoRaWAN Network Server (LNS). 

System performance is measured by counting the number of messages sent by each device per week and comparing that to the number of messages received by the LoRaWAN Network Server (LNS) for each device per week. The ratio of packets received over packets sent is called Packet Completion Rate or PC Rate. 

Between 8/2/2025 and 8/11/2025, the IoT gateway was offline, resulting in no message transfer from the devices to the LNS. Before the gateway went offline, PC Rate was near 94% for all 7 sensors. After IoT gateway came back online after 9 days of being offline, only 2 of the sensors returned to a near 94% PC Rate. The other 5 sensors have been running at a PC Rate in the 34% range since then. 
 
Q1: Why are 5 of the sensors running at a 34% PC Rate after the gateway outage?
Q2: Is it possible to fix the performance of the 5 sensors without having to physically remove the batteries to force a reset/rejoin?

Log files and additional information about the Longview system can be found in the **problem-statement** sub folder. 

Analysis results will be published to the **analysis-results** sub folder.
