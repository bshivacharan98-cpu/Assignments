AI Programs in Python

This repository contains a few basic Artificial Intelligence programs written in Python. The aim of these programs is to understand simple AI concepts such as human–machine interaction and search algorithms.

The programs included are:

Simple Chatbot based on the Turing Test concept
CAPTCHA Verification System
BFS and DFS implementation for the Missionaries and Cannibals problem

1. Turing Test Idea
   
Description
This program is a basic chatbot that interacts with the user through the console. It responds to simple keywords entered by the user.

Features
Console based chatbot
Responds to words like hello, hi, name, weather
Runs until the user types exit

Example
Ask something: hello
AI: Hello! Nice to talk with you.

Ask something: exit
AI: Goodbye!



2. CAPTCHA Verification System
   
Description
This program generates a random CAPTCHA and asks the user to enter it correctly. It helps check whether the user is human.

Features
Generates a random 5-character CAPTCHA
Uses letters and numbers
Allows 3 attempts

Example
Generated CAPTCHA: A7K2P
Enter the CAPTCHA: A7K2P

Access Granted!



3. Missionaries and Cannibals Problem (BFS and DFS)
   
Description
This program solves the Missionaries and Cannibals problem using Breadth First Search (BFS) and Depth First Search (DFS).

Problem
3 missionaries and 3 cannibals must cross a river
Boat can carry maximum 2 people
Cannibals should never be more than missionaries on either side

State Representation
Each state is written as:
(m, c, boat)
Where
m = missionaries on left side
c = cannibals on left side
boat = boat position
1 → left side
0 → right side


Output
The program prints:
Solution path using BFS
Number of nodes explored by BFS and DFS


Example:
Missionaries and Cannibals Problem

BFS Solution Path:
(3,3,1) → (3,1,0) ...

Nodes explored by BFS: 20
Nodes explored by DFS: 32
