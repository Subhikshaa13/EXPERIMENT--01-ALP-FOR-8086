# EXPERIMENT--01-ALP-FOR-8086
Name :Subhikshaa

Roll no 212222230151

Date of experiment :13.03.2024





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
mov al,24h
mov bl,24h
add al,bl
hlt
```


## Output  
![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/fe490754-c00e-41d6-b4d4-bba2dc2615fe)

 
## Subtraction   of 8 bit numbers  ALP 
```
mov al,24h
mov bl,14h
sub al,bl
hlt
```

 
## Output  
![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/e10406bc-5610-485c-a16e-27a15bfcd2c7)

## Multiplication alp 
```
mov al,10h
mov bl,6h
mul bl
hlt
```
 ## Output  


![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/c606a835-3f89-4a0c-9668-30007762b52c)


## Division alp 
```
mov al,40h
mov bl,2h
div bl
hlt
```
## Output  

![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/91c116bf-cce5-4450-93bd-24d448812472)
### Programs for logical operations
### AND
```
org 100h
mov AL,66h;
mov BL,70h;
AND AL,BL;
HLT
ret
```
### OUTPUT:
![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/b3cfa432-30dd-438b-a879-d17b977ebc43)
### OR:
```
org 100h
mov AL,66h;
mov BL,70h;
OR AL,BL;
HLT
ret
```
### OUTPUT:
![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/32001c5c-eb5e-47d4-b40e-bd32199d46df)
### NOT:
```
org 100h
mov AL,66h;
NOT AL;
HLT;
ret
```
### OUTPUT:
![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/37802034-be66-49d8-b30d-e4b16dfbd422)
### XOR:
```
org 100h
mov AL,66h;
mov BL,70h;
XOR AL,BL;
HLT
ret
```
### OUTPUT:
![image](https://github.com/Subhikshaa13/EXPERIMENT--01-ALP-FOR-8086/assets/118787344/1280045c-f351-4df6-8308-5e495d122528)

## Result :
 Thus, a program is executed on ALP for the fundamental arithmetic and logical operations.








