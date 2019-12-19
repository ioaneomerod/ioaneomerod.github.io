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

<img alt="picture of record stack" src="../images/Records.jpg">

The final project for my ICS 211 class simulates a record database that can be changed based on user input. 
The database is a linked list of record structures. 
A user can add, delete and print information about the records.
A user can add a new record by giving the person’s name, address and account number. 
A user can also delete a record from the database using the record’s account number. 
A user can look up a name and any name in the database that matches the name given by the user will be printed. 
A user can print a record using the record’s account number and print all records in the database. 
A user can also reverse the order of the database and print out the changed database. 
When a user exits the program, the database is saved so any changes made to the database can be reloaded the next time the user uses the program.

Here is the compilation and linkage of the project and a sample output:
```
uhx02:/home/i/ioane808/Project1% make project2
g++ -ansi -pedantic-errors -Wall -c llist.cpp
g++ -ansi -pedantic-errors -Wall -c menuoptions.cpp
g++ -ansi -pedantic-errors -Wall -c main.cpp
g++ -o project2 main.o menuoptions.o llist.o
uhx02:/home/i/ioane808/Project1% ./project2
Select a task to be done by typing the number 
corresponding to the option.
1. Add a new record in the database.
2. Print information about a record using the accountno.
3. Print all information in database.
4. Print records whose name starts with:
5. Delete existing record using accountno.
6. Reverse the order of the database and print it.
7. Exit.
Enter an option: 1
Enter accountno: 12345
Insert name: John Doe
Type your address and type a ; at the end
when you are finished.
Insert address: 1213 Doe Street
Honolulu, HI
96818;
Record added successfully.
Select a task to be done by typing the number 
corresponding to the option.
1. Add a new record in the database.
2. Print information about a record using the accountno.
3. Print all information in database.
4. Print records whose name starts with:
5. Delete existing record using accountno.
6. Reverse the order of the database and print it.
7. Exit.
Enter an option: 7
```
This project was a culmination of various things learned through out the semester. 
A lot of class assignments required us to  create simple, text based user interfaces and handle incorrect input from a user, which was used to ensure the user input was what I expected and did not contain anything that could break my program. 
We had to create structures and classes in C and C++, which was needed to create the linked list class and record structure that made up this project's database. 
SCCS, Source Code Control System, was used for version control, so we could access older versions of our code in previous assignments. 
We learned how to create a Makefile to compile and link our files into an executable program with only one command.
For this final project, not only did we have to use SCCS and a Makefile, but we also had to create a bash script named getrelease that would get all of the files necessary to run the project from SCCS in a single command.

Here is the source code for my project: <a href="https://github.com/ioaneomerod/records-project"><i class="large github icon "></i>Records</a>
