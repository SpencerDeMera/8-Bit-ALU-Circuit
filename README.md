# 8-Bit Adder/Subtractor ALU Circuit

## Project Description
This project is my design of a basic ALU that can perform addition, subtraction, and bitwise logic operations. This project was designed in Logisim Evolution purely through the use of logic design via logic gates. 

I additionally developed a simplified second circuit in hardware with breadboards once my virtual designs were complete. It is merely a proof of concept and exercise of my knowledge. This physical component is built entirely in hardware with 7400 series TTL chips, breadboards, and wires. This circuit works entirely in 8-bit binary via the TTL chips and I/O modules. Input is taken in via 8-switch dip switches and output is displayed across individual LEDs in binary representation. Addition will be displayed in normal signed magnitude and subtraction will be displayed in 2’s complement binary form. There are also three flag LEDs for the purpose of declaring a leftover carry out/integer overflow, a zero flag, and a sign flag (for the purpose of declaring whether an output is negative). Additionally, to control whether or not to do addition or subtraction there is another dip switch that acts as a control input. High control input denotes subtraction while low control input denotes addition, additional is default.

The physical portion has limitations in that it does not contain various functions present in my digital design (such as bitwise logic operations, op error flags, etc.).

## Depth
A more in depth discription of the project, its design, and visuals of both the software and hardware based implementations can be foudn in the attached PDF document.

## Tool & Technologies Used
- Logisim Evolution
- Tinkercad Online
- Digital Computer Electronics By Dr. Albert Paul Malvino
