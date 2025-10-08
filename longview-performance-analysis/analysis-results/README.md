# longview-performance-analysis/analysis-results

The **analysis-results** folder contains the results from the analysis of the Longview system performance problem. 

The contents of this folder are as follows:

* **Final Report - PC Rate Degradation Analysis of the Longview LoRaWAN System.pdf** - This document details the root cause analysis and result of attempting to fix the problem
* **(SUPPORTING) Performance Investigation - ChatGPT Research.pdf** - this document contains several series of ChatGPT analysis exercises on the log data. 
* **(SUPPORTING) Downlink Experiments on TBWL100_10 to fix the PC Rate.pdf** - this document contains a history of trying ChatGPT suggested downlink commands in the TTI console to first fix the Rx Delay issue and then reset the channel sub mask. In the end, I was never able to get the TBWL100_10 device to accept/ack a downlink command. 
* **Avg FrameCount Gap before and after gateway outage.jpg** - this graph is another way to look at device performance before and after the gateway outage
* **PerformanceGraph.jpg** - Plot of PC Rates before and after the gateway outage
* **20250911_Log_Longview_SensorDataFlow_TTN_with_SubBand_Channel.xlsx** - TTN log file, with SubBand and Channel columns added
