# FLOALT Controller

[![CI](https://github.com/Qeteshpony/FloaltController/actions/workflows/ci.yml/badge.svg)](https://github.com/Qeteshpony/FloaltController/actions/workflows/ci.yml)

![image](https://qeteshpony.github.io/FloaltController/3D/Floalt-3D_top.png)

[Schematics](https://qeteshpony.github.io/FloaltController/)

A custom, ESP32 based controller for the 30 x 90 cm IKEA FLOALT LED light panel. This probably works with other sizes of the panel as well but i can't test this since I don't own any of them. 

I created this since my original controller got fried by a thunderstorm and IKEA does not sell these anymore in Europe. 

As a side effect this allows way better control over the panel than the original controller which kept the light very bright even at lowest settings. The board is created with KiCad 7 and with production and assembly by JLCPCB in mind. Some components have to be purchased elsewhere and manually soldered. 

The controller is powered by a 24VDV 2.5A power supply, though 1.5A are enough if you never run both warm and cold white on full power at the same time. I use ESPHome with the included code to control this, which takes care of that automatically.

The included .stl file is a simple frame to glue the board to the back of the panel. 

