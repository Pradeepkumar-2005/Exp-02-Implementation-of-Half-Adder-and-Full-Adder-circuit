# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
##FULL ADDER 
![Screenshot 2023-11-26 142647](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/8c3e00e4-40e3-472c-afb6-64d8ed0d60bd)



##HALF ADDER 
![Screenshot 2023-11-26 141415](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/2854447d-34af-4614-b347-e73f470ee4ce)


/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Pradeep kumar R
RegisterNumber:  23006358
*/

Logic symbol & Truthtable

##FULL ADDER

![Exp3 truthtable (fa)](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/23d936df-9001-40d1-b8c7-19a44b131621)


##HALF ADDER

![Exp3 truthtable (ha)](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/4b457e6c-2e8d-42f5-805c-a0ef5f9eebb0)




RTL realization
##FULL ADDER

![Screenshot 2023-11-26 142628](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/00ebd88d-8cda-4165-a6f7-2aeff08c5c07)


##HALF ADDER

![Screenshot 2023-11-26 141354](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/85fe8beb-2ecc-443a-8940-459c6a9df0b2)




### Output:
##FULL ADDER

![Screenshot 2023-11-26 142532](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/d2c4d59d-bb79-484a-97a5-bb635335c5ca)


##HALF ADDER

![Screenshot 2023-11-26 141326](https://github.com/Pradeepkumar-2005/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147474038/12d8ec95-0d08-4c3f-929d-fdb55c425a74)

### Result:
