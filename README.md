# IoT Temperature Monitoring System

A simple IoT project that measures temperature using an Arduino board and a temperature sensor, then displays the readings on a web page using an ESP8266 Wi-Fi module.

## Components Used

* Arduino Uno
* ESP8266 Wi-Fi Module
* Temperature Sensor (LM35 / DHT11)
* Jumper Wires & Breadboard

## Features

* Reads real-time temperature data from the sensor.
* Sends data to a web server via ESP8266.
* Displays live readings on a simple HTML/CSS web page.

## How It Works

1. The Arduino reads temperature values from the sensor.
2. Data is sent to the ESP8266 module using serial communication.
3. The ESP8266 hosts a web server that displays the temperature readings on any connected device.

## Tools & Languages

* Embedded C / Arduino IDE
* HTML, CSS (for web interface)

## Future Improvements

* Add humidity or other environmental sensors.
* Use MQTT for cloud integration.
* Log temperature data over time.

## Author

Developed by Minhal Naqvi as part of an IoT learning project.
