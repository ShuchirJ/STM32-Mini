# STM32 Mini
A small, stm32f072 devboard in the pico form factor! I've played around with the RP2040 and various ESP32 chips for the past few years, but I wanted to try something different. The STM32 series of microcontrollers are very popular especially for low power usage, and I wanted to try using one myself. There's also less abstraction (imo-at least compared to MicroPython) when writing code for the STM32 and I think it'd be a great chance for me to advance my skills a little. 

![render](src/renders/pcb.png)
![schematic](src/renders/schematic.svg)

## Stackup
The board follows a SIG-GND-PWR-SIG stackup.

SIG (1):
![alt text](src/renders/image.png)

GND (2):
![alt text](src/renders/image-1.png)

PWR (3):
![alt text](src/renders/image-2.png)

SIG (4):
![alt text](src/renders/image-3.png)

### BOM
The bill of materials for this board can be found at [src/PCB/BOM.xlsx](src/PCB/BOM.xlsx). Additionally, 1x20 male headers will be bought separately from AliExpress ([https://www.aliexpress.us/item/2255800867206912.html](https://www.aliexpress.us/item/2255800867206912.html)) and soldered onto the board.