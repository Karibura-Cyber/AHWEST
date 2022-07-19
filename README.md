# AHWEST Arduino Home Weather Station

This project use DHT11 for Temperature and Humidity sensor
## Website:
RestAPI: http://esp.meck.ml:5510/<br>
RestAPI: http://esp.meck.ml:5510/station/<station_name>
## Setup:
NodeMCU ESP8266 Download " AHWEST.bin " <br>
WEMOS D1 mini Download " AHWEST_WITH_096OLED_WEMOSD1MINI.bin " 

## Wire Connect:
### DHT11
- VCC/+ => 3v3
- GND/- => GND
- OUT   => D4

### Buzzer:
- VCC/+ => D5
- GND/- => GND

### LED:
!! Only test for <code>WEMOS D1 mini</code>
- GREEN LED => D8
- RED LED   => D7


### OLED SSD1306 0.96' 128x64:
!! Only test for <code>WEMOS D1 mini</code>
- VCC/+   => 5V
- GND/-   => GND
- SCK/SCL => D1
- SDA     => D2
