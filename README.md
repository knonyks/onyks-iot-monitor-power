## ESP32 power meter

Based on:

* ACS712 - 30A
* 2ma - 2ma voltage measuring transformer
* ADS1115 - I2C ADC 16bit

Programer:

* [ESP-prog](https://docs.espressif.com/projects/esp-iot-solution/en/latest/hw-reference/ESP-Prog_guide.html)
* [voltage module schematic](https://diyprojectslab.com/zmpt101b-voltage-sensor-module-with-arduino/)

Power suply:
	
* [220V-5V_1000mA/2000mA](https://pl.aliexpress.com/item/1005005029575292.html?spm=a2g0o.order_list.order_list_main.40.53561c24AgBVnU&gatewayAdapt=glo2pol)

Connector:
	
* [Screw_connectorm_8x8_M3](https://pl.aliexpress.com/item/1005007060857910.html?spm=a2g0o.detail.0.0.38d7AUSVAUSVAv&mp=1&_gl=1*10grcc4*_gcl_aw*R0NMLjE3Mjgy)

### TO DO:

- [x] Add prog connector and essentials for esp32
- [x] Add pads for Isens
- [x] Add voltage sensor
- [x] Change footpirnts
- [ ] Test ad-dc converter
- [x] Add relay
- [x] Add extra outputs (5V, sig, GND)

### PCB V1 (not for production):

* [schematic](img/V1/schematic_v1.pdf)
* [bom](fab/V1/ibom.html)
* PCB

![](img/V1/pcb_v1.png)

![](img/V1/onyks-iot-esp32-monitor-power_v1.jpg)



### PCB V2:

* [check list](docs/V2/check_list.md)


---

Author: Maciej Załęski [macmysz]