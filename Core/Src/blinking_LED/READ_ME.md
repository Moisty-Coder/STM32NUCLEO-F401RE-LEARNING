## BLINKING LED

### Function:
This program blinks the LED light on the micontroller using the HAL_DELAY function. The delay is based on a global uint32_t variable (in ms) that I have initalized before main. 


### What I have Learned:
This program is my first step into the world of embedded firmware. Firstly, I have learned that several functions have already been prepared (known as HAL) which I can use to control peripherals without writing bare-metal code. Overall, this program is the first major milestone, and I will continue to progress through the other peripherals on the board.

### Special .ioc Configurations:
PA5 (GPIO Pin 5) has been renamed to LED_GREEN


*Date: Sometime before 24/8/2026

##

## BLINKING LED V2

### Function:
Aims to use HAL_GetTick() instead of HAL_Delay(). Delaying means stopping the code from progressing, which blocks the whole program for the set time. This is inefficient as it wastes power and does not allow the CPU to handle tasks simultaneously.

### Extra Things:
I also have tried included #defines for readability, and initilizing the LED before the infinite loop starts. These concepts will be useful in the future.

*Date: 28/8/2026