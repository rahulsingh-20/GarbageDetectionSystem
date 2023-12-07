# Garbage Monitoring System
created by group-4 for the course 'Embedded Systems and IoT'.

Group 4 members:
<ul>
  <li>Rahul Singh</li>
  <li>Anupam Dwivedi</li>
  <li>Anoop Kumar</li>
  <li>Ritwik R</li>
  <li>Krishnapal Panwar</li>
</ul>

## Objective:
Our objective is to built an IoT system that can track garbage levels in a network of dustbins and notify waste management teams when the bins need to be emptied.

## Architecture:
The system includes an ultrasonic sensor that is connected to an ESP8266 board. The sensor monitors the garbage level in the dusbin and assigns the level a value from 0 to 3 based on the distance of the top of the pile from the lid of the bin, and sends this data to a ThingSpeak channel at regular intervals, which can be accessed through a web application. Once the level reaches 3, the application displays an alert to the concerned authorities, indicating that the bin needs to be emptied.

## Hardware used:
<ul>
  <li>ESP8266 board</li>
  <li>Ultrasonic sensor</li>
  <li>Jumper wires</li>
  <li>Breadboard</li>
</ul>

## Software used:
<ul>
  <li>ThingSpeak - IoT data analytics platform (to store the data gathered)</li>
  <li>Arduino IDE to program the ESP8266 board</li>
  <li>VS Code to create the web application</li>
</ul>

## Project Setup

![iot_setup](https://github.com/rahulsingh-20/GarbageDetectionSystem/assets/76691609/e4b456aa-60b3-4888-92e0-96dbf5482241)

## ThingSpeak Setup

![thingspeak](https://github.com/rahulsingh-20/GarbageDetectionSystem/assets/76691609/1313ba29-0ad1-4648-b7a4-c578f8e1a408)

## Web Application

![Screenshot from 2023-12-07 04-50-34](https://github.com/rahulsingh-20/GarbageDetectionSystem/assets/76691609/68aff6d2-11ec-4f6b-a864-29297515a511)

## Demonstration video

https://drive.google.com/file/d/192v2f0acF1me_tjzxvFuoUBeAiwgEwkw/view?usp=sharing
