# Reaction Time Tester

## Items/Software needed

- JTAG/sd Card
- Spartan Edge Acceletor (https://wiki.seeedstudio.com/Spartan-Edge-Accelerator-Board/)
- Vivado

## Summary
- This program uses USER1 as the main button
- You load the program onto the FPGA, and you can run it by clicking the reset button
- Then CLICK on the USER1 button as fast as possible to record how fast your reaction is
  
| **Response Time** | **LED Output** |
|:-----------------:|:---------------|
| **< 250 ms**      | 🟢 **Green** |
| **250–500 ms**    | 🔴 **Red** |
| **> 500 ms**      | 🟢🔴 **Blinking Green & Red** |

## Procedures

1. Download the ZIP folder
2. Extract the ZIP folder
3. Find the blinking_led.xpr file and double-click (make sure you have Vivado)
4. Synthesize, implement, and generate bitstream
5. If using an SD card, transfer the bit file in the .runs folder to the SD card
6. If using JTAG, just open the target and connect.
