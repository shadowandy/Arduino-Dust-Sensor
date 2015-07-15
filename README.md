Arduino Dust Sensor
===================

Arduino-based dust sensor for particulate matter 2.5 and 10 concentration readings. The readings are logged to ThingSpeak.com.

It utilises the following:
* ESP8266 (ESP-01)
* Shinyei PPD42NS dust sensor
* 3.3-to-5.0v logic level converter
* DHT22 Humidity & Temperature Sensor


Additional Libraries
====================

The project makes use of the following libraries
* adafruit DHT-sensor-library (https://github.com/adafruit/DHT-sensor-library)


Modifications
=============

The following modifications are performed:
* RST pin is connected to GPIO16 on the ESP8266 (ESP-01)
* 10uF 25V Tantalum Capacitor connected between VCC and GND on the ESP8266 (ESP-01)