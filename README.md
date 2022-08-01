# JavaPrograms
This repo consists of some of the basic java programs which i have done as part of my learning. 

## Features of Java (Java Buzzwords) :- 
 1) Object oriented 
 2) Simple 
 3) Secured 
 4) Platform Independent 
 5) Robust 
 6) Portable 
 7) Architecture Neutral 
 8) Dynamic 
 9) Interpreted 
 10) High Performance 
 11) Multithreaded 
 12) Distributed 

## Execution of a java program.
 To understand the execution of a java program. We need to be familiar with three words.
 
 ### Source Code 
     It is the code developed by the programmer.
  
 ### Object Code 
     It is the program which can be interpreted by the system.
     It contains 0's and 1's.
     It is obtained by compiling the source code.

 ### Byte Code 
     Byte code is the speciality of java.After the code is compiled a byte code is generated and it does not have any     relationship with the system.

Unlike other languages java doesn't convert its source to object code directly.
When we try to execute our code. The java interpreter converts the byte code into object code.


![image](https://user-images.githubusercontent.com/99969931/182023976-a7625bf1-d952-4408-bf3a-3341da768d8b.png)


In this way a java program works similar in different operating systems.
Anyways, All the system dependencies will be taken care by the JVM(Java Virtual Machine).

## JVM, JRE, JDK

These three are platform independent, with the help ot these three a java program becomes platform independent.

### JVM(Java Virtual Machine)

As the name suggets, it doesn't exist physically.
JVM executes the byte code.

### JRE(Java Runtime Environment)

It consists of JVM as well as all the libraries required for the program to execute.

![image](https://user-images.githubusercontent.com/99969931/182081772-760a9d3f-ee1b-4d42-99de-4d965a1e43a6.png)


### JDK(Java Development Kit)

In a nutshell,

     JVM + JRE = JDK
     
  ![image](https://user-images.githubusercontent.com/99969931/182082358-af467ceb-01a5-4fe7-9c84-70ef20080d90.png)

A JDK provides all the tools required for java development.

## Data types & Variables in java.

### Variable.

A variable is not just a value.
Variable is a memory location of a data type.

### Data types.

1) numeric to perform arithmetic operations.
2) boolean to perform conditions.
3) string for alpha-numeric.
4) array to store more than one value.

In this way each data type has its own significance.

![image](https://user-images.githubusercontent.com/99969931/182083801-03678968-b5c0-45bd-b51a-6f87c5f37750.png)

Choosing a correct data type for a variable is very essential. If not assigned properly it may lead to errors and memory wastage.

Each data type has a size and its own purpose.

For ex :- 
    
    We use integer to store numbers, If the number we want to store is huge we use 'long' before int. Using this the compiler assigns more space to that variable.
    
    We can use 'float' or 'double' for storing decimal numbers like 20.556, 45.675.
    float is of size 4 bytes.
    double is of size 8 bytes.
    
    boolean stores only two values. i.e; 'true', 'false'.
    
    Arrays are used to store multiple values at a time.
    
    To read only a single character we can use 'char'.
    
    If we want to store multiple characters we can use 'String'.
    
