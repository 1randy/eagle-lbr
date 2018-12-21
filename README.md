# eagle-lbr
A collection of self created eagle libraries.

Designed with/for eagle 7.x

:warning: **Use at your own risk, always check your layout before manufacturing!**

## Changes


- 20181220:
  - added Analog Devices AD724 & AD8056
     
- 20180807:
  - added SK6812 symbol name & value, changed pin visbility <br>
    [https://github.com/1randy/eagle-lbr/issues/2](https://github.com/1randy/eagle-lbr/issues/2)
  - added Fastron Inductors PISR & PISR4728
    
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

* analog-devices.lbr:
  - [AD724][40]: RGB to NTSC/PAL Encoder
  - [AD8056][41]: Dual 300 MHz Voltage Feedback Amplifiers
  
* con-wago-2060.lbr ([WAGO 2060 Series Cage Clamp][10])
  - 2060-401/451/471: SMD 4mm, 1 x 0,75 mm2
  - 2060-402/452/452: SMD 4mm, 2 x 0,75 mm2
  - 2060-403/453/473: SMD 4mm, 3 x 0,75 mm2
  - [2060-802/852/853][11]: SMD 8mm, 2 x 0,75 mm2
  - [2060-1401/1421][12]: THR 4mm, 1 x 0,75 mm2
  - [2060-1402/1422][12]: THR 4mm, 2 x 0,75 mm2
  - [2060-1403/1423][12]: THR 4mm, 3 x 0,75 mm2
  - [2060-1802/1822][13]: THR 8mm, 2 x 0,75 mm2

* ESP32_modules.lbr
  - [Heltec WIFI LoRa 32][20]<br>
    ESP32 Module with LoRa, 2.54mm DIP
  
* ESP8266_modules.lbr
  - NodeMCU-ESP-12E
    ESP8266 Module, 2.54mm DIP
  - ESP-12E
    ESP8266 SMT Module, 22/16 pins
    
* LoRa_modules.lbr:
  - [AI-Thinker_RA-01][30]: 433MHz LoRa Module
  - RFM95: 866MHz LoRa Module
  - LORA\_SILK\_M, LORA\_SILK\_S: LoRA Logo for silkscreen (medium & small size)
    
* mec\_switches\_multimec.lbr ([MEC Multimec Series switches][35])
  - 3AT: Navimec switch THT with/without cap 1ZB
  - 3FT: Navimec switch THT with/without cap 1ZC
  
* inductor_FASTRON.lbr:
  - [PIS4728][31]: SMD-Power-Inductor, Ferrit 12.5 mm x 12.5 mm
  - [PISR][32]: SMD-Power-Inductor, Ferrit 15 mm x 19 mm
      
* SK6812.lbr:
  LED with smart control circuit
  - [SK6812 SMD3535][2]: 3.5mm x 3.5mm
  - [SK6812 SMD5050][3]: 5.0mm x 5.0 mm
  - [SK6812 SMD5050_N][3]: 5.0mm x 5.0mm with shorter/narrower pads
  - [SK6812 SMD5050_W][3]: 5.0mm x 5.0mm with longer/wider pads

* TAS6424.lbr:
  - [TAS6424-Q1][1]: 2.1-MHz Digital Input 4-Channel Automotive Class-D Audio Amplifier

    
## Misc

* Datasheets for the components in the directory datasheets/

[1]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/TAS6424-q1.pdf
[2]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/SK6812%20MINI%203535%20LED%20Datasheet.pdf
[3]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/SK6812%205050%20LED%20Datasheet.pdf
[10]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/WAGO_SMD_Terminal_Blocks.pdf
[11]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/WAGO_2060-8_DB.pdf
[12]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/WAGO_2060-14_DB.pdf
[13]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/WAGO_2060-18_DB.pdf
[20]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets//Heltec_WIFI-LoRa-32_DiagramPinoutFromTop.jpg
[30]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/RA-01_product_specification_v1.1.pdf
[31]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/FASTRON-SMD_Induktivitaeten-PIS4728.pdf
[32]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/FASTRON-SMD_Induktivitaeten-PISR.pdf
[35]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/mec_switches_1206_katalog_v6_d.pdf
[40]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/AD724.pdf
[41]: https://raw.githubusercontent.com/1randy/eagle-lbr/master/datasheets/AD8055_8056.pdf

