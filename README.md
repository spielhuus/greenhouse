# Greenhouse Sensors for Arduino

This is a hydrophonic greenhouse for the garden. The system is built with bato buckets....


## Electronic

* Air Temperature and Humidity


## Components 

|Amount        | Type           | Description  |
|:------------- |:-------------| -----:|
| 1 | [DHT22](https://www.sparkfun.com/datasheets/Sensors/Temperature/DHT22.pdf)|Temperature/Humidity Sensor|
| 1 | [BMP180](https://ae-bst.resource.bosch.com/media/_tech/media/datasheets/BST-BMP180-DS000-12.pdf)|Digital Barometric Pressure Sensor Board Module compatible with with BMP085 For Arduino|
|1 | [DS1820](https://datasheets.maximintegrated.com/en/ds/DS18S20.pdf) Stainless steel package Waterproof DS18b20 temperature probe temperature sensor 18B20 For Arduino|
|1 |[SR04T](https://www.jahankitshop.com/getattach.aspx?id=4635&Type=Product) Waterproof Ultrasonic Range Distance Measurement Sensor| |
|1 |[ESP-01](http://www.microchip.ua/wireless/esp01.pdf) Waterproof Ultrasonic Range Distance Measurement Sensor
|1 |[DS1307](https://www.sparkfun.com/datasheets/Components/DS1307.pdf) | RTC module|
|1 |[LM317](https://datasheet.octopart.com/LM317TG-ON-Semiconductor-datasheet-613672.pdf) | 1.5 A Adjustable Output, Positive Voltage Regulator|
|1 | | Resistor 4.7 kΩ |

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

[Waterproof Ultrasonic Range Distance Measurement Sensor](http://qqtrading.com.my/waterproof-ultrasonic-range-distance-measurement-sensor-sr04t)

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

https://www.deviceplus.com/how-tos/arduino-guide/esp8266-setup-tutorial-using-arduino/

### DS-1307

| Pin| 	Arduino Pin|
|----|-------------|
|VCC| 	5V|
|GND| 	GND|
|SDL| 	Analog Pin 5|
|SDA| Analog PIN 4 |

[DS1307 Real-Time Clock Modul mit einem Arduino ansteuern](https://www.frag-duino.de/index.php/maker-faq/26-ds1307-real-time-clock-modul-mit-arduino-ansteuern)


## Links

* [How many Devices can you Connect to the I2C Bus?](https://www.bluedot.space/tutorials/how-many-devices-can-you-connect-on-i2c-bus/)

