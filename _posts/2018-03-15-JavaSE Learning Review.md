---
layout:     post
title:      JavaSE Learning Review_1
subtitle:   Based on Jenior Java developer interview 
date:       2018-03-15
author:     Alexa
header-img: img/post-bg-note1.jpg
catalog: true
tags:
    - Java
    - JAVASE
    - JDK
    - oop
---

## Preview

Becuase of preparing the tech interview for my first job, I have to start review all points which might be asked. Firstly , JavaSE is the basic part of (java)web application development, thus I tend to go through the whole points at the beginning...

## Java Terms

**JVM vs JRE vs JDK** 

>JVM is the virtual machine that runs on computers and executes Java byte code. The JVM doesn’t understand Java source code, that’s why we need to have `javac` compiler that compiles `.java` files to obtain `.class` files that contain the byte codes understood by the JVM. _JVM makes java portable (write once, run anywhere)_. 

![](https://beginnersbook.com/wp-content/uploads/2013/05/JVM.jpg)
* Java Virtual Machine : It’s an abstract machine . It is a specification that provides run-time environment in which java byte code can be executed. _The primary function of JVM is to execute the byte code produced by compiler_.
* Java Runtime Environment: it refers to a runtime environment in which java byte code can be executed. It implements the JVM and provides all the class libraries and other support files that JVM uses at runtime._When you have JRE installed on your system, you can run a java program however you won’t be able to compile it.When you only need to run a java program on your computer,  you would only need JRE_. 
* Java Development Kit : It is the tool necessary to compile ,document and package Java programs. The JDK completely includes JRE which contains tools for Java programmers.The Java Development Kit is provided free of charge. Along with JRE, it includes an interpreter/loader, a compiler `javac`, an archiver `jar`, a documentation generator `javadoc` and other tools needed in Java development. In short, it contains JRE + development tools.

**[WHY JAVA AS PLATEFORM INDEPENDENT LANGUAGE]**
* `javac`Compiler converts source code `.java file`to the byte code`.class file`.As mention above , JVM executes the bytecode produced by compiler. This btyecode can run on any plateform(Windows,Linux, Mac OS etc). 
* Each operating system has different JVM, however the output they produce after execution of byte code is same across all operating system.

**[EXPLIAN JAVA IS AN OBJECT ORIENTED LANGUAGE]**
`Object Oriented Programming`is a way of organizing programs as collection of objects, each of which represents an instance of a class.
- Abstraction 
- Encapsulation
- Inheritance
- Polymorphism

>Q:Why java is not 100% Object-oriented?
**Java is not 100% Object-oriented because it makes use of eight primitive datatypes such as boolean, byte, char, int, float, double, long, short which are not objects**.

## Pros of Java 
* [Simple](#){:target="_blank"} 
* [Robust Language](#){:target="_blank"} 
* [multithreading](#){:target="_blank"}
* [Secure](#){:target="_blank"} 
* [Distributed](#){:target="_blank"} 
* [Portable](#){:target="_blank"} 

## Tips of Basic Part
1.Primary Data Type:Java supports eight primitive data types: `byte`` short``int`` long``float``double``char``boolean`.
>>The output of the relational operator is (true/false) boolean value, and in Java, true or false is a non-numeric value that is not related to zero or one.
2.Java string compare different case(uppercase & lowercase)
>>Rules of Declaring variables in Java:
* A variable name can consist of Capital letters A-Z, lowercase letters a-z, digits 0-9, and two special characters such as underscore and dollar Sign.
* The first character must be a letter.
* Blank spaces cannot be used in variable names.
* Java keywords cannot be used as variable names.
* Variable names are case-sensitive.
  

<p style="color:gray;font-size:10px">reference from:<a href="https://beginnersbook.com/2013/05/java-introduction">beginnersbook.com<a>


