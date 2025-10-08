# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin



**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

<img width="1917" height="973" alt="image" src="https://github.com/user-attachments/assets/b9144da2-5dc3-4c40-9b44-281ee6563593" />


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

<img width="1917" height="920" alt="image" src="https://github.com/user-attachments/assets/d3d93f2d-5056-4e95-aa36-0a0f16ccc48e" />


**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: BALAMURUGAN S
RegisterNumber:25017904


**RTL Schematic**

**Output Timing Waveform**

<img width="1091" height="824" alt="image" src="https://github.com/user-attachments/assets/9a5cc81f-c923-4ab2-a82d-e0f0547d2c33" />

<img width="1079" height="832" alt="image" src="https://github.com/user-attachments/assets/8a776e6d-8be4-45e6-9d67-a7c93118d910" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



