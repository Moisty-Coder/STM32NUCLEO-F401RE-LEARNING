## BLINKING LED

### Function:
This program blinks the LED light on the micontroller using the HAL_DELAY function. The delay is based on a global uint32_t variable (in ms) that I have initalized before main. 

### What I have Learned:
There are functions knows as HAL that abstarcts away from bare-metal coding, which is useful for beginners like me. However, I should understand the inner workings of the functions to get a better understanding on what it's actually doing.

### Special .ioc Configurations:
PA5 (GPIO Pin 5) has been renamed to GREEN_LED

*Date: Sometime before 24/8/2026

##

## BLINKING LED V2

### Function:
Aims to use HAL_GetTick() instead of HAL_Delay(). Delaying means stopping the code from progressing, which blocks the whole program for the set time. This is inefficient as it wastes power and does not allow the CPU to handle tasks simultaneously.

### Extra Things:
I also have tried included #defines for readability, and initilizing the LED before the infinite loop starts. These concepts will be useful in the future.

*Date: 28/8/2026