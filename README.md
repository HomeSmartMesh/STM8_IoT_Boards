# STM8_IoT_Board
The PCB design of the STM8 with the nRF24L01+ Board

The IoT node is an STM8 based low cost development platform.
It is an initiative for an open product = open hardware + open source project.
find all the details in this link :
http://www.homesmartmesh.com/mediawiki/index.php/IoT_Node

This board will be interfacing such peripherals :
 - Radio transceiver module
 - Weather sensors : temperature, humidity, air quality.
 - RGB Leds
 - Gyro / Accel
 - Ambient light and user gesture

The wiki above contains links to SW and HW, but here's a direct link to the Firmware open source project:
https://github.com/wassfila/STM8_IoT_HelloWorld
The Firmware contains drivers (in development) for the above mentionned peripherals.

This IoT Node is part of a bigger project that extand the collaboration to a complete IoT environment.
It includes  interfaces to existing products and server applications for merging everything together.
The "Home Smart Mesh" concept is described in the main wiki page
http://www.homesmartmesh.com/mediawiki/index.php/Main_Page

The Board is grouping two modules :
 - STM8 Dev Board based on the STM8S103F3
 - nRF24L01+ module based on the reference design
 - It also has a pullup resistor and 3 pins where to plug an DS18B20 temperature sensor

For any questions, or if you have answers for the pending questions, please post on the Forum
http://www.homesmartmesh.com/forum/
