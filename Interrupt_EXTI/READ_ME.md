## INTERRUPT (EXTI)

### Function:
This program aims to use the interrupt feature "EXTI". The program starts off with the LED turned off. The program will keep checking to see if the button is pressed. When it does, an interrupt fires and turns on the LED.

## What I have Learned:
Interrupts are useful in events where user inputs are unpredictable and can happen at any given time the cpu is running. Thus, HAL_GetTick is unsuitable for this case because it relies on fixed tick rates.

EXTI is useful for emergency switches where one button push will shut the whole program down safely.

## Special Configurations:

### User Labels
PA5: Green_LED,   
PC13-ANTI_TAMP: BLUE_BUTTON

BLUE_BUTTON
- GPIO Mode: External Interrupt Mode with Falling edge trigger detection (interrupt occurs when pressed)

- GPIO Pull-up/Pull-down: Pull-up


 

