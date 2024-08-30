# PI-Flow PC🖥
### As per many requests from my reddit post about my Raspberry pi pc case i made by reconstruction my old Pi-satelite shell iv decieded to reopen the old files and remodel it into a fully fledged PC case for the Raspberry pi 3b-4  
![DSCN4768](https://github.com/user-attachments/assets/d73ae835-e4fc-4307-83d3-2f96dbbce639)


# List of parts required!
* Any old laptop fan (preferably HP L51102-001 laptop fan)
* Raspberry pi 3 or 4
* 6 x 6mm SPST Tactile Switch
* 3D Printed casing
* 4 neodymium magnets
* adhesive
* Jumper cables
  
# Pinnout diagram for the fan and the button
* wire 2 female dupont cables by soldering them onto the ends of the switch and connect to gpio 3 and ground
* Wire the black and red wire respectivly on to the female dupon connectors and wire on (5V and ground or 3V and ground) fan speed may vary according to given voltage
* pwm wires are not needed so can be desoldered to your liking
  
# Pinnout diagram:
![images](https://github.com/user-attachments/assets/bfdf7612-63ad-4e66-82d5-10442df5ab19)


# 3D Printed case!
## Main Frame!
![Screenshot 2024-07-27 174138](https://github.com/user-attachments/assets/efd501df-3851-4207-8dd5-e792f931b31f)

#### The case is designed Compactly sized to fit snugly around your components.this case also maximizes active ventilation and airflow with its well ventilated design

## Subframe and cover!
![Screenshot 2024-07-27 174204](https://github.com/user-attachments/assets/7f65e525-c3b3-435f-9569-15ffc55a5040)
this frame is to be glued on top the main frame with magnets to be installed on the given holes
## Cover:
### with the choice of 3 diffrent cover plates you can print any one to your liking 

![Screenshot 2024-07-27 174507](https://github.com/user-attachments/assets/c3cdca55-ed8e-418a-997e-11a0f1b840e5)
#### Acrlyc transparent sheet is required for the blank frame
#### magnets to be installed on the given holes 
![Screenshot 2024-07-28 094056](https://github.com/user-attachments/assets/409b2dfa-8bd4-4599-a1f3-30d20f077dd5)

## The case is also uploaded opensource in this page where you can download and modify your case to your liking!

# Code for the power button:
```Script for shutdown:
git clone https://github.com/Howchoo/pi-power-button.git

./pi-power-button/script/install
````
# Final Build!
![DSCN4769](https://github.com/user-attachments/assets/81bcc68b-6cdd-477d-82b5-6b261bab7561)
![DSCN4770](https://github.com/user-attachments/assets/ff65c962-0b68-4f4f-b607-e11066b9e3a1)

