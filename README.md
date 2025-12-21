# 8-Bit Binary Adder

## Abstract  
This project implements an **8-bit binary adder** using two **74LS283 4-bit full adder ICs**. The circuit takes two 8-bit binary inputs provided through DIP switches and produces their sum. The result is displayed using LEDs, where each LED corresponds to a bit in the binary sum (from 2⁰ to 2⁷).  

This project demonstrates fundamental concepts in digital electronics, including binary addition, cascading of 4-bit adders to achieve 8-bit operation, and visual output representation using LEDs.

---

## Features
- **8-bit Binary Addition** using TTL logic ICs.  
- **Cascaded 74LS283 Chips** to handle full 8-bit arithmetic.  
- **Inputs**: DIP switches to provide two 8-bit numbers.  
- **Outputs**: LEDs that display the resulting binary sum.  

---

## Components Used
- **74LS283** – Two 4-bit full adders (cascaded for 8-bit addition).  
- **DIP Switches** – User input for binary numbers A and B.  
- **Resistors** – Current limiting for LEDs.  
- **LEDs** – Display of binary output sum.  
- **Perfboard** – For mounting and wiring the circuit.  

---

## Circuit Overview
- The two 74LS283 ICs are connected in cascade.  
- The carry out from the lower 4-bit adder is connected to the carry in of the higher 4-bit adder.  
- LEDs represent the resulting sum bits.  

---

## Working Principle
- Each DIP switch represents a bit of the binary input.  
- The adder ICs perform binary addition in parallel.  
- LEDs glow according to the output bit value (`1` = ON, `0` = OFF).  

---

## Project Image  
![IMG_20250423_232046](https://github.com/user-attachments/assets/69d95c73-12ab-4632-aab4-ed9b1f11d93d)


---  
