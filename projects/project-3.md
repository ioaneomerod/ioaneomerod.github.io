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
summary: "My final project for ICS 212 that would allow a user to manipulate a database of records with the commands: add a record, delete a record, find and print a record using the user's account number or name and printing the whole record database."
---

<img class="ui image" src="{{ site.baseurl }}/images/cotton-header.png">

Our final project for ICS 211 that simulates a record database that can be changed based on user input. The database would be a linked list of record structures. The user can add a new record that includes the person’s name, address and account number. The user can also delete a record from the database using the record’s account number. The user can find and print a record using the name associated with the record. The user can print a record using the record’s account number. When a user exits the user interface the database is saved so it can be reloaded the next time a user uses the program.

This project was a culmination of various things learned through out the semester like using SCCS to save different versions of a file. Writing a bash script to get the different files from SCCS. Writing a Makefile to compile all of the code and create an executable. And manipulating a linked list with different functions. 

To give you a flavor of the game, here is an excerpt from one run:

<hr>

<pre>
You open your eyes, and you are greeted by an unfamiliar ceiling.
Startled, you get to your feet and quickly scan your surroundings. It's
dark except for the stream of light coming from a crack on the only boarded
window in the room. You try to peek through the crack, but you cannot see
anything. You wonder where you are and who could have possibly brought you here.

<--------------------help------------------------>
Enter quit or one of the following commands -
Weld light look walk pickup inventory help h ?
<------------------------------------------------>

look
The room is a picture of decay with only a faded number identifying it as room-4. The bed you were
 lying on is stained with what looks like dried blood. Could it be your blood? No - it is not. The
 only way out of the room aside from the door to the corridor is a window that is boarded shut. It
 looks like it has been like that for decades. There is a door going west from here. You see a candle
 on the floor. You see a match on the floor.

pickup candle
- you are now carrying the candle -

pickup match
- you are now carrying the match -

light match candle

The candle is now lit. It illuminates everything in the room.

walk west
The corridor is lit with the candle. It is so long that you cannot see to the end. You notice that
 there are words written on the wall. There is a door going east from here. There is a way going north
 from here. There is a door going south from here.
</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

