---
layout: project
type: project
image: images/BST.png
title: Binary Search Tree
permalink: projects/bst
# All dates must be YYYY-MM-DD format!
date: 2018-11-09
labels:
  - Java
  - Binary Search Tree
  - In Order Traversal 
summary: An ICS 211 assigment that helped us learn about binary search trees and the different ways to traverse them. We had to create a binary search tree of Contacts and have a function traverse the tree in order. 
---

<img alt="example picture of binary search tree" src="../images/BST.png" width="50%">

For this assignment we were given a class, contacts, which had the contact's first name, last name and contact number as strings, and we were given a search tree interface, in order interface and test cases. 
The assignment was to take the search tree and in order interfaces and create a binary search tree class.
The binary search tree was made with functions to add contacts to the tree, delete contacts from the tree, find a contact and a contains function that returned true if a contact was found to be in the tree or false if no contact was found. 
I built a comparator that returned an integer based on the contact’s last name and an integer comparator was made to compare the integers returned from the contact comparator. 
These comparators were used so the contacts could be sorted when added to the binary search tree. 
I implemented an in order function to traverse the binary search tree in order and return a list of all of the contacts in the binary search tree. 

This assignment combined elements from things we learned before in the class and we just needed to apply it to this assignment. 
We had learned the concept of trees and how to build trees earlier, so I had to apply what I learned from building trees before to building a binary search tree. 
I also had to use recursion for most of the binary search tree functions, which we had also learned about and used in previous assignments. 
I ran into some problems with recursion, specifically with the add and delete functions and updating the root node while calling the function recursively. 
This was fixed by creating helper functions that would run recursively instead of the actual add or delete functions. 

Here is my source code for this project: <a href="https://github.com/ioaneomerod/binary-search-tree"><i class="large github icon"></i>Binary Search Tree</a>
