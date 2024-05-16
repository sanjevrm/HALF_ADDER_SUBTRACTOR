# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

## AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

## Half Adder

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/57ab1129-667f-4ca4-8789-12532abd5823)


Figure -01 HALF ADDER

## Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/bed14a5c-be0b-463b-aac1-4b5c1661eeef)


Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

## Program

```
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Sanjev R M
RegisterNumber: 212223040186
```
## Half Adder
### Program
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/9443a692-54aa-4a8b-8578-9b90cf7c70b7)

### Truth Table
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/7d6b9314-bad7-4008-b6b1-9646ca153807)

### RTL Schematic
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/fc959378-f2b0-4f30-89c5-da6fe7edde6e)

### Output/TIMING Waveform
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/a981f86c-51e3-4a99-8630-0e3e01631f70)

## Half Subtractor
### Program
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/c0473b39-fe2f-439b-bf67-103b5156d347)

### Truth Table
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/f4c90062-1d81-47b2-be46-dad559c5b978)

### RTL Schematic
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/99ba94fe-921c-4be7-a396-7c3e41689fe1)

### Output/TIMING Waveform
![image](https://github.com/sanjevrm/HALF_ADDER_SUBTRACTOR/assets/155142423/170b94d0-3206-4708-8620-262555717e60)

### Result:
Thus the program was successfully verified.
