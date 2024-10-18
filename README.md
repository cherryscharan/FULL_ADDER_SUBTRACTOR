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

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
## FULL ADDER


![image](https://github.com/user-attachments/assets/61d8b0be-2fd1-4eea-b567-399ea52593f7)

## FULL SUBTRACTOR

![image](https://github.com/user-attachments/assets/e1f36212-833c-47c6-9b58-64eadfdc6514)



**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by: charan kumar s

RegisterNumber: 212223220015
*/

**RTL Schematic**
## FULL ADDER


![full adder](https://github.com/user-attachments/assets/a68c1198-b8c8-4f77-8057-bf7587fdbec8)

## FULL SUBTRACTOR 


![full sub](https://github.com/user-attachments/assets/159aa704-94b3-4cda-bdb7-decd0c2d0af6)


**Output Timing Waveform**

## FULL ADDER


![exp4a wave](https://github.com/user-attachments/assets/dd2f8ce6-3e74-4e35-bcec-353858549a7f)


## FULL SUBTRACTOR


![exp4b wave](https://github.com/user-attachments/assets/52fa53db-11a1-461f-b511-6594e0253044)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



