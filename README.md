# Omron-Arduino
Arduino code to get data out of the incredible 4x4 IR OMRON MEMS sensor.
Omron D6T is a MEMS IR sensor that has the distinct advantage of sensing human presence even if the individual is stationary. The sensor array also allow sensing of movement direction of the person.

Example Image from the Omron D6T 4x4 array:

![alt tag](ExampleImage.png?raw=true "Image Title")

In this image the brighter pixels correspond to a warmer body. Note that the OMRON D6T-44L returns data in a 4x4 format. To view the result in a large image like this, I used Matlab to resize to a much larger image and mapped the image intensities with some sensible intensity transforms (power transform).
