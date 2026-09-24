# Reaction Time Tester

## Items/Software Needed

- JTAG/SD Card
- [Spartan Edge Accelerator](https://wiki.seeedstudio.com/Spartan-Edge-Accelerator-Board/)
- Vivado

## Summary

- This program uses **USER1** as the main button.
- Load the program onto the FPGA, then press the **RESET** button to start.
- Then, **CLICK**!! the **USER1** button as fast as possible to record your reaction time.

| **Response Time** | **LED Output** |
|:-----------------:|:---------------|
| **< 250 ms** | 🟢 **Green** |
| **250–500 ms** | 🔴 **Red** |
| **> 500 ms** | 🟢🔴 **Blinking Green & Red** |

## Procedures

1. Download the ZIP folder.
2. Extract the ZIP folder.
3. Find the `blinking_led.xpr` file and double-click it (make sure you have Vivado).
4. Synthesize, implement, and generate the bitstream.
5. If using an SD card, transfer the `.bit` file in the `.runs` folder to the SD card.
6. If using JTAG, open the target and connect.
