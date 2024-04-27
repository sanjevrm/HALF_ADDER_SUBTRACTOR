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

# Procedure

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

# Developed by: Sanjev R M

# RegisterNumber:212223040186
# HALF ADDER
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/01443c66-be63-4ee3-bda9-8a8fe2887256)

# RTL Schematic
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/7dd5d579-294d-49e4-8cd3-55403584ece4)

# Truth table
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/14a828e8-1413-4504-9f80-d120e25cf1ab)


# output/TIMING Waveform
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/308de63c-e2f2-4dfb-b78f-057ce0d2f2a3)

## HALF SUBTRACTOR
# Program
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/e1050f20-8564-4596-9a67-4c9d04b22479)

# RTL Schematic
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/6d6c5cb2-acb6-45ee-bef3-20cb0e7bee95)

# Truth table
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/befc0f79-3d5a-4426-ae03-baa2bd0204a1)

# Output/TIMING Waveform
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/ab87c9b0-be0b-46f0-a749-12c08fa50c08)

# Result:
Thus the program has successfully verified.
