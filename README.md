
## EX.NO:4
## DATE :

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

![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/778429a1-70c2-44e1-b455-5dd8b4961fe8)


**Figure -1 FULL ADDER**

**Procedure**

1.Open Quartus II and create a new project.    
2.Use schematic design entry to draw the full adder circuit.      
3.The circuit consists of XOR, AND, and OR gates.       
4.Compile the design, verify its functionality through simulation.      
5.Implement the design on the target device and program it.     


**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/e629b0cf-1dc2-44c9-b0ba-2e698f2fa5fe)


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin


**Procedure**

1.Open Quartus II and create a new project.   
2.Use schematic design entry to draw the full adder circuit.      
3.The circuit consists of XOR, AND, and OR gates.       
4.Compile the design, verify its functionality through simulation.      
5.Implement the design on the target device and program it.     

## FULL ADDER

**Program:** 

**Developed by: KARTHIKEYAN P**  
**RegisterNumber:  212223230102** 


![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/bf34f229-957a-47fa-bf6b-62183f7759a7)


**RTL Schematic**
![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/dc07904f-f9ed-4828-8d6c-d95083534e86)


**Truth Table**

![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/902874e1-c53e-4177-984c-8e0c915c0e18)


**Output Timing Waveform**
![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/3003fe09-0bf6-4034-8e04-60b50adc774f)

## FULL SUBTRACTOR

**Program:**

![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/bb5bd9d3-543b-475f-897f-56802e0921b6)


**RTL schematic**

![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/273af991-dd7a-4ac7-93d0-27796fc22fc4)


**truth Table**

![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/7d3da4ab-438b-479d-9df6-4e9617550fab)


**Output Timing Waveform**
![image](https://github.com/karthikeyanpachiyappan/FULL_ADDER_SUBTRACTOR/assets/155143878/02613998-1f61-4a12-a9cb-68a0beba4cb7)



**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.
