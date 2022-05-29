# 🤖🌭 Sloppy Joe - Arduino based Turtlebot connected via MQTT

Since the *origianl* [Turtlebot](https://www.turtlebot.com/) isn't quite cheap, my idea was to build a even cheaper version based on Arduino using Azure IoT or any other MQTT cloud provider to do *difficult* calculations, using the Arduino only to control the attached hardware.

## Components

* [Arduino MKR 1010 WiFi](https://store.arduino.cc/products/arduino-mkr-wifi-1010)
* L298N Motor Driver
* DC Motor + Wheels
* Arduino Cam (not yet implemented)

### Price List & Total Price

tbd

## Documentation

The Arduino is connected as a device to Azure IoT Hub via MQTT.

### Connection Diagram

tbd --> https://fritzing.org/

## Useful Links

* Arduino MQTT Client Repo: https://github.com/arduino-libraries/ArduinoMqttClient
* Sending data over MQTT Example: https://docs.arduino.cc/tutorials/mkr-wifi-1010/mqtt-device-to-device
* Arduino DC Motor Guide: https://arduinogetstarted.com/tutorials/arduino-dc-motor
* CSR and Cloud Connectivity Tutorial: https://docs.arduino.cc/tutorials/mkr-wifi-1010/securely-connecting-an-arduino-mkr-wifi-1010-to-aws-iot-core
* Azure IoT Hub Connectivity: https://create.arduino.cc/projecthub/Arduino_Genuino/securely-connecting-an-arduino-nb-1500-to-azure-iot-hub-af6470 & related Issue: https://github.com/arduino-libraries/ArduinoMqttClient/issues/34
* Azure Sas Token Docs: https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-dev-guide-sas?tabs=node#use-sas-tokens-as-a-device and https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-mqtt-support
* Connect MKR 1010 to WiFi: https://docs.arduino.cc/tutorials/mkr-wifi-1010/connecting-to-wifi-network#
* **Cool IoT Tutorial: https://github.com/microsoft/IoT-For-Beginners/blob/main/1-getting-started/lessons/4-connect-internet/README.md**
* Another Project Example with Arduino/Azure IoT: https://paul-bruffett.medium.com/iot-azure-pipeline-9725ac2b6a00 and https://github.com/firedog1024/mkr1000-iotc
* Azure IoT SDK: https://github.com/Azure/azure-iot-sdk-c
* Free MQTT Broker: https://test.mosquitto.org/
* Firmata for Arduino: https://github.com/firmata/arduino
