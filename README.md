# IR-Remote---Laser-Tag---Blynk---ESP8266
Blynk Controlled Laser Tag Wireless Remote for Testing/Configuration


This is a simple sketch that is used to generate customizable IR TAGS to send to laser tag equipment. It is set with a 25 bit protocol with high represented as a 1000 microsecond pulse and low represented with 500 microsecond pulse.

It is made to compile via Arduino on either an ESP32 or and ESP8266 and has a single pin for use GPIO4 on esp8266 and will need to be changed in the code if using ESP32

This is controlled via the Blynk mobile application and the QR is provided for quick download

When setting up this application and a device, simply copy the authentication code from the blynk app and paste into the code and you are good to go.

I do not show a resistor in the diagram, honestly I argue it's need... it's for testing and the pulses are so short I could care less. It's also being driven at 3.3 v on an esp at a potential of 20 mA and the peak forward current of the task is 200mA at 5v. If your concerned about the esp dumping 10 times more than it's capacity, add a resistor.

Enjoy!
