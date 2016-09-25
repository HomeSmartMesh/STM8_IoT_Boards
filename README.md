# STM8_IoT_Boards
This repository provides PCBs based on the STM8 which is the cheapest microcontroller on the market (Low and production volumes) with the cheapest debug and development environment.

## IoT Node (RF but Connected to Power)
PCB design using the STM8S103F bread board with the nRF24L01+ module. Provides connectors for I²C, UART and One wire.
[STM8S fixed Node wiki page](http://technolab.ddns.net/display/SSN/STM8S+Fixed+Node)

## Smart IoT Node (Wireless and Cell Coin Powered)
[STM8L Mobile Node wiki page](http://technolab.ddns.net/display/SSN/STM8L+Mobile+Node)

# Links to Firmware Sources
 - [Hello World Examples](https://github.com/wassfila/STM8_IoT_HelloWorld)
 - [Complete Usecase Examples e.g. Sender + Receiver](https://github.com/wassfila/STM8_IoT_Base)

# Blabla
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

# License
- It is possible to use these designs for commercial purpose
- It is possible to modify the designs
- It is not necessary to mention the original author of these designs
- It is possible to add your own name or company on the design
- It is not possible to prevent anyone else from having the rights mentionned above
