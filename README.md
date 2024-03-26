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

**HALF ADDER**:

![Screenshot (84)](https://github.com/saravidhya/HALF_ADDER_SUBTRACTOR/assets/87062069/9fff8708-afbc-404e-80d0-a348bb114ac6)


**HALF SUBTRACTOR**:

![Screenshot (86)](https://github.com/saravidhya/HALF_ADDER_SUBTRACTOR/assets/87062069/0579c8df-b0ad-4446-83a8-c224cdd3ed64)



Developed by: Vidhiya Lakshmi S

RegisterNumber: 212223230238

**RTL Schematic**

**HALF ADDER**:

![Screenshot 2024-03-20 201221](https://github.com/saravidhya/HALF_ADDER_SUBTRACTOR/assets/87062069/3175890d-69b4-4641-bbea-4b30690cde52)



**HALF SUBTRACTOR**:

![Screenshot 2024-03-20 203142](https://github.com/saravidhya/HALF_ADDER_SUBTRACTOR/assets/87062069/0e674942-c997-4805-802c-ba0e9073420c)


**Output/TIMING Waveform**

**HALF ADDER**:

![Screenshot (85)](https://github.com/saravidhya/HALF_ADDER_SUBTRACTOR/assets/87062069/71b0c817-755c-49c0-a77b-80af24dc086b)

**HALF SUBTRACTOR**:

![Screenshot 2024-03-20 203142](https://github.com/saravidhya/HALF_ADDER_SUBTRACTOR/assets/87062069/a4087983-d110-4eca-aee1-5051f406409a)



**Result:**
