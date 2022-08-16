The version 2 Sense HAT includes an onboard colour sensor that can be used to measure the amount of light that is hitting the sensor, and detect the quantities of red, green and blue light.

To sense colour on the SenseHAT is easy - simply hold up something in front of the SenseHAT (the colour sensor is on the top, near the LED array) and it will detect the colour and intensity of the light reflected off the object and entering the sensor. 

If you hold up a red teddy bear, the colour sensor will detect that the light in front of it is primarily red. If you point it at the sky, it will detect a higher intensity of light and indicate that it is blue. Pointing the light sensor at the grass will show that there is mostly green light in the environment. 

When the sensor is polled, these colour values are stored in a list as the `red`, `blue`, `green` and `clear` values. You can use this data in your code by storing it as a variable.
