---
layout: page
title: Programming Projects
permalink: /projects/
---


### *Regio Vinco* Map Editor
[Software Design Description (PDF)](../docs/RigioVincoMapEditorSDD.pdf){:target="_blank"}

*Regio Vinco* is a map-picking game proided by the professor ([demo](https://www.youtube.com/watch?v=HXFr6on4Yug){:target="_blank"}). The *Regio Vinco* Map Editor is a editing software written in Java that can construct maps for the game. The editor use Simple App Framework to perform basic file operations. The editing file and exported map is constructed in JSON format. User can change the background border color, edit subregion information, attach images and music, customize the size and scale of the map.

![screenshot](../images/rvme_sc.png "Regio Vinco Map Editor")
![screenshot](../images/rvme_sc2.png "Regio Vinco Map Editor")

This software is the first "big" project with user interface I have done, and which I learned the whole process of releasing a software, from software design to beta test and review. A document of software requirement is provided by the "customer" (professor). I was able to fully experience the real world bussiness.

<br><br>

### Seawolf Script
A simple "console" parser implemented with PLY (Python Lex-Yacc). Supports if statements, while loops and functions (procedures). An Abstract Syntax Tree is first generated, from tokenized reserved symbols to Nodes, when parsing, then the entire tree is "executed" from the root node. The supported languages performs shallow binding by the global stack. 

Sample executable code:

![screenshot](../images/seawolf_script.jpg "Regio Vinco Map Editor")

<br><br>

### Memory Allocator
This is a Dynamic Memory Allocator for Unix Systems written in C, using fixed-size block allocation with "first fit" algorithm. An explicit free list is used to store all the free blocks in the memory. Supports *malloc()*, *free()* and *realloc()* functions.

<br><br>

### (Bash-like) Unix Shell
A beta version. The basic functions and commands are same as Bash. Also supports additional keyboard shortcuts.

![screenshot](../images/shell_sc.jpg "Custom Shell")

It was the hardest and most time consuming course project I have done. It included a lot of concepts such as multiprocessing, pipes and signal handling. I learned a lot about system level programming from this project.

<br><br>

### Digital Alarm Clock - A Real One!
An LED alarm clock with a USB charger which I made in a Electical Engineering course. Seconds are indicated by the six LED diodes on the bottom in binary.

![screenshot](../images/clock.JPG "Clock")
![screenshot](../images/clock_usb.JPG "USB port")

Circuit board was provided. I did soldering, coding and testing, which I enjoyed very much and discovered the difference of coding in Software Engineering and Electrical Engineering. 
