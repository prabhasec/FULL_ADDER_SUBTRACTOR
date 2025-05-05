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

![image](https://github.com/user-attachments/assets/6e734817-7e76-408a-87ed-a6040a6495dd)

![image](https://github.com/user-attachments/assets/f97a0e5c-3574-45bd-b8f9-32dfc6deda5c)


**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

![Screenshot 2024-12-04 113005](https://github.com/user-attachments/assets/75a5fd95-7eae-4be1-8ba3-163340d7006b)

![Screenshot 2024-12-04 113809](https://github.com/user-attachments/assets/acb3854e-26bc-4f6b-a429-d57a3d78e2bb)


**RTL Schematic**

![Screenshot 2024-12-04 112942](https://github.com/user-attachments/assets/c0372d1e-8bfe-4ade-853c-03f09fc5c3c9)

![Screenshot 2024-12-04 114033](https://github.com/user-attachments/assets/54c44e6b-de6f-420a-a65b-4a489df4933e)


**Output Timing Waveform**

![Screenshot 2024-12-04 112914](https://github.com/user-attachments/assets/c447937f-5722-4a65-b610-4ac6090de3b9)

![Screenshot 2024-12-04 114005](https://github.com/user-attachments/assets/6abe9e49-e6fc-47d5-bbab-b482416c7bf7)




**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



