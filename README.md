# Digital Stopwatch using NI Multisim

## Overview
This project implements a digital stopwatch using TTL logic components in NI Multisim. The stopwatch counts time and displays the result on two seven-segment displays.

The design uses BCD counters and seven-segment display drivers to simulate a basic stopwatch system.

## Features
• Start / Stop control  
• Reset functionality  
• Time displayed using 7-segment displays  
• Implemented using standard TTL ICs  

## Components Used
- 74LS190 Up/Down BCD Counter
- 7447 BCD to Seven Segment Decoder
- Seven Segment Displays
- Clock Generator
- Push Button Switches
- Power Supply (5V)

## Working Principle
1. The clock generator produces periodic pulses.
2. These pulses are given to the 74LS190 BCD counter.
3. The counter increments the count for every clock pulse.
4. The BCD output is sent to the 7447 decoder.
5. The decoder drives the seven-segment display to show the current count.

Two counters are cascaded to display two digits of the stopwatch.

## Simulation
The circuit was designed and tested using NI Multisim.

The stopwatch counts seconds using a clock signal and updates the display in real time.

## Circuit Diagram
![Circuit](images/circuit.png)

## Applications
• Digital timers  
• Electronic clocks  
• Embedded system learning  
• Digital electronics education  

## Author
Laxmi Sathvika Chenna
