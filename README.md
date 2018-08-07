# eagle-lbr
A collection of self created eagle libraries.

Designed with/for eagle 7.x

:warning: **Use at your own risk, always check your layout before manufacturing!**

## Changes

- 20180807:
  - added SK6812 symbol name & value, changed pin visbility <br>
    [https://github.com/1randy/eagle-lbr/issues/2](https://github.com/1randy/eagle-lbr/issues/2)

- 20180727:
  - added Wago 2060 Cage Clamp
  - addded ESP12 Module
  - MEC Multimec Switches

- 20180726:
  - added Heltec Wifi LoRa 32 module<br>
    [https://github.com/Heltec-Aaron-Lee/WiFi\_Kit\_series](https://github.com/Heltec-Aaron-Lee/WiFi_Kit_series)

- 20180724:
  - fixed SK6812 SMD3535 footprint<br>
    [https://github.com/1randy/eagle-lbr/issues/1](https://github.com/1randy/eagle-lbr/issues/1)

  - added SMD5050_W(ide) footprint, longer pads for easier soldering

  - renamed package "SK6812-NARROW" to "LED5050_N"


## Libraries

* SK6812.lbr:
  LED with smart control circuit
  - SK6812 SMD3535: 3.5mm x 3.5mm
  - SK6812 SMD5050: 5.0mm x 5.0 mm
  - SK6812 SMD5050_N: 5.0mm x 5.0mm with shorter/narrower pads
  - SK6812 SMD5050_W: 5.0mm x 5.0mm with longer/wider pads

* TAS6424.lbr:
  - TAS6424-Q1: 2.1-MHz Digital Input 4-Channel Automotive Class-D Audio Amplifier

* LoRa_modules.lbr:
  - AI-Thinker_RA-01: 433MHz LoRa Module
  - RFM95: 866MHz LoRa Module
  - LORA\_SILK\_M, LORA\_SILK\_S: LoRA Logo for silkscreen (medium & small size)
  
* ESP32_modules.lbr
  - Heltec WIFI LoRa 32<br>
    ESP32 Module with LoRa, 2.54mm DIP
  
* ESP8266_modules.lbr
  - NodeMCU-ESP-12E
    ESP8266 Module, 2.54mm DIP
  - ESP-12E
    ESP8266 SMT Module, 22/16 pins

* con-wago-2060.lbr
  - WAGO 2060 Series Cage Clamp
    - 2060-401/451/471: SMD 4mm, 1 x 0,75 mm2
    - 2060-402/452/452: SMD 4mm, 2 x 0,75 mm2
    - 2060-403/453/473: SMD 4mm, 3 x 0,75 mm2
    - 2060-802/852/853: SMD 8mm, 2 x 0,75 mm2
    - 2060-1401/1421: THR 4mm, 1 x 0,75 mm2
    - 2060-1402/1422: THR 4mm, 2 x 0,75 mm2
    - 2060-1403/1423: THR 4mm, 3 x 0,75 mm2
    - 2060-1802/1822: THR 8mm, 2 x 0,75 mm2
    
* mec\_switches\_multimec.lbr
  - MEC Multimec Series switches
    - 3AT: Navimec switch THT with/without cap 1ZB
    - 3FT: Navimec switch THT with/without cap 1ZC
    
## Misc

* Datasheets for the components in the directory [datasheets/](datasheets/)



