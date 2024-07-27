# PI-Slim PC🖥️ 
As per many requests from my reddit post about my Raspberry pi pc case i made by reconstruction my old Pi-satelite shell iv decieded to reopen the old files and remodel it into a fully fledged PC case for the Raspbetty pi 3b-4 The pi slim case has been remodeled from old files 
![DSCN4760](https://github.com/user-attachments/assets/0911bc43-b8f9-4fb4-acde-1066c9bbe11b)


## List of parts required!
* Any old laptop fan (preferably HP L51102-001 laptop fan)
* Raspberry pi 3 or 4
* 6 x 6mm SPST Tactile Switch
* 3D Printed casing
* 4 neodymium magnets
* adhesive
* Jumper cables
  
## Pinnout diagram for the fan and the button
* wire 2 female dupont cables by soldering them onto the ends of the switch and connect to gpio 3 and ground
* Wire the black and red wire respectivly on to the female dupon connectors and wire on (5V and ground or 3V and ground) fan speed may vary according to given voltage
* pwm wires are not needed so can be desoldered to your liking
  
## Pinnout diagram:
![images](https://github.com/user-attachments/assets/bfdf7612-63ad-4e66-82d5-10442df5ab19)


## 3D Printed case!
### Main Frame!
![Screenshot 2024-07-27 174138](https://github.com/user-attachments/assets/efd501df-3851-4207-8dd5-e792f931b31f)

#### The case is designed Compactly sized to fit snugly around your components.this case also maximizes active ventilation and airflow with its well ventilated design

## Subframe!
<img width="923" alt="Screenshot 2024-01-06 072618" src="https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/905a0a55-a298-43c1-b8c5-bb4c4eabb86e">

#### The case is also uploaded opensource in this page where you can download and modify your case to your liking!

## integration of diffrent modules and Google home!
![x](https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/ea1ff7be-93c9-4ff3-8a29-6d05d46ea49c)

## Code for the power button:

#### With the integration of Google Home, CleanSphere becomes voice-activated and seamlessly connects with the broader smart home ecosystem. Users can leverage Google Assistant to query and control the environmental parameters monitored by CleanSphere effortlessly.(yet to be implimented soon!)
### Adittion and use of diffrent modules:

#### Because of the vast amount of diffrent sensors that can be used and configured with the ESP8266/ESP32 it is possible to swap out the pre existing sensors used in this system with diffrent kinds of sensors like MQ4 Methane gas sensor module,MQ3 Alcohol sensor module,DHT11 or LM35DZ.

#### it is also possibel to add aditional modules such as a SIM800L GSM module which allows to send and recive text messages when configured to do so!(currently only avilable for arduino IDE and not avilable for CADIO as of now)
