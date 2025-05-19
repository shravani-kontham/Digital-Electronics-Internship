# DIGITAL ELECTRONICS 
# TASK 1
# Table of Contents


- [What is Digital Electronics](#what-is-digital-electronics)
- [Applications of Digital Electronics](#applications-of-digital-electronics)
- [Digital vs Analog Signals](#digital-vs-analog-signals)
- [Logic Levels](#logic-levels)
- [Number Systems in Digital Electronics](#number-systems-in-digital-electronics)
- [Conversion Between Number Systems](#conversion-between-number-systems)
- [Basic Logic Gates](#basic-logic-gates)


# What is Digital Electronics
Digital electronics is a branch of electronics that deals with discrete signals and circuits, as opposed to analog electronics which handles continuous signals. Digital circuits use binary logic (0 and 1) and Boolean algebra to process and store information. These circuits are the foundation of modern computers, digital communications, and numerous other technological applications. 
# Applications Of Digital Electronics
1. computation
2. communication systems
3. Automation and robotics
4. Iot smart devices
5. Home appliances
6. medical devices
7. Transportation 
8. military
# Digital vs Analog signals
|**Digital signal**                         |**Analog Signal**                      | 
|-------------------------------------------|---------------------------------------|
|continous:They vary smoothly and continuosly over time,They can take on any value within in aspecified range|Discrete: They have specific, defined values,typically represented by 0s and 1s.|
|Infinite Values: They can take on any value within a specified range|Binary: They represent information using binary code, the foundation of digital|
|Examples: Sound waves, light waves, andthe voltage from a battery|Examples: Computer data, digital radio transmissions, and digital image|
|Susceptible to Noise: They can easily be affected by noise and interference during transmission|Noise Immunity: They are more resistant to noise and interference, making them reliable for data transmission|
|Used in: Audio systems, sensors, and traditional communication systems|Used in: Computers, digital communication systems and many modern technologies|


   ![WhatsApp Image 2025-05-09 at 03 19 03_1ac7866a](https://github.com/user-attachments/assets/6932d2d7-16cd-455e-9fc7-293fb30fb6ae)
   # Logic Levels
In digital electronics, a logic level is the voltage representing a specific state,typically a binary digit (0 or1) in a digital circuit. These levels are crucial  for how devices process and transmit data, ensuring reliable communication between components.

 Positive Logic: 0V typically represents 0, and+5V or +3.3V represents 1.
 
 Negative Logic: High voltage represents 0, and low voltage represents 1.
 # Number Systems 
 In digital electronics, number systems are crucial for representing and manipulating data within electronic circuits. The most important number systems are binary (base 2), octal (base 8), and hexadecimal (base 16), with decimal (base 10) being used for human understanding. Binary is fundamental because digital systems primarily operate using two states (0 and 1).
 
 ![WhatsApp Image 2025-05-09 at 03 32 37_88748cd3](https://github.com/user-attachments/assets/902e6919-46e9-4c58-bfe1-f86c79ba8226)

# Binary Number System(Base 2)
1. Uses only two digits: 0 and 1. 
2.  Each position represents a power of 2.
  
  Example: 10101 (binary)
  
  = 21 + 23 + 20
  
  = 101 (decimal)
# Decimal Number System(Base 10)
1.  Each position represents a power of 10.
2.  The system we commonly use in everyday life.
  
 Example: 234 (decimal) 
 
 = 2 * 10^2 + 3 * 10^1 + 4 * 10^0
 
 = 234
# Hexa Decimal Number System(Base 16)
1.  Uses digits 0-9 and letters A-F (A=10, B=11, C=12, D=13, E=14, F=15).
2.  Each position represents a power of 16.
3.  Used as a shorthand for binary (each 4-bit group of binary can be
   represented by one hexadecimal digit).

  Example: AB (hexadecimal) 

  = 10 * 16^1 + 11 * 16^0
  
  = 171 (decimal)
# Octal Number System(Base 8)
1. Uses digits 0-7. 
2. Each position represents a power of 8. 
3. Used as a shorthand for binary (each 3-bit group of binary can be represented by one octal digit).
 
Example: 234 (octal)

= 2 * 8^2 + 3 * 8^1 + 4 * 8^0

= 156 (decimal)

# Conversion b/w Number Systems
 # 1.  Decimal → Binary
Method: Divide the number by 2 repeatedly, write down remainders in reverse.

Example:

 13 ÷ 2= 6 R1
 
 6 ÷ 2= 3 R0
 
 3 ÷ 2= 1 R1
 
 1 ÷ 2 = 0 R1
 
 → Binary: 1101
 
 # 2. Binary → Decimal
Method: Multiply each binary digit by 2 raised to its position (from right to left), then sum.

Example:

1101 

= 1×2³ + 1×2² + 0×2¹ + 1×2⁰ 

= 8 + 4 + 0 + 1

= 13

 # 3.  Decimal → Octal
Method: Divide the decimal by 8 repeatedly, reverse remainders.

Example:

65 ÷ 8 = 8 R1

8 ÷ 8 = 1 R0

1 ÷ 8 = 0 R1

→ Octal: 101
# 4. Octal → Decimal
Method: Multiply each octal digit by 8^position and sum.

Example:

101
= 1×8² + 0×8¹ + 1×8⁰

= 64 + 0 + 1

= 65
# 5.  Decimal → Hexadecimal
Method: Divide by 16 repeatedly, convert remainders >9 to A–F, reverse.

Example:
254 ÷ 16 = 15 R14

→ F and E

→ Hex: FE
 # 6.   Hexadecimal → Decimal
Method: Convert each digit to decimal and multiply by 16^position.

Example:

FE = F×16¹ + E×16⁰

= 15×16 + 14 

= 240 + 14

= 254
# 7.  Binary → Octal
Method: Group binary digits in 3s from right, convert each group to decimal.

Example:

110101
= 000 110 101

→ 6 5

→ Octal: 65
 # 8. Octal → Binary
Method: Convert each octal digit to 3-bit binary.

Example:

65

→ 6= 110, 5

= 101 
→ Binary: 110101
# 9. Binary → Hexadecimal
Method: Group binary digits in 4s from right, convert to hex.

Example:
11111110
= 1111 1110
→ F E 
→ Hex: FE
 # 10.  Hexadecimal → Binary
Method: Convert each hex digit to 4-bit binary.

Example:

FE
→ F= 1111,

E = 1110

→ Binary: 1111111
# 11. Octal → Hexadecimal
Method: Octal → Binary (3 bits), then Binary → Hex (4 bits).

Example:

65 (Octal) 

→ 110101 (Binary)

→ 0001 1010 1 

= 1A1 (Hex, pad as needed)
# 12.  Hexadecimal → Octal
Method: Hex → Binary (4 bits), then Binary → Octal (3 bits).

Example:

FE (Hex) 

→ 1111 1110 

→ Group in 3s: 001 111 111 0

→ pad: 000 111 111 010

→ 3 7 2 

→ Octal: 372

# TASK 2

# BASIC LOGIC GATES

# 1. AND GATE
![WhatsApp Image 2025-05-13 at 08 25 31_ddbdedde](https://github.com/user-attachments/assets/18d879fa-c403-4ef8-8685-dae258bb596d)

# Function
An AND gate is a fundamental logic gate in digital electronics that outputs a 1 (true) only if all its inputs are 1 (true). Otherwise, it outputs a 0 (false). The output is a logical product of the inputs.

# Truth Table

|A|	B	|A AND B|
|----|-----|-----|
|0	|0|	0|
|0	|1|	0|
|1|	0|	0|
|1|	1|	1|

# 2. OR GATE
![WhatsApp Image 2025-05-13 at 08 25 31_b054052b](https://github.com/user-attachments/assets/484e0bd0-ce46-497f-9721-2c8ad620dabd)

# Function
The OR gate is a digital logic gate that implements logical disjunction. The OR gate outputs "true" if any of its inputs is "true"; otherwise it outputs "false". The input and output states are normally represented by different voltage levels.
# Truth Table
|A|B|A OR B|
|-|-|------|
|0|	0|	0|
|0|	1	|1|
|1|	0|	1|
|1|	1	|1|

# 3. NOT GATE
![WhatsApp Image 2025-05-13 at 08 32 15_99d4c0e2](https://github.com/user-attachments/assets/e53ffa18-b5f4-463b-8c36-319c97f43674)

# Function
A NOT gate, also known as an inverter, is a fundamental digital logic gate that reverses its input signal. It has one input and one output. If the input is high (1), the output is low (0), and vice versa.

# Truth Table
|INPUT|	OUTPUT|
|-----|-------|
|A	| A'|
|0|	1|
|1	|0|

# 4. NAND GATE
![WhatsApp Image 2025-05-19 at 07 29 27_a65bbb54](https://github.com/user-attachments/assets/f2c1830e-4d96-4196-8d86-d7e6631be21b)

# Function
A two-input NAND gate is a fundamental digital logic gate that produces an output only when either or both inputs are low. In simpler terms, it gives a high output (1) unless both inputs are high (1), in which case, it gives a low output (0).

# Truth Table
|A|B|X|
|--|--|-|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|

# 5. NOR GATE
![WhatsApp Image 2025-05-19 at 07 38 50_e41981bb](https://github.com/user-attachments/assets/607815ff-8aee-4696-bcf2-e28cc9bc494b)

# Function
A NOR gate is a digital logic gate that gives an output of 0 when any of its inputs are 1, otherwise 1. NOR gates can be made to produce a variety of logic gates, including OR and AND gates. The output of the NOR gate is a logic 0 as long as the input voltage is below the threshold.

# Truth Table
|A|B|OUTPUT|
|--|--|--|
|0|0|1|
|1|0|1|
|0|1|0|
|1|1|0|

 # 6. XOR GATE 
 ![WhatsApp Image 2025-05-19 at 07 42 55_7585709f](https://github.com/user-attachments/assets/692553fa-c7a1-4017-9d22-df3806c8ab24)

 # Function
 An XOR (Exclusive OR) gate is a digital logic gate that produces a high (1) output only when the inputs are different. If both inputs are the same (both 0 or both 1), the output is low (0). It's also known as an "either/or, but not both" gate.

# Truth Table
|A|B|OUTPUT|
|--|--|--|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

# 7. XNOR GATE
![WhatsApp Image 2025-05-19 at 07 49 27_c7f03487](https://github.com/user-attachments/assets/258dc465-2119-4fbf-ad59-1eb950d01acd)

# Function
An XNOR (Exclusive NOR) gate is a digital logic gate that produces a high (1) output if both inputs are the same (both 0 or both 1), and a low (0) output if the inputs are different. It's essentially the inverse of an XOR gate.

# Truth Table
|A|B|OUTPUT|
|--|--|--|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|1|

 

