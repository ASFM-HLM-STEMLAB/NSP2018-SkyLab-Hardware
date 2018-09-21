# NSP2018-SkyLab-Hardware
ASFM Near Space Program 2018 - SkyLab FlightComputer Hardware

## Welcome to NSP2018-SkyLab-Hardware repository
The flight computer consists of a *ESP32* Microcontroller in the Adafruit Feather form factor. 
[ESP32](https://www.adafruit.com/product/3405)

* Optionally we are waiting for Particle.io to release their new mesh line of MCUs. We love the development environment from Particle.io and their devices. For now we are awaiting for them to release the line, we should test compatibility when they do and hope for the best.<small>

This device contains an onboard GPS, LoRa Radio, SDCard and Internal Pressure and Temp Sensor. It is designed to interface with an optional external Iridium RockBlock Satelite Module:
[RockBlock Sat Modem](https://www.sparkfun.com/products/14498)

Also contains ports for external sensors, both in i2c and SPI. It also has a couple of mosfets for a buzzer and a beacon or optionally an electric match to prevent floaters.

See the attached BOM for details

The internal GPS is a U-Blox GPS picked because it allows the device to be effective above the 60,000ft gps limit.

Designed in Autodesk Eagle.
by: Francisco Lobo
at ASFM STEM LAB Monterrey
[HLM STEM-LAB Instagram](https://www.instagram.com/asfmstemlab/)

=======
