![alt tag](https://github.com/mjScientech/Monitoring-Temp-and-Humidity-using-AWS-ESP32/blob/master/imgonline-com-ua-twotoone-XpoMD4Mf6S.jpg)

**In this tutorial, we will measure different temperature and humidity data using Temp and humidity sensor. You will also learn how to send this data to AWS.**


**Hardware** :
- **[ESP-32](https://store.ncd.io/product/esp32-iot-wifi-ble-module-with-integrated-usb/)**:The ESP32 makes it easy to use the Arduino IDE and the Arduino Wire Language for IoT applications. This ESp32 IoT Module combines Wi-Fi, Bluetooth, and Bluetooth BLE for a variety of diverse applications. This module comes fully-equipped with 2 CPU cores that can be controlled and powered individually, and with an adjustable clock frequency of 80 MHz to 240 MHz. This ESP32 IoT WiFi BLE Module with Integrated USB is designed to fit in all ncd.io IoT products.Monitor sensors and control relays, FETs, PWM controllers, solenoids, valves, motors and much more from anywhere in the world using a web page or a dedicated server.We manufactured our own version of the ESP32 to fit into NCD IoT devices, offering more expansion options than any other device in the world! Integrated USB port allows easy programming of the ESP32. The ESP32 IoT WiFi BLE Module is an incredible platform for IoT application development. This ESP32 IoT WiFi BLE Module can be programmed using Arduino IDE.

- **[IoT Long Range Wireless  Temperature And Humidity  Sensor](https://store.ncd.io/product/industrial-long-range-wireless-temperature-humidity-sensor/)**:Industrial Long Range Wireless Temperature Humidity Sensor. Grade with a Sensor Resolution of ±1.7%RH ±0.5°C .Up to 500,000 Transmissions from 2 AA Batteries.Measures -40°C to 125°C with Batteries that Survive these Ratings.Superior 2-Mile LOS Range & 28 miles with High-Gain Antennas.Interface to Raspberry Pi, Microsoft Azure, Arduino and More

- **[Long Range Wireless Mesh Modem with USB Interface](https://store.ncd.io/product/900hp-s3b-long-range-wireless-mesh-modem-with-usb-interface/)**

**Software Used:**
- Arduino IDE
- AWS

**Library Used:**
- PubSubClient Library
- Wire.h
- AWS_IOT.h
##  Uploading the code  to ESP32 using Arduino IDE:
- **Download and include the PubSubClient Library and Wire.h Library.**
- **You must assign your unique Ubidots TOKEN, MQTTCLIENTNAME, SSID (WiFi Name) and Password of the available network.**
- **Compile and upload the  [temp_humidity.ino](https://github.com/mjScientech/Esp32-Ubidots-Wireless-long-range-Temperature-And-Humidity/blob/master/temp_humidity.ino) code.**
- **To verify the connectivity of the device and the data sent, open the serial monitor.If no response is seen, try unplugging your ESP32 and then plugging it again. Make sure the baud rate of the Serial monitor is set to the same one specified in your code 115200.**

## Serial monitor output.
![alt tag](https://github.com/mjScientech/Esp32-Ubidots-Wireless-long-range-Temperature-And-Humidity/blob/master/serialout.JPG)
