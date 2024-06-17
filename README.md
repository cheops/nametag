# nametag
nametag firmware for arduino pro mini 5V 16MHz 328 with OLED SSH1106 128x64 i2c

## hardware
- arduino pro mini 5V 16MHz AVR 328
- SSH1106 OLED 128x64 i2c
- 5V boost converter
- e-sigarette lipo
- lipo charge + protection board
- hardware power switch (disconnects battery + from lipo charge board)

## programming header
view from top  
board on the right (connector on left side)  
programmer on the left

```
       -> GND
GND  <--> GND
VCC  <--> VCC (5V)
TX   <--> RX
RX   <--> TX
DTR  <--> DTR
```
