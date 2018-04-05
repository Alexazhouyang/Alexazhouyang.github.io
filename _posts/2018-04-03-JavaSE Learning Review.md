---
layout:     post
title:      JavaSE Learning Review_3
subtitle:   heap space vs stack - Memory
date:       2018-04-03
author:     Alexa
header-img: img/post-bg-note1.jpg
catalog: true
tags:
    - Java
    - Memory
---
> There are three different spaces be used in java: PermGen space(permanent generation space)、heap space、stack space;

## what is permgen space?
As for the name is permanent generation space, the memory is mostly used to store Class and Meta data in JVM. When Class is loadered , it would be put in permgen space. Thus if you apply too much Class, it might generate PerGen space error when web server pre compile with JSP.Meanwhile, based on web application with too much jar files, the error might be showed because of oversize of JVM(default:4M)

## what is heap apace?
Java heap space is used by java untime to allocate memory toO bjects and JRE classes.Whenever we creat any object ,it's always created in the heap space.
Garbage Collection runs on the heap memory to free the memory used by object that doesn't have any reference. Any object created in the heap space has global access and can be referenced from anywhere of the application.
