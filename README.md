# ESPHome Secure Garage Config
Secure ESPHome Configuration for a garage door 

I wanted to make my garage door smart by connecting the motor to an ESP32 flashed with ESPHome.
From the tutorials I have found, I was unable to find one which prevented me from closing the door, if the door was already closed, or, if it is closed, asking to close it (which would then open it)

The script basically, when calling an open or close, checks if the garage is already in that state, otherwise, if it is in the other state, it will trigger the correct action.

I've configured my magnetic read switch on pin 13 and the relay on pin 2. This can be changed around as desired.
