# ESPHome Secure Garage Config
Secure ESPHome Configuration for a garage door 

I wanted to make my garage door smart by connecting the motor to an ESP32 flashed with ESPHome.
From the tutorials I have found, I was unable to find one which prevented me from closing the door, if the door was already closed, or, if it is closed, asking to close it (which would then open it)

I've configured my magnetic read switch on pin 13 and the relay on pin 2. This can be changed around as desired.
