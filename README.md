# Greenhouse Sensors for Arduino

This is a hydrophonic greenhouse for the garden. The system is built with bato buckets....


## Electronic

* Air Temperature and Humidity


## Components 

| Amount        | Name           | $  |
| ------------- |:-------------:| -----:|
| 1 | [DHT22](https://www.sparkfun.com/datasheets/Sensors/Temperature/DHT22.pdf) Temperature/Humidity Sensor| 2.54 |
| 1 | [BMP180](https://www.bosch-sensortec.com/bst/products/all_products/bmp180) Digital Barometric Pressure Sensor Board Module compatible with with BMP085 For Arduino| 1.44 |
|1 | [DS1820](https://datasheets.maximintegrated.com/en/ds/DS18S20.pdf) Stainless steel package Waterproof DS18b20 temperature probe temperature sensor 18B20 For Arduino| 1.38 |
|1 |[SR04T]() Waterproof Ultrasonic Range Distance Measurement Sensor| |
|1 |[ESP-01](http://www.microchip.ua/wireless/esp01.pdf) | 1.76 |
|1 | Resistor 4.7 kΩ | |

## Wiring

### DHT22

| Pin| 	Arduino Pin|
|----|-------------|
|VCC| 	5V|
|Data| 	D7|
|NC| 	NC|
|GND| 	GND|

[Temperature Monitoring With DHT22 & Arduino](https://create.arduino.cc/projecthub/attari/temperature-monitoring-with-dht22-arduino-15b013)

### BMP180

| Pin| 	Arduino Pin|
|----|-------------|
|VCC| 	3.3V|
|GND| 	GND|
|SCL| 	A5|
|SDA| 	A4|

[BMP085 Barometric Pressure Sensor Quickstart](https://www.sparkfun.com/tutorials/253)

### DS1820

| Pin| 	Arduino Pin|
|----|-------------|
|VCC| 	3.3V|
|GND| 	GND|
|DATA| 	A2|

There needs to be a 4.7 kΩ pull-up resistor between Data and VCC.

[DS18B20 (digital temperature sensor) and Arduino](https://create.arduino.cc/projecthub/TheGadgetBoy/ds18b20-digital-temperature-sensor-and-arduino-9cc806)

### TODO SR04T

| Pin| 	Arduino Pin|
|----|-------------|
|VCC| 	3.3V|
|GND| 	GND|
|DATA| 	A2|

[]()

### ESP-01

| Pin| 	Arduino Pin|
|----|-------------|
|Rx| 	Pin1/Rx|
|Tx| 	Pin2/Tx|
|CH-PD| 	3.3V|
|RST| NC |
|VCC| 3.3V |
|GND|GND|
|GPIOx|NC|

[Getting Started With the ESP8266 ESP-01](https://www.instructables.com/id/Getting-Started-With-the-ESP8266-ESP-01/)


