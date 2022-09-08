# AHWEST Arduino Home Weather Station

This project use DHT11 for Temperature and Humidity sensor

## Website & API
#### API primary path: https://api.ahwest.cf
 - <code>GET /</code> for get all data from storage

#### AHWEST MAP Website: https://map.ahwest.cf

## Setup:
- Download [ESP8266Flasher.exe](https://github.com/nodemcu/nodemcu-flasher/raw/master/Win64/Release/ESP8266Flasher.exe) for flash ESP8266 Board <br>
- Download [AHWEST.bin](https://github.com/Karibura-Cyber/AHWEST/blob/main/AHWEST.bin?raw=true) for NodeMCU ESP8266(ESP 12E) without OLED<br>
- Download [AHWEST_WITH_096OLED_WEMOSD1MINI.bin](https://github.com/Karibura-Cyber/AHWEST/blob/main/AHWEST_WITH_096OLED_WEMOSD1MINI.bin?raw=true) for WEMOS D1 mini with OLED

- Connect wifi SSID <code>AHWEST Setup</code>
- Open browser and search <code>192.168.4.1</code>
- Click to <code>Configure WiFi</code>
- Fill data <code>Station Name must be not have space EX: "TEST-01" </code>
- Save and wait for beep signal or BuiltIn LED blink

## Wire Connect:
#### DHT11
- VCC/+ => 3v3
- GND/- => GND
- OUT   => D4

#### Buzzer:
- VCC/+ => D5
- GND/- => GND

#### LED:
!! Only test for <code>WEMOS D1 mini</code>
- GREEN LED => D8
- RED LED   => D7


#### OLED SSD1306 0.96' 128x64:
!! Only test for <code>WEMOS D1 mini</code>
- VCC/+   => 5V
- GND/-   => GND
- SCK/SCL => D1
- SDA     => D2
