# Cleansphere🌍 
Welcome to CleanSphere, an open-source project dedicated to fostering sustainable practices through advanced environmental monitoring. This repository houses the codebase and design files for a comprehensive system that integrates an ESP32 microcontroller, DHT22 temperature and humidity sensor,MQ-135 gas sensor, and a user-friendly CADIO dashboard.

## List of parts required!
* MQ135 Air Quality sensor
* DHT 22 temperature and humidity sensor
* ESP8226MOD/ESP32
* 3D Printed casing

## Pinnout diagram for the ESP32
<img width="474" alt="Image20240106070325" src="https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/06954a58-d221-4f1e-8dc7-27c299034727">

### These are the connections for each sensor:

### DHT22

* VCC: Connect to the power supply (3.3V or 5V).
* GND: Connect to ground.
* DATA: Connect to a digital pin on your microcontroller.
* NC: No connect.

### MQ-135
* VCC: Connect to the power supply (5V).
* GND: Connect to ground.
* AOUT: Connect to an analog pin on your microcontroller.

### To measure air quality, temperature, and humidity with these sensors, you'll need to Flash the [CADIO FIRMWARE](https://egycad.com/cadio/docs/category/firmware/ "Named link title") onto the ESP8266/ESP32 Via [ESP Flash Tool](https://www.espressif.com/en/support/download/other-tools "Named link title") and configure the connection and pins via the CADIO mobile app

## 3D Printed case!
<img width="924" alt="Screenshot 2024-01-06 072544" src="https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/c81cc899-4a4b-4aad-8acb-b26282ddb3a5">

#### The case is designed Compactly sized to fit snugly around your components.this case also minimizes material waste, while cleverly placed ventilation holes promote passive cooling and reduces energy consumption.
<img width="923" alt="Screenshot 2024-01-06 072618" src="https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/905a0a55-a298-43c1-b8c5-bb4c4eabb86e">

#### The case is also uploaded opensource in this page where you can download and modify your case to your liking!

## integration of diffrent modules and Google home!
![x](https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/ea1ff7be-93c9-4ff3-8a29-6d05d46ea49c)

## Google Home Integration:

#### With the integration of Google Home, CleanSphere becomes voice-activated and seamlessly connects with the broader smart home ecosystem. Users can leverage Google Assistant to query and control the environmental parameters monitored by CleanSphere effortlessly.(yet to be implimented soon!)
### Adittion and use of diffrent modules:

#### Because of the vast amount of diffrent sensors that can be used and configured with the ESP8266/ESP32 it is possible to swap out the pre existing sensors used in this system with diffrent kinds of sensors like MQ4 Methane gas sensor module,MQ3 Alcohol sensor module,DHT11 or LM35DZ.

#### it is also possibel to add aditional modules such as a SIM800L GSM module which allows to send and recive text messages when configured to do so!(currently only avilable for arduino IDE and not avilable for CADIO as of now)
