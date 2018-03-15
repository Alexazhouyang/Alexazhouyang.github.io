---
layout:     post
title:      JavaSE Learning Review(1)
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

## Basic Part

**Java terms: JVM , JRE, JDK** JDK includes JRE includes JVM
* Java Virtual Machine : It’s an abstract machine . It is a specification that provides run-time environment in which java byte code can be executed. `The primary function of JVM is to execute the byte code produced by compiler `.
* Java Runtime Environment: it refers to a runtime environment in which java byte code can be executed. It implements the JVM and provides all the class libraries and other support files that JVM uses at runtime.`When you have JRE installed on your system, you can run a java program however you won’t be able to compile it.When you only need to run a java program on your computer,  you would only need JRE `. 
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
* [Secure](#){:target="_blank"} 
* [Java is distribute](#){:target="_blank"} 
* [Portable](#){:target="_blank"} 


<p style="color:gray;font-size:10px">reference from:<a href="https://beginnersbook.com/2013/05/java-introduction">beginnersbook.com<a>


