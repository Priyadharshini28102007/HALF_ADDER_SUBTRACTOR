# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:  E.Priyadharshini     RegisterNumber:  25014488    */

<img width="1897" height="752" alt="Screenshot 2025-12-14 184747" src="https://github.com/user-attachments/assets/89c1d00b-948a-4836-b954-b6c45ad05685" />
<img width="1896" height="907" alt="Screenshot 2025-12-14 184707" src="https://github.com/user-attachments/assets/17c34f49-2703-4490-88d5-00336a9d38f3" />

**RTL Schematic**

<img width="1886" height="936" alt="Screenshot 2025-12-14 184252" src="https://github.com/user-attachments/assets/c1893eb9-e006-47c5-9a4f-bace02c7a1a3" />
<img width="1916" height="967" alt="Screenshot 2025-12-14 184845" src="https://github.com/user-attachments/assets/f80671e0-d122-4353-8f50-7e6730928c2b" />

**Output/TIMING Waveform**

<img width="1913" height="430" alt="Screenshot 2025-12-14 184433" src="https://github.com/user-attachments/assets/c58ef1ad-c006-4b59-a4f0-95b5895e5467" />
<img width="1909" height="491" alt="Screenshot 2025-12-14 185338" src="https://github.com/user-attachments/assets/b0436d5f-b9ba-4177-a1ef-55e2e4907b9e" />

**Result:**

 Thus the given design implement and verified using truth table. 
