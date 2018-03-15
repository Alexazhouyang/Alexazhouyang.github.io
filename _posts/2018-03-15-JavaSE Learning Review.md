---
layout:     post
title:      JavaSE Learning Review 
subtitle:   Based on Jenior Java developer interview 
date:       2018-03-15
author:     Alexa
header-img: img/post-bg-note1.jpg
catalog: true
tags:
    - Java
    - JAVASE
    - JDK
---

## Preview

Becuase of preparing the tech interview for my first job, I have to start review all points which might be asked. Firstly , JavaSE is the basic part of (java)web application development, thus I tend to go through the whole points at the beginning...

## Content | Basic Part

### Java terms: JVM , JRE, JDK

JDK includes JRE includes JVM
* Java Virtual Machine : It’s an abstract machine . It is a specification that provides run-time environment in which java byte code can be executed. `The primary function of JVM is to execute the byte code produced by compiler `.
* Java Runtime Environment: it refers to a runtime environment in which java byte code can be executed. It implements the JVM and provides all the class libraries and other support files that JVM uses at runtime.`When you have JRE installed on your system, you can run a java program however you won’t be able to compile it.When you only need to run a java program on your computer,  you would only need JRE `. 
* Java Development Kit : It is the tool necessary to compile ,document and package Java programs. The JDK completely includes JRE which contains tools for Java programmers.The Java Development Kit is provided free of charge. Along with JRE, it includes an interpreter/loader, a compiler (javac), an archiver (jar), a documentation generator (javadoc) and other tools needed in Java development. In short, it contains JRE + development tools.

**[WHY JAVA AS PLATEFORM INDEPENDENT LANGUAGE]**
* Each operating system has different JVM, however the output they produce after execution of byte code is same across all operating system.
