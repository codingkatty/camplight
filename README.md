# camplight

![camplight](camplight-pic.png)

camplight is a little camping warning light with neopixels. it is powered by an ATtiny85, which can be powered by a li-po battery under the pcb. the camplight would be put together using glue and some double sided tape to attach the pcb to the case, as I can't think of a better way to do it.

### the pcb
the pcb files can be found in the pcb folder. it is made with kicad and you can get production files at `pcb/production`.

![image](https://github.com/user-attachments/assets/62f10bf3-447a-41c8-aab0-a9d950411786)

![image](https://github.com/user-attachments/assets/359ae724-264d-4abf-a22b-3ad346776473)

### the casing
the case consists of 4 components which are the main base, the top, the button and an acrylic piece. you can find them in the models folder! (respectively, `camplight-mainbase`, `camplight-topcover`, `camplight-button` and `camplight top cut.dxf` for acrylic)

![assemble](camplight.gif)

### bill of materials

for some of them i got 100 because the total is cheaper

| Item | Quantity | Price |
| ---- | -------- | ----- |
| Hot plate & solder paste | 1 | $0 |
| Case | 1 | $0 / self print |
| Soldering iron | 1 | $0 |
| Acrylic | 1 | $0 |
| PCB from JLCPCB | 1 | $1.50 (with coupon) |
| [Type-C connector](https://lcsc.com/product-detail/USB-Connectors_Korean-Hroparts-Elec-TYPE-C-31-M-12_C165948.html) | 5 | $0.87 |
| [1.5kΩ resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-0603WAF1501T5E_C22843.html) | 100 | $0.11 |
| [5.1kΩ resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FOJAN-FRC0603F5101TS_C2907044.html) | 100 | $0.10 |
| [1kΩ resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_YAGEO-RC0603FR-071KL_C22548.html) | 100 | $0.11 |
| [1.2kΩ resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FOJAN-FRC0603F1201TS_C2906976.html) | 100 | $0.10 |
| [100Ω resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_YAGEO-RC0603FR-07100RL_C105588.html) | 100 | $0.10 |
| [22Ω resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FOJAN-FRC0603J220-TS_C2907129.html) | 100 | $0.08 |
| [470Ω resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FOJAN-FRC0603J471-TS_C2907172.html) | 100 | $0.09 |
| [4.7kΩ resistor](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_FOJAN-FRC0603J472-TS_C2907166.html) | 100 | $0.08 |
| [LED indicator](https://lcsc.com/product-detail/LED-Indication-Discrete_XINGLIGHT-XL-1608SURC-06_C965799.html) | 100 | $0.32 |
| [WS2812B neopixels](https://lcsc.com/product-detail/RGB-LEDs-Built-in-IC_XINGLIGHT-XL-5050RGBC-WS2812B_C2843785.html) | 20 | $0.98 |
| [100nf capacitor](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_YAGEO-CC0603KRX7R9BB104_C14663.html) | 100 | $0.24 |
| [10uf capacitor](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL10A106KP8NNNC_C19702.html) | 20 | $0.12 |
| [3.6V zener diodes](https://lcsc.com/product-detail/Zener-Diodes_Shandong-Jingdao-Microelectronics-1SMA4729A_C438351.html) | 20 | $0.69 |
| [1x2P pin header](https://lcsc.com/product-detail/Pin-Headers_Megastar-ZX-PZ2-54-1-2PZZ_C7501260.html) | 20 | $0.37 |
| [ATtiny85-20PU](https://lcsc.com/product-detail/Microcontrollers-MCU-MPU-SOC_Microchip-Tech-ATTINY85-20PU_C965497.html) | 5 | $15.49 |
| [FS2805A](https://lcsc.com/product-detail/MOSFETs_TECH-PUBLIC-FS8205A_C2830320.html) | 10 | $0.45 |
| [TP4056](https://lcsc.com/product-detail/Battery-Management_TPOWER-TP4056_C382139.html) | 5 | $0.44 |
| [DW01A](https://lcsc.com/product-detail/Battery-Management_YONGYUTAI-DW01A_C2927799.html) | 20 | $0.49 |
| [AMS1117-5.0](https://lcsc.com/product-detail/Voltage-Regulators-Linear-Low-Drop-Out-LDO-Regulators_GOODWORK-AMS1117-5-0_C6068482.html) | 10 | $0.38 |
| [Push button switch](https://lcsc.com/product-detail/Tactile-Switch-Push-Button-Switch_YIZHI-YZA-072-5-0_C49108658.html) | 50 | $0.46 |
| [Slide switch](https://lcsc.com/product-detail/Slide-Switches_G-Switch-MK-12C02-G025_C778186.html) | 5 | $0.63 |
| LCSC shipping | | $19.47 |
| Total | | $43.67 |
