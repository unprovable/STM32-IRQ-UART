# WE KNOW WHAT THE F*CK WAS WRONG!!

Going to go through and add the phrase 'Magic pixie dust' to the places where you needed to do stuff... that way a `grep -A 4 Magic\ pixie\ dust` will locate the important stuff to get UART working with IRQ's. 

__PS__ - NVIC needs to be better defined to stop manufacturer HAL's b0rking this stuff... it should **not** be this hard!!
 
# WTFIWWM
What the f*ck is wrong with me?

This is an example STM32F103C8T6 (AKA 'blue pill') project that should setup a UART that gets triggered over the IRQ to do something.

# IT DOESN'T

So, in the spirit of sharing the rage, here's the code. I don't know why it doesn't work. I would love to know why it doens't work.

Halp.
