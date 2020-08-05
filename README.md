# iot-project
iot project with Raspberry Pi and using MQTT protocol
## Introduction
The purpose of this project is to create a system for measuring and controlling the temperature in a building as well as providing an intuitiv interface to the system.
There is an emphasis on using the M2M protocol MQTT for communication purposes.

## Requirements
* A single temperature sensor connected through a Raspberry Pi
* A graphical user interface implemented on a Raspberry Pi with an LCD screen
* A web user interface
* UIs should let user see real time temperature, historical temperature and change the control policy
* Emulate a temperature controller with the Raspberry Pi
* Local logging of all events on the RPi
* Remote logging of all events to a database in the cloud
* Reply to ping messages from remote MQTT Broker

