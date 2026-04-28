# EXPERIMENT--01-ALP-FOR-8086
Name :Swetha A

Roll no :212224040343

Date of experiment :24/04/26

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL, 12H
MOV BL, 11H
ADD AL, BL 
```
## Output  
<img width="705" height="429" alt="Screenshot 2026-04-21 215824" src="https://github.com/user-attachments/assets/7e4e6875-916f-40c0-86a9-8dbd8d0bed8a" /> 

## Addition  of 16 bit ALP 
```
MOV AX, 1234H
MOV BX, 1111H
ADD AX, BX 
```
## Output  
<img width="703" height="535" alt="Screenshot 2026-04-21 220104" src="https://github.com/user-attachments/assets/61ad75d1-0e95-41fb-9b28-3b459eea2775" />

## Subtraction   of 8 bit numbers  ALP 
```
MOV AL, 12H
MOV BL, 11H
ADD AL, BL
```

 ## Output  
<img width="695" height="543" alt="Screenshot 2026-04-21 220735" src="https://github.com/user-attachments/assets/658a686b-92f7-4465-b4a8-3cb4ff8018fc" />

## Subtraction   of 16 bit numbers  ALP 
```
MOV AX, 1234H
MOV BX, 1111H
SUB AX, BX  

```

 ## Output  
<img width="698" height="515" alt="Screenshot 2026-04-21 220223" src="https://github.com/user-attachments/assets/1251fdd9-c3de-499a-aa6f-d41a6de02a6b" />


## Multiplication of 8 bit numbers alp 
```
MOV AL, 05H
MOV BL, 04H
MUL BL
```
## Output  
<img width="698" height="538" alt="Screenshot 2026-04-21 220935" src="https://github.com/user-attachments/assets/94b45c4f-d5af-4a0d-93e1-97edf3cb8969" />

## Multiplication of 16 bit numbers alp 
```
MOV AX, 0005H
MOV BX, 0004H
MUL BX

```
## Output  
<img width="702" height="539" alt="Screenshot 2026-04-21 221037" src="https://github.com/user-attachments/assets/dbaaad00-30df-45ab-97e1-859789d321eb" />

## Division of 8 bit numbers alp 

```
MOV AL, 10H
MOV BL, 04H
DIV BL
````

## Output  
<img width="699" height="536" alt="Screenshot 2026-04-21 221204" src="https://github.com/user-attachments/assets/e3dc208c-e445-4ab8-a1b8-12d1ae70457d" />

## Division of 16 bit numbers alp 

```
MOV AX, 0010H
MOV BX, 0004H
DIV BX
````

## Output  
<img width="696" height="538" alt="Screenshot 2026-04-21 221305" src="https://github.com/user-attachments/assets/2eb58b14-c1b3-496e-a750-baafc83c72e6" />

## Result :
 Thus,to Write and execute ALP on fundamental arithmetic and logical operations is executed successfully






