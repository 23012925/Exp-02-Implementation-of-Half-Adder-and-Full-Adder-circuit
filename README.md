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
Developed by: JANARTHANAN K 
RegisterNumber: 23012925  
*/
Logic symbol & Truthtable
RTL realization

# Code

                                                                      ### HALF ADDER: 
                                                                         
![program](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/f7010711-b569-4d21-9cf6-bd27b955e7b0)

                                                                      ### FULL ADDER:

![program](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/2738a3cb-6587-4985-b7e8-d86977420e0a)
                                                                         

# RTL

                                                                      ### HALF ADDER: 

![RTL viewer](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/f31387b2-98aa-421b-b447-d2d2d3752b6f)
                                                                         
                                                                      ### FULL ADDER:

![RTL viewer](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/e1597298-7fbe-4d2b-a48d-4986334dbd1c)

                                                                         

# TIMING DIAGRAM

                                                                      ### HALF ADDER: 

 ![Timing diagram](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/4fe78122-ddc8-4b30-993d-49d28008e75f)
                                                                        
                                                                      ### FULL ADDER:

 ![Timing diagram](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/9650ffa1-9081-4087-ba70-0a400ccc1510)


# TRUTH TABLE   

                                                                      ### HALF ADDER: 

![truth table](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/d8f0276b-8766-4740-b3d5-6c271731bb48)

                                                                      ### FULL ADDER:

![truth table](https://github.com/23012925/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150931013/b1cba94c-bd6e-4e07-9250-3b86e15855cc)


### Result:  
           Thus, the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
