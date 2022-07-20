# AHWEST Arduino Home Weather Station

This project use DHT11 for Temperature and Humidity sensor

## Website & API
#### API primary path: https://api.ahwest.cf
 - <code>GET /</code> for get all data from storage
 - <code>GET /station/<station_name></code> for get data from some station
 - <code>GET /docs</code> for all request document

#### AHWEST MAP Website: http://map.ahwest.cf

## Setup:
- ESP8266Flasher Download https://github.com/nodemcu/nodemcu-flasher/raw/master/Win64/Release/ESP8266Flasher.exe <br>
- NodeMCU ESP8266 Download " AHWEST.bin " <br>
- WEMOS D1 mini Download " AHWEST_WITH_096OLED_WEMOSD1MINI.bin " 

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
