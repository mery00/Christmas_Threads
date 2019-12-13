# Christmas_Threads
This university project is based on the stm32f3discovery board.

## Overview

This project was made for the class of Embedded Systems. The official material of the class was the STM32F3discovery and the real time operative system ChibiOS. You can find information on the board at [this link](https://www.st.com/en/evaluation-tools/stm32f3discovery.html) and on the RTOS at [this link](http://chibios.org/dokuwiki/doku.php). 
For this project you need ChibiStudio software correctly installed (You can download it at [this link](http://chibios.org/dokuwiki/doku.php?id=chibios:product:chibistudio:start).

The program reads data from the accelerometer and the user button, and allows to play diffenrent Christmas songs with a buzzer, and 7 different LEDs turn on and off in time of music.

### What hardware you need
- 1 STM32F3Discovery
- 7 coloured LEDs
- 1 buzzer
- A breadboard
- A lot of jumper cables

### The circuit
The used pins for the LEDs are: PE8, PE10, PE11, PE12, PE13, PE14, PE15. The PE9 pin is used for the buzzer, and also the V3 pin, and the GND pin that is the ground pin.

## Flash and Run the code
Download the zipped code, unzip it, open ChibiStudio and import "existing project". Connect the board to an USB plug, then click on the "External Tool" icon in the upper part of the IDE and select "OpenOCD on STLink ..." and select the correct configuration file at the path "ChibiStudio\tools\openocd\scripts\board\stm32f3discovery.cfg". You are ready to run the debug configuration of the code.

### Collaborators
- Marialuisa Trerè - [mery00](https://github.com/mery00)
- Simone Faiella - [simoneFaiella](https://github.com/SimoneFaiella)
