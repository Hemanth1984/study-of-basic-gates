### study-of-basic-gates

**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: E Hemachandran
 
 RegisterNumber: 212224230093

 ```
module logicgate(f1,f2,f3,f4,f5,f6,f7,a,b);
input a,b;
output f1,f2,f3,f4,f5,f6,f7;
assign f1=a&b;
assign f2=a|b;
assign f3=~a;
assign f4=~f1;
assign f5=~f2;
assign f6=a^b;
assign f7=~(a^b);
endmodule
```
 
**Logic symbol & Truthtable**

<img width="354" height="670" alt="502649927-69735680-7d15-47f2-b032-0ab60198ac5c" src="https://github.com/user-attachments/assets/991dbdf7-d19c-491c-8f5e-72612c0f35d1" />


**RTL realization Output:** 

<img width="1050" height="638" alt="504061722-8dd254cd-c51b-4323-8948-b6102d73dc9f" src="https://github.com/user-attachments/assets/1dfd35c7-5866-495a-a5ab-d5a4ebb91415" />


**RTL**

<img width="1919" height="662" alt="504061625-256adb3f-d637-483c-ba6f-94070961aa19" src="https://github.com/user-attachments/assets/e0ee3ee3-e9a4-44ca-a93a-171d9d3aa432" />




**Result:**

The truth table of logic gates in Quartus II using Verilog programming is verified.

