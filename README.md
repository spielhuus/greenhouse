# Greenhouse Sensors for Arduino

This is a hydrophonic greenhouse for the garden. The system is built with bato buckets....


## Electronic

* Air Temperature and Humidity


## Components 

| Amount        | Name           | $  |
| ------------- |:-------------:| -----:|
| 1 | [DHT22](https://www.sparkfun.com/datasheets/Sensors/Temperature/DHT22.pdf) Temperature/Humidity Sensor| 2.54 |
| 1 | [BMP180](https://www.bosch-sensortec.com/bst/products/all_products/bmp180) Digital Barometric Pressure Sensor Board Module compatible with with BMP085 For Arduino| 1.44 |
| [DHT22}() Temperature/Humidity Sensor| | xxx |

## Wiring

### DHT22

First Pin is a VCC connect it to 5V.

Second Pin is Data Pin Connect it to Digital Pin 7.

Third Pin is called NC but i don't know why it's their i did not used it.

And Finally Fourth Pin is Ground Pin.

[https://create.arduino.cc/projecthub/attari/temperature-monitoring-with-dht22-arduino-15b013](Temperature Monitoring With DHT22 & Arduino)

### BMP180

|BMP085| Pin| 	Arduino Pin|
|------|----|--------------|
|VCC| 	3.3V|
|GND| 	GND|
|SCL| 	A5|
|SDA| 	A4|

[https://www.sparkfun.com/tutorials/253](BMP085 Barometric Pressure Sensor Quickstart)
