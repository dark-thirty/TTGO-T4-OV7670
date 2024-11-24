# TTGO-T4 V1.3 OV7670 MOD

The TTGO T4 v1.3 offers a 2.4" (ILI9341) display, ESP32 dual-core Tensilica LX6, 4MBflash, 8MB PSRAM, MicroSD card slot,
LiPo battery support, a 20-pin GPIO header, a 5-pin I2C connector for expansion and a three buttons.






https://github.com/user-attachments/assets/637ba0bd-3b72-460f-9d87-3d711f954747







## Connect

Pins used to connect TTGO T4 and OV7670 camera module are shown in below:

![ttgo-t4_v1 3](https://github.com/user-attachments/assets/fe19a6f3-9fcc-482b-b431-8aa464121f65)

Тo gain access to the pins that is wired in to the MicroSD slot you can use Sparkfun MicroSD Sniffer

![sparkfun](https://github.com/user-attachments/assets/8949b8cb-88b4-4754-82c4-e494214c2a1a)

* or _(if you carefully remove the cover of the MicroSD card slot and solder directly on to the pins or the pad)_.


|  OV7670 Pins | TTGO T4 Pins |
| ---------- | ---------- |
| 3.3V | 3.3V |
| GND  | GND  |
| SCL | IO 13 (4.7kΩ Pull Up)|
| SDA | IO 15 (4.7kΩ Pull Up) |
| VSYNC / VS | IO 14 |
| HSYNC / HS | IO 34 |
| PCLK | IO 36 |
| XCLK / MCLK | IO 0 |
| D7 | IO 35 |
| D6 | IO 26 |
| D5 | IO 33 |
| D4 | IO 22 |
| D3 | IO 21 |
| D2 | IO 39 |
| D1 | IO 2  |
| D0 | IO 19 |
| RESET / RST | 3.3V |
| PWDN / PWNN | GND |

## Display connection

| 2.4" (ILI9341) display | TTGO T4 Pins |
| ---------- | --------- |
| MOSI | IO 23 |
| CLK  | IO 18 |
| CS | IO 27 |
| DC | IO 32 |
| MISO | IO 12 |
| LCD RST | IO 5 |
| LCD BACKLIGHT | IO 4 |
