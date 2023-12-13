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

###Procedure

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
### Program:

###Half Adder

![hf pro 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/068d4a9f-b20f-44c5-b180-cf8d1bac87f5)

###Full Adder

![full pro 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/38a17572-7e8e-427b-b299-ff9a77de6832)


/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: PRAJAN P
RegisterNumber: 23013995
*/
Logic symbol & Truthtable
###RTL realization

###Half Adder

![hf rtl 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/5452a27a-45de-4748-a86d-8d076b584665)

###Full Hadder

![fh rtl 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/fe44a2d7-d6d3-4f1d-8790-ff995ab26e11)


### Output:


### TRUTH TABLE 

###Half Adder

![hf tr 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/6abd6c54-707c-4284-b836-ce27295ac814)

###Full Hadder

![ful tr 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/ea795c02-164e-44e0-a97d-03b8594d418a)

###Timing Diagram

###Half Adder 

![hf td 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/d4b05cc7-96e4-4bb6-9de9-27e49e2103b8)

###Full Adder 

![full td 3](https://github.com/PRAJAN-23013995/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150313345/bd9392ed-4b07-4698-98c4-51aa1914e576)

### Result:
Thus a Half Adder and Full Adder is designed and its truthtables are verified in Quartus using Verilog programming.
