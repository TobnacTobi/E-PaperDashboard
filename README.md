# E-PaperDashboard
An Dashboard made on an ESP32 which drives an Waveshare 7.5in E-Ink Display

## Features (TODO)
The EPD can be divided into multiple areas that show individual data, retrieved from variable APIs or WebServers.  
It displays SWU Departure Information of a given Stop.  
It displays Weather data for a given city.  
It displays Custom Information, retrieved from an individual WebServer.  
It displays Images, downloaded from an individual WebServer.  
Very low power consumption so it can be run with a relatively small power bank (2Ah) for multiple days/months

## Hardware
1x [ESP32 from AZ-Delivery](https://www.az-delivery.de/products/esp32-developmentboard), [Manual](https://www.az-delivery.de/a/downloads/-/9f1e739bd625deb8/134823a6ab91089f)  
1x [Waveshare 7.5in E-Ink Display (with HAT)](https://www.waveshare.com/7.5inch-e-paper-hat.htm) (could basically be any size)  
1x 7.5in Frame to hold the display + ESP32  
1x Power Bank of any size (e.g. 2Ah) to power the system in a mobile environment.

## Libraries
This project heavily uses the [GxEPD2 Library](https://github.com/ZinggJM/GxEPD2) of Jean-Marc (ZingJM), who [helped me a lot](https://forum.arduino.cc/t/waveshare-e-paper-display-hat-not-working-with-esp32-dev-kit-c-v2/1064415)!  
Some Modules are part of an [library](https://github.com/G6EJD/ESP32-e-Paper-Weather-Display) by G6EJD.  
[ArduinoJson](https://arduinojson.org) is important to read API Information.

## Usage (TODO)
I don't know how this will be usable yet.
