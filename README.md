# Sloppy Joe - Arduino based Turtlebot connected via MQTT

Since the *origianl* [Turtlebot](https://www.turtlebot.com/) isn't quite cheap, my idea was to build a even cheaper version based on Arduino using Azure IoT or any other MQTT cloud provider to do *difficult* calculations, using the Arduino only to control the attached hardware.

## Components

* [Arduino MKR 1010 WiFi](https://store.arduino.cc/products/arduino-mkr-wifi-1010)
* L298N Motor Driver
* DC Motor + Wheels
* Arduino Cam (not yet implemented)

## Documentation

The Arduino is connected to Azure IoT Hub 

### Connection Diagram

## Useful Links

* Arduino MQTT Client Repo: https://github.com/arduino-libraries/ArduinoMqttClient
* Sending data over MQTT Example: https://docs.arduino.cc/tutorials/mkr-wifi-1010/mqtt-device-to-device
* Arduino DC Motor Guide: https://arduinogetstarted.com/tutorials/arduino-dc-motor
* CSR and Cloud Connectivity Tutorial: https://docs.arduino.cc/tutorials/mkr-wifi-1010/securely-connecting-an-arduino-mkr-wifi-1010-to-aws-iot-core
* Azure IoT Hub Connectivity: https://create.arduino.cc/projecthub/Arduino_Genuino/securely-connecting-an-arduino-nb-1500-to-azure-iot-hub-af6470 & related Issue: https://github.com/arduino-libraries/ArduinoMqttClient/issues/34
* 
