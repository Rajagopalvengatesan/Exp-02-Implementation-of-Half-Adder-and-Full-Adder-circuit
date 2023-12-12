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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Rajagopal V
RegisterNumber:23002920
*/
Logic symbol & Truthtable
RTL realization
### code 

### Half Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/1ee45e90-bae1-4490-b1b7-211405ca8728)

### Full Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/7eca0546-924b-4035-badd-20b7cd488ff6)

### Truth Table 

### Half Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/06513673-2737-4432-b81e-c9ca113c153d)

### Full Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/ea359dae-6b33-44bc-a0f0-65795f4cf7bb)

### RTL 
### Half Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/2139841d-c849-4d8b-9fff-eef1c2a0ee99)

### Full Adder 
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/0a643aaf-ab33-43a3-a0f5-038f2fe7fe63)

### Timing Diagram
### Half Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/6a7d7cd6-b4b6-410b-af59-bd27ce492d90)

### Full Adder
![image](https://github.com/Rajagopalvengatesan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/144870784/6279b334-61ea-4241-bcda-a2c68464ba28)




### Output:
### RTL
### TIMING DIAGRAM


### TRUTH TABLE 

### Result:
