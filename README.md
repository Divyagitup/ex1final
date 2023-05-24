# Implementation of Logic Gates using Verilog HDL
## Aim
To implement and to verify the truth table in Verilog HDL for the following logic gates 
1.	AND gate
2.	 OR gate
3.	 NOT gate 
4.	 NAND gate
5.	 NOR gate
6.	 Ex-OR gate
7.	 Ex-NOR gates 

## Components Required:
1.	Laptop with Quartus software and modelsim software

## Theory
## Introduction
Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. 


1) AND gate
The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
	Y= A.B
![image](https://github.com/rvinifa/ex1final/assets/133735746/0b3bb617-91e2-48cb-b076-0ee1a72e0479)

  





2) OR gate
The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.

  Y= A+B

![image](https://github.com/rvinifa/ex1final/assets/133735746/68debf78-a4f1-47a5-9dba-0220a8c3f537)
 




3) NOT gate

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.

Y= A'
![image](https://github.com/rvinifa/ex1final/assets/133735746/bfb047a9-0077-4164-bd7d-3972a1b5f997)


 




4) NAND gate
This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.

Y= (AB)’
![image](https://github.com/rvinifa/ex1final/assets/133735746/f103398b-56bf-43d0-a454-c611aa79ce1e)



 



5) NOR gate

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.


Logic Symbol							Truth Table
Y= (A+B)’

 ![image](https://github.com/rvinifa/ex1final/assets/133735746/22a03cab-dc44-4a49-a293-b03dfd4b586e)





6) Ex-OR gate

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.


Logic Symbol							Truth Table
Y= A⊕B
![image](https://github.com/rvinifa/ex1final/assets/133735746/cf18ea9e-7d95-4416-bd1d-350141b010c2)

 











7) Ex-NOR gate

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.


Logic Symbol						Truth Table
Y= A⊕B

![image](https://github.com/rvinifa/ex1final/assets/133735746/f5fc7782-e4a7-47d1-b596-394835324213)
 






## Procedure:
1.	Type the program in Quartus software.
2.	Compile and run the program.
3.	Generate the RTL schematic and save the logic diagram.
4.	Create nodes for inputs and outputs to generate the timing diagram.
5.	For different input combinations, generate the timing diagram.

## Program:
module exp1(a,b,o1,o2,o3,o4,o5,o6,o7);
input a,b;
output o1,o2,o3,o4,o5,o6,o7;
and(o1,a,b);
or(o2,a,b);
xor(o3,a,b);
nand(o4,a,b);
nor(o5,a,b);
not(o7,a);
endmodule 

## RTL Schematic
<img width="917" alt="exp1 dia" src="https://github.com/Divyagitup/ex1final/assets/134514564/d9d52994-e7de-4c2a-88f2-de0a8142b0cf">

## Timing Diagram:

<img width="960" alt="exp1 out" src="https://github.com/Divyagitup/ex1final/assets/134514564/b98cc534-1e25-4d47-b21c-1d296f8485b1">



## Result:

Thus the different logic gates are implemented in Verilog HDL and the truth table are verified.



