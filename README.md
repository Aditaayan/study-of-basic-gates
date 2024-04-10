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




**AND GATE**



**PROGRAM**

![321155193-ea8256d6-9793-43aa-9599-8edb471afa27](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/42721fa4-25cf-479c-ac62-c46eb4848116)


Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by:aditaayan.m RegisterNumber: 212223040006
 
**Logic symbol & Truthtable**

![319458613-e333ab21-f7bf-4aa0-8a6b-f69c57451122](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/6c88473a-812c-49c7-aa4e-b4d96a3f01df)

**RTL realization Output:** 

![314435924-ff9b3046-63ed-449d-bba6-e1a0cff0279b](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/8e2b2737-5e06-4e52-ba2a-95ad34f4cf6e)


**RTL**

![314435835-e6d8cd84-a6f9-494a-8dbe-14f5232a24b1](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/a2039c34-158a-44a6-ad99-01382c1391c2)

**OR GATE**

**PROGRAM**

![321155726-ddeb460c-e5f3-45b6-a115-169e4397563c](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/bcc41892-f1a4-4532-9b2e-bb97dd065d6b)

**Logic symbol & Truthtable**

![319458650-7c6f142b-46a3-4e36-a4c7-76008d1b9832](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/bdbc2626-a8c5-403e-a780-fe9c45ecd620)

**RTL realization Output:** 

![319249934-e4c2528d-b615-49a1-8c0d-eae421b8adcc](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/eef07ad4-b607-4661-88f6-28bc5b457d99)

**RTL**

![319253722-18e815c2-415d-48a5-881e-a4073c55509d](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/ee471bb5-ea2d-41f7-95fc-391d8fd17738)

**NOT GATE**

**PROGRAM**

![321155801-1cad371c-4463-4d9d-a033-bdad05e1b6d1](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/c3b3f3d5-0993-4668-8e53-a7407a559d6e)

**Logic symbol & Truthtable**

![319459057-19d8cb59-7eab-4f7b-a45d-296947b83146](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/9ff3c934-4ee1-4612-b3fd-085030bc9d5d)

**RTL realization Output:** 

![319255215-91e6f5d3-07b5-4f9e-8304-e633aa560a0a](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/004354e0-69b2-45fb-bbc1-49b3ccfc5dd3)

**RTL**

![319255162-b113887a-9711-4cc6-a370-65011076d102](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/baf715c8-daf9-4ebc-bea2-a27746521e53)


**NAND GATE**

**PROGRAM**

![321155891-d24d2a06-0780-4e5d-8f4f-5cd5825b96a0](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/7542227e-3fea-4e85-942a-3041c16fc056)

**Logic symbol & Truthtable**

![319458770-a0137613-8911-48f3-b17b-8f2829320975](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/34d57c74-af7c-47e9-aeaf-c85d37ad8973)

**RTL realization Output:** 

![319257953-cd6af132-c459-4b8d-ae94-7acece134f68](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/1aea652d-aa6c-4cab-8f76-13f325b44ea5)

**RTL**

![319257880-4af553bd-b913-4db8-a3ec-089a9482ad06](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/413f6513-be24-4a82-89dd-9ea38c807fdb)

**NOR GATE**

**PROGRAM**

![321157180-bbc077de-ee0e-446b-a62e-7117b5221b51](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/2b587732-18ca-4096-b7b5-8fc08c11a05b)

**Logic symbol & Truthtable**

![319458802-eb93295d-0d69-4b8f-bedd-99ec4f99c4aa](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/96c33b8b-7701-44cb-8d55-03ad19bc7192)

**RTL realization Output:** 

![319259741-cdfb5e64-a652-4bf0-89d8-1d07528a4a42](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/5500839e-e01f-4fdd-ad9f-f49f8c659298)


**RTL**


![319259667-7cfffafe-e298-41f7-9563-46a1f94f5972](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/f7c56117-2266-4207-aba8-71542604109e)

**EX-OR GATE**

**PROGRAM**


![321156830-d286b753-55ac-4244-a3bd-9b43f11fab22](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/6554cf7b-2e19-454d-a622-4b8bf1df1d62)

**Logic symbol & Truthtable**


![319458857-dfcd8129-dc9c-47bf-9dc1-8d34142f0f81](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/95c84c59-a361-4562-a1d0-9e5b263e89e3)

**RTL realization Output:** 


![319262492-dbf2c102-470c-4de1-93f4-68449fe7390e](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/29e12ee5-77c5-4a2e-ae85-832101244566)

**RTL**


![319262447-d473eed3-f79f-48cf-a817-df2ec6c0eec2](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/d42bf2c7-949f-4bfc-8b55-d550c35ba9a0)

**EX-NOR GATE**

**PROGRAM**


![321156597-395f90c6-e3da-451d-baa9-93e89af26ad9](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/d6d5e59c-986c-42b6-825d-23ea10901a12)

**Logic symbol & Truthtable**


![319458896-ed25b34e-8a78-4fd1-9b9b-86894a498f7d](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/79461902-ef69-4411-9670-934c2458e24e)

**RTL realization Output:** 


![319457505-b87a09f9-a913-4428-bcb4-8a1d92176656](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/4c5684be-49b0-4a08-879b-2947c035d572)

**RTL**


![319266755-0a08d115-8fe8-4943-b322-66f16da0ec08](https://github.com/Aditaayan/study-of-basic-gates/assets/147473394/3dab2c2a-f7cf-4a6e-b086-8f490fc88c52)

**Result:**
Thus,truth table of logic gates in Quartus II using Verilog programming is executed successfully and verified

