---
layout: project
type: project
image: images/jni.png
title: Java Native Interface
permalink: projects/jni
# All dates must be YYYY-MM-DD format!
date: 2019-04-26
labels:
  - Java Native Interface
  - Java
  - C
summary: To learn about Java Native Interface in my ICS 212 class, we were tasked with splitting a program into Java and C or C++ code and then compiling and running the code with Java Native Interface. 
---

In this homework for ICS 211 we were given a function:
<br>
<br>f(x) = x^2 for x < 5
<br>f(x) = x^2 - 3x - 10 for 5 <= x < 10
<br>f(x) = x^2 - 7x - 8 for 10 <= x.
<br>
<br>
We were tasked with getting an user inputted integer and printing out a table of x and f(x) values that would start at x = 0 and increment by 0.5 until the table reached the user inputted integer. 
The user interface code and code to print the values of x and f(x) as a table were done in Java. 
While the code to find the f(x) values based on the user inputted integer was done in C. 
The main point of the project was to use Java Native Interface to compile and execute code that is in both Java and C or C++.

Here is a sample of the code's output and how I compiled and executed the code: 
    ```
    uhx02:/home/i/ioane808/Homework9% make hw9
    javac hw9.java
    javah hw9
    gcc -ansi -pedantic-errors -Wall -I/usr/java/jdk1.8.0_131/include -I/usr/java/jdk1.8.0_131/include/linux -shared hw9.c -fPIC -o libhw9.so
    java -Djava.library.path=. hw9
    This program will print a table of x
    and f(x) for x from 0 to the user
    inputted integer with f(x) being
    equal to:
    x^2 for x < 5
    x^2 - 3x - 10 for 5 <= x < 10
    x^2 - 7x - 8 for 10 <= x.
    Enter number of x: 3
        x        y
        0.00     0.00
        0.50     0.25
        1.00     1.00
        1.50     2.25
        2.00     4.00
        2.50     6.25
    ```
    
The two hardest parts about this assignment were trying to switch between writing Java and C code and getting everything to compile and execute. 
Trying to debug and switch between Java and C while coding was a challenge as I had never worked on multiple languages at the same time before, but it’s something I found valuable to be able to switch from one language to another. 
Getting the files to compile together was also the biggest challenge as I was having trouble including a path for the code to run.

Here is the source code for my project: <a href="https://github.com/ioaneomerod/java-native-interface"><i class="large github icon "></i>Java Native Interface</a>
