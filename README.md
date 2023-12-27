# Implementation of Half adder and Full adder circuit using verilog HDL
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
Developed by: RAGUL RAAJAN T
RegisterNumber:23007752  
*/
Logic symbol & Truthtable
RTL realization

# CODE:
 ### HALF ADDER:
![Screenshot 2023-12-23 052818](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/2527e78b-0df8-4699-90a3-d06aebd6791b)
 ### FULL ADDER:
 ![Screenshot 2023-12-27 102618](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/36689b1b-5686-4462-a1d9-ab93d328b0a6)

# RTL
 ### HALF ADDER:
![Screenshot 2023-12-27 102632](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/8f9fc27a-8632-41bf-a809-aa5ca9977cb9)

 ### FULL ADDER:

![Screenshot 2023-12-27 102642](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/7675d7dd-d09c-4ebc-bc84-93873b589b23)

# TIMING DIAGRAM
### HALF ADDER:
![Screenshot 2023-12-27 102700](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/aea4f86a-6eea-442c-8010-6acb8ed5faf6)

### FULL ADDER:
![Screenshot 2023-12-27 102711](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/be5e94ff-7acb-49f6-bfd5-6287efdfb308)
 
# TRUTH TABLE 
### HALF ADDER:
![Screenshot 2023-12-23 053331](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/c683c93a-01a4-430f-85a7-8c0eb4036fd1)

### FULL ADDER:
![Screenshot 2023-12-27 102721](https://github.com/RAGULRAAJAN/DE.EXP.03/assets/147473144/a87f410d-2042-417e-81ff-927a9f77edb3)

### Result:
Thus the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
