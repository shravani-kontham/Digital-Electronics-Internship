# DIGITAL ELECTRONICS 
# TASK 1
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
  
  Example: 10101 (binary) = 21 + 23 + 20 = 101 (decimal)
# Decimal Number System(Base 10)
1.  Each position represents a power of 10.
2.  The system we commonly use in everyday life.
  
 Example: 234 (decimal) = 2 * 10^2 + 3 * 10^1 + 4 * 10^0 = 234
# Hexa Decimal Number System(Base 16)
1.  Uses digits 0-9 and letters A-F (A=10, B=11, C=12, D=13, E=14, F=15).
2.  Each position represents a power of 16.
3.  Used as a shorthand for binary (each 4-bit group of binary can be
   represented by one hexadecimal digit).

  Example: AB (hexadecimal) = 10 * 16^1 + 11 * 16^0 = 171 (decimal)
# Octal Number System(Base 8)
1. Uses digits 0-7. 
2. Each position represents a power of 8. 
3. Used as a shorthand for binary (each 3-bit group of binary can be represented by one octal digit).
 
Example: 234 (octal) = 2 * 8^2 + 3 * 8^1 + 4 * 8^0 = 156 (decimal)

# Conversion b/w Number Systems
 # 1.  Decimal → Binary
Method: Divide the number by 2 repeatedly, write down remainders in reverse.

Example:
13 ÷ 2 = 6 R1
6 ÷ 2 = 3 R0
3 ÷ 2 = 1 R1
1 ÷ 2 = 0 R1
→ Binary: 1101
 # 2. Binary → Decimal
Method: Multiply each binary digit by 2 raised to its position (from right to left), then sum.

Example:
1101 = 1×2³ + 1×2² + 0×2¹ + 1×2⁰ = 8 + 4 + 0 + 1 = 13

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
101 = 1×8² + 0×8¹ + 1×8⁰ = 64 + 0 + 1 = 65
# 5.  Decimal → Hexadecimal
Method: Divide by 16 repeatedly, convert remainders >9 to A–F, reverse.

Example:
254 ÷ 16 = 15 R14 → F and E
→ Hex: FE
 # 6.   Hexadecimal → Decimal
Method: Convert each digit to decimal and multiply by 16^position.

Example:
FE = F×16¹ + E×16⁰ = 15×16 + 14 = 240 + 14 = 254
# 7.  Binary → Octal
Method: Group binary digits in 3s from right, convert each group to decimal.

Example:
110101 = 000 110 101 → 6 5 → Octal: 65
 # 8. Octal → Binary
Method: Convert each octal digit to 3-bit binary.

Example:
65 → 6 = 110, 5 = 101 → Binary: 110101
# 9. Binary → Hexadecimal
Method: Group binary digits in 4s from right, convert to hex.

Example:
11111110 = 1111 1110 → F E → Hex: FE
 # 10.  Hexadecimal → Binary
Method: Convert each hex digit to 4-bit binary.

Example:
FE → F = 1111, E = 1110 → Binary: 1111111
# 11. Octal → Hexadecimal
Method: Octal → Binary (3 bits), then Binary → Hex (4 bits).

Example:
65 (Octal) → 110101 (Binary) → 0001 1010 1 = 1A1 (Hex, pad as needed)
# 12.  Hexadecimal → Octal
Method: Hex → Binary (4 bits), then Binary → Octal (3 bits).

Example:
FE (Hex) → 1111 1110 → Group in 3s: 001 111 111 0 → pad: 000 111 111 010 → 3 7 2 → Octal: 372

# TASK 2

# BASIC LOGIC GATES
1. AND Gate
2. OR Gate
3. NOT Gate

# 1. AND GATE
![WhatsApp Image 2025-05-13 at 08 25 31_ddbdedde](https://github.com/user-attachments/assets/18d879fa-c403-4ef8-8685-dae258bb596d)

# Function
AND gates have two inputs. The output of an AND gate is on only if both inputs are on.
If at least one of the inputs is off, the output will be off.

A and B are both in an On state, the output (out) will be an On state. If either A or B is in an Off state, the output will also be in an Off state.
A and B must be On for the output to be On.

# Truth Table

|A|	B	|A AND B|
|----|-----|-----|
|On	|On|	On|
|On	|Off|	Off|
|Off|	On|	Off|
|Off|	Off|	Off|

# 2. OR GATE
![WhatsApp Image 2025-05-13 at 08 25 31_b054052b](https://github.com/user-attachments/assets/484e0bd0-ce46-497f-9721-2c8ad620dabd)

# Function
if at least one of the inputs are on. If both inputs are off, the output will be off.

 if either A or B is On, the output (out) will also be On. If both A and B are Off, the output will be Off.

# Truth Table
|A|B|A OR B|
|-|-|------|
|On|	On|	On|
|On|	Off	|On|
|Off|	On|	On|
|Off|	Off	|Off|

# 3. NOT GATE
![WhatsApp Image 2025-05-13 at 08 32 15_99d4c0e2](https://github.com/user-attachments/assets/e53ffa18-b5f4-463b-8c36-319c97f43674)

# Function
The NOT logic gate has only one input. If the input is On then the output will be Off. In other words, the NOT logic gate changes the signal from On to Off or from Off to On. It is sometimes called an inverter.

# Truth Table

|INPUT|	OUTPUT|
|-----|-------|
|A	|NOT A|
|On|	Off|
|Off	|On|

