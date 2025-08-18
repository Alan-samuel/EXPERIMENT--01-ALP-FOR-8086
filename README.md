# EXPERIMENT--01-ALP-FOR-8086
Name : Alan Samuel Vedanayagam
<br>
Roll no : 212223040012
<br>
Date of experiment : 18-08-2025




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







# Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

mov ax,0765h;
mov bx,0767h;
add ax,bx;
ret
```

## Output  
<img width="851" height="423" alt="Screenshot 2025-08-18 101747" src="https://github.com/user-attachments/assets/f76d1780-10cd-4b30-8930-4ec80fa22278" />
<img width="1051" height="697" alt="Screenshot 2025-08-18 101811" src="https://github.com/user-attachments/assets/07179e14-95ac-41b5-ae41-c76286d1403a" />

## Subtraction   of 8 bit numbers  ALP 
```
org 100h

mov ax,123;
mov bx,125;
sub ax,bx;

ret
```
## Output  
<img width="850" height="317" alt="Screenshot 2025-08-18 102139" src="https://github.com/user-attachments/assets/82fe885b-bd69-48a8-ab96-a933c332dbb0" />
<img width="1051" height="710" alt="Screenshot 2025-08-18 102203" src="https://github.com/user-attachments/assets/a1f2e18b-7945-48a6-b2b5-cf47e9942e83" />

## Multiplication alp 
```
org 100h

mov ax,[0070h];
mov bx,[0072h];
mul bx
ret
```
 ## Output  
<img width="852" height="472" alt="Screenshot 2025-08-18 100307" src="https://github.com/user-attachments/assets/1ae397cc-7da1-4d4f-8476-2961b88fa27d" />
<img width="1665" height="735" alt="Screenshot 2025-08-18 100339" src="https://github.com/user-attachments/assets/cf5e4c8a-4fed-4ff7-bd9c-af43ba528fcb" />


## Division alp 
```
org 100h


mov ax,[0077h]
mov bx,[0079h]
div bx


ret
```
## Output  
<img width="837" height="322" alt="Screenshot 2025-08-18 101111" src="https://github.com/user-attachments/assets/30306388-746c-4a3c-a570-42090263a658" />
<img width="1670" height="742" alt="Screenshot 2025-08-18 101139" src="https://github.com/user-attachments/assets/7a0d7099-0b79-4499-a00b-2c2d770e597a" />


## Result :
 
Thus, we have have written and executed alp on fundamental arithmetic (add,sub,mul,div) and logical operations (and,or,not,xor) successfully







