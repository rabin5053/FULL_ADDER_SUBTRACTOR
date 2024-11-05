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

**Program:**![Screenshot 2024-11-05 090958](https://github.com/user-attachments/assets/241ca5ba-7868-4445-99d6-a120808c9b11)![Screenshot 2024-11-05 092612](https://github.com/user-attachments/assets/2f6987ad-cc67-4512-91de-d4fca7b43301)



/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:Rabin.R RegisterNumber:
24900518

**RTL Schematic**![Screenshot 2024-11-04 215859](https://github.com/user-attachments/assets/745a435f-239d-4e61-bb9a-83c10dad8358)![Screenshot 2024-11-05 091257](https://github.com/user-attachments/assets/f02ccfdd-0a6e-4845-b72e-ed55e7fbe131)



**Output Timing Waveform**
![Screenshot 2024-11-05 091550](https://github.com/user-attachments/assets/779d128a-d991-42d3-930e-6c04bcb96305)![Screenshot 2024-11-05 094504](https://github.com/user-attachments/assets/554f40d1-c3ef-40ff-a040-2451d26a1329)


**Result:**
 Thus the full adder and full subtractor has been implemented and verified
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



