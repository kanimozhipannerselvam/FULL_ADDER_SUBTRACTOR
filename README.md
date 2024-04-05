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
Developed by: Kanimozhi p
RegisterNumber: 212222230060
*/

**FULL ADDER**
![image](https://github.com/kanimozhipannerselvam/FULL_ADDER_SUBTRACTOR/assets/119476060/08e8d52c-1938-419f-aa5c-eb2002c64dd2)

**FULL SUBTRACTOR**

![image](https://github.com/kanimozhipannerselvam/FULL_ADDER_SUBTRACTOR/assets/119476060/f6505f41-8950-4b0d-b24d-b94e3ab8cf8c)



**RTL Schematic**

**Full Adder** 

![image](https://github.com/kanimozhipannerselvam/FULL_ADDER_SUBTRACTOR/assets/119476060/e182060d-c15d-45a1-afa7-53429fbdd005) 

**Full Subtractor**
![image](https://github.com/kanimozhipannerselvam/FULL_ADDER_SUBTRACTOR/assets/119476060/b065a65d-d558-42c4-83e2-e397eeaf6cdb)

**Output Timing Waveform**

**Full Adder**

![image](https://github.com/kanimozhipannerselvam/FULL_ADDER_SUBTRACTOR/assets/119476060/e91d3d0a-544b-4595-860f-d95eb6bb8ea6)

**Full Subtractor**

![image](https://github.com/kanimozhipannerselvam/FULL_ADDER_SUBTRACTOR/assets/119476060/055fd86e-9a05-420a-804a-01effcdffd0e)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



