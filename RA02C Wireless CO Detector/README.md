This folder contains artifacts from onboarding a netvox RA02C LoRaWAN wireless CO detector into Datacake. 

The default Datacake decoder for RA02C devices is quite minimial. I made quite a few modifications to the decoder to meet my needs. 

The contents of this folder are as follows:
- **20250321_Datacake Outbound Webhook Log – RA02C.xlsx**
    This is a Google Sheet log of messages sent by the RA02C-1 device. 
- **CO_Alarm_Status_report-RA02C-1_-2025-3-14.csv**
    I've got Datacake programmed to send a weekly report for the RA02C-1 device. This report can be used as a compliance log.
- **CurrentConditionsDashboardwithRA02C.jpg**
    This is a screenshot of part of a Datacake dashboard displaying information from device, RA02C-1
- **FacilityDashboardwithRA02C.jpg**
    This is a screenshot of a different Datacake dashboard displaying information from device, RA02C-1
- **RA02C Datacake Fields - 1 of 2.jpg**
    This is a screenshot of most of the Datacake fields being captured for device RAO2C-1 using the custom Datacake decoder
- **RA02C Datacake Fields - 2 of 2.jpg**
    This is a screenshot of the rest of the Datacake fields being captured for device RAO2C-1 using the custom Datacake decoder
- **RA02C_payloadAnalysis.doc**
    To understand the RA02C payload so that I could modify the Datacake decoder to extract additional information, I did a bit-level analysis of several payloads.
- **RAO2C decoder v14.txt**
    This is the custom Datacake decoder I ended up with to create my dashboards.
- **TTN hitechdb custom Decoder for RA02C v1.txt**
    I made some minor tweaks to the TTN decoder so that I could see more information in the TTN message logs




