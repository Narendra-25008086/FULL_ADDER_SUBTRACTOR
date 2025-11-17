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

**Procedure**

Write the detailed procedure here

**Program:**


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

Developed by:NARENDRA KRISHNAN KS  RegisterNumber:25008086

##FULL ADDER:##

<img width="784" height="213" alt="image" src="https://github.com/user-attachments/assets/b3441bb9-1455-4281-95e8-bf60f8c94c67" />

##HALF ADDER:##

<img width="716" height="274" alt="image" src="https://github.com/user-attachments/assets/772e9996-892e-42b0-a2cf-a7e0b69b1c7a" />


**RTL Schematic**
##FULL ADDER##

<img width="711" height="400" alt="image" src="https://github.com/user-attachments/assets/f284b7df-a7b6-4c00-bb26-6ae615f1e3dc" />

##HALF ADDER##

<img width="828" height="285" alt="image" src="https://github.com/user-attachments/assets/2f388c7f-e4e0-4b69-8cdf-2b7d4adc31d6" />







**Output Timing Waveform**

<img width="834" height="199" alt="image" src="https://github.com/user-attachments/assets/f8e56b63-89aa-4d9b-8f15-3176aed90681" />

<img width="785" height="155" alt="image" src="https://github.com/user-attachments/assets/014096bd-0b85-41ec-aece-bd313d52d61d" />



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



