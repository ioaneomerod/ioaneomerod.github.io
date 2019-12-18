---
layout: project
type: project
image: images/Records.jpg
title: Records 
permalink: projects/records
# All dates must be YYYY-MM-DD format!
date: 2019-04-13
labels:
  - C++
  - Source Code Control System
  - Makefile
  - Bash Scripts
summary: My final project for ICS 212 that acted as a database of records that could be manipulated by a user with specific commands.
---

<p>
    Our final project for ICS 211 that simulates a record database that can be changed based on user input. 
    The database is a linked list of record structures. 
    The user can add a new record by giving the person’s name, address and account number. 
    The user can also delete a record from the database using the record’s account number. 
    The user can look up a name and any name in the database that matches the name given by the user will be printed. 
    The user can print a record using the record’s account number and print all records in the database. 
    The user can also reverse the order of the database and print out the changed database. 
    When a user exits the user interface the database is saved so it can be reloaded the next time a user uses the program.
</p>

<p>
    Here is the compilation and linkage of the project and a sample output:
    <img class="sample output of records project" src="{{ site.baseurl }}/images/records-output.png">
</p>

<p>
    This project was a culmination of various things learned through out the semester. 
    A lot of class assignments required us to  create simple, text based user interfaces and handle incorrect input from a user. 
    We had to create structures in C and C++ and classes in C++, which was needed when we worked with the linked list class and record structure in this project. 
    SCCS was used as version control in previous assignements and we had to use again in this project. 
    A makefile had to be used to compile the files in this project, and a bash script had to be made that would check our files out of SCCS to be compiled and run. 
</p>

<p>
    Here is the source code for my project: <a href="https://github.com/ioaneomerod/records-project"><i class="large github icon "></i>Records</a>
</p>
