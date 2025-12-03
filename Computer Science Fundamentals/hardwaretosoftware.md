Hardware to Software, Low to High-level languages
Writer: Tegster
Tegster
Apr 28, 2021
3 min read

Updated: Dec 20, 2022

Table of Contents:

1. Hardware 

2. Hardware to Software

		Hardware and Machine Language 

3. Low Level Language 

4. Middle Level Language 

5. High Level Language 



In this article, we will talk about how the computer essentially works on a high level and how all the components are integrated to build and a PC (Personal Computer), written by yours truly. We will cover only the  high level topics to get an understanding of everything works and fits, slowly building towards where Python fits and lives on the computer.


A computer is simply a device that provides compute, which is just a general term to describe the computational success of a set of instructions carried out by the processor using its resources. The first computer was really the calculator providing the compute or calculate numbers.



Hardware
ree

Components of a personal computer

Power Supply

Provides power for the internal components of a computer.

Mother Board

Motherboard is chief support that ties the all of the computer's components together at one spot and allows them to talk to each other.

RAM

Temporary computer storage that allows stored data to be received and read almost instantaneously. 

Is completely cleared when computer is shut down

CPU

Once all the components are integrated in to the Motherboard and the operating system is able communicate with all the components through their programs. 

CPU execute programs that are coded in machine language and stored in the main memory (RAM) of the computer. 

It does this by repeating the fetch-and-execute cycle over and over; that is, it repeatedly fetches a machine language instruction from memory and executes it.

Memory/SDD/Hard-Drive

Storage device used in computers.

Operating System is installed and stored on the hard disk, hard disk is a non volatile memory, OS does not lose information when turned off.

Many other components such as monitor, keyboard and else are external interactive components that can be optional, if we don't have the need to interact with a computer.


Hardware to Software
ree


ree


We should have a fair understanding of all the hardware components, and how they integrate with each other and on the motherboard to form a complete computer or a compute resource. 


Hardware and Machine Language


Now we have all the Hardware, 


The only language understood by computers is binary, which is known as machine code

This is because computers are electronic devices that can only tell the difference between the on and off states of an electric circuit. 1 and 0 are used by humans to represent these on/off values. 


Numbers in their binary representation

8: 1000

9: 1001

10: 1010

11: 1011


Instructions for a computer to follow must therefore be written in machine code. 

Low-level languages
Assembly:

Assembly was the first programming language invented, it's comprised of small set of commands words called mnemonics. Examples of mnemonics are “MOV”, “ADD” and “PUSH”.

Computers cannot understand machine code, so the assembly code is converted to machine code by an Assembler. 

ree



An assembler is a program that converts assembly language into machine code.

 



Middle Level Languages

Middle-level languages lies in between the low level and high-level language. 

C language is the middle-level language. 


Operating systems programming as well as application programming is done at the middle-level language.


The middle-level language is an output of any high level programming language, which is known as source code. The source code is written in a high-level language, middle-level language is designed to improve the translated code before it moves down the pipeline to the CPU.


ree


High Level Languages

Now that we have an understanding of how hardware understands Binary Machine Language.

Assembly language and the Assembler translate the Assembly code to machine language. Then we have middle level languages, that will host the Operating System. Which in terms gives us a complete computer or a compute resource. 

 

Now that we have a structure for a computer, and an Operating system that can be distributed to work on compatible machines. We have a universal model we can build on for the masses with portability.


Most programmers write programs in high-level languages such as Java, Python...

High-level languages are portable and can be used on different types of computers.


High-level languages have several advantages as they are easier to:

ree


read and understand

write in a shorter time

debug at the development stage




As the assembler in assembly code translates assembly code to machine code.


C and C++ code is compiled into an executable file 


High level languages also have a compiler to compile the code or they can be an interpreted language as Python is. 


Many of the modern day portable mobile and web applications are written in Python. World's current leader in High Level Language.


References:

https://sites.google.com/a/iharrow.org.uk/compsci/13-hardware-and-software/1-3-7-high-low-level-languages-and-their-translators 

https://www.tutorialandexample.com/middle-level-language/ 