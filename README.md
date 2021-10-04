# node-red-obniz-examples #

Examples for obniz devices controlled by Node-RED

This repository contains a growing collection of examples for electronic circuits based on [obniz boards](https://obniz.com/) and controlled by [Node-RED](https://nodered.org/). The are organized around the parts found in the [Keyestudio 48 in 1 Sensor Kit](https://wiki.keyestudio.com/KS0349_Keyestudio_48_in_1_Sensor_Kit) in order to help my students to carry out web-based or cloud-connected hardware projects without requiring too much affinity to electronics.

> Please note: this work is currently in progress. While it may already be used, do not expect it to be finished before end of October 2021.

## Background ##

**Obniz boards** are microcontroller boards based on the [ESP-WROOM-32](https://www.espressif.com/en/products/modules/esp32) with an additional OLED display and a three-way switch on-board and additional circuitry to make GPIOs 5V tolerant and robust even against short-circuits.

The boards and their firmware have been designed to be connected to local Wifi networks out-of-the-box and without any need for additional hardware. The devices then connect to a server operated by Obniz and provide a REST interface via which they can be controlled. In contrast to most other microcontroller boards the idea is therefore *not* to program the controller itself but to get access to its components and I/O pins over the internet.

This approach makes obniz devices unusable without an active internet connection (or while the servers at obniz are down) and cause an extra latency (making them unsuitable for real-time applications), but if the planned project requires internet access anyway, these drawbacks may not weigh so heavy - particularly since, on the other side, the offered hardware is astonishing robust and may therefore also be used by novices in electronics.

**Keyestudio** offers dozens of different sensors and actors on small boards which may be (plugged into breadboards and) directly connected to a microcontroller - at reasonable prices. Using such modules can speed up hardware development and reduce wiring and soldering efforts.

The 48-in-1 sensor kit contains the following modules

<table>
 <tr><td></td><td></td><td></td></tr>
</table>
