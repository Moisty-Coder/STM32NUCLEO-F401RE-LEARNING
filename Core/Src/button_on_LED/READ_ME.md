## BUTTON ON LED

### Function:
This program functions to turn on the LED when the blue button (B1) is pressed/held. When the button is released, the LED will turn off.

### What I have Learned:
The main thing I have learned is that pin status can be read through the HAL function (HAL_GPIO_ReadPin). The weird thing is that for the button, the non-pressed state returns a '1', while a pressed state returned a '0'. This is intuitively flipped for the LED. 

This is also the first program to use basic C concepts like if statements. I love the debugging process of changes in my code that reflects to real-life visible results on my board. Overall great stepping stone!

## Special .ioc Configurations
PA5 (GPIO Pin 5) has been renamed to LED_GREEN

Date: 24/8/20226