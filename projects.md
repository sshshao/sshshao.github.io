---
layout: page
title: Programming Projects
permalink: /projects/
---


### *Regio Vinco* Map Editor
[Software Design Description (PDF)](../docs/RigioVincoMapEditorSDD.pdf){:target="_blank"}

*Regio Vinco* is a map-picking game proided by the professor ([demo](https://www.youtube.com/watch?v=HXFr6on4Yug){:target="_blank"}). The *Regio Vinco* Map Editor is a editing software written in Java that can construct maps for the game. The editor use Simple App Framework to perform basic file operations. The editing file and exported map is constructed in JSON format.

![screenshot](../images/rvme_sc.png "Regio Vinco Map Editor")
![screenshot](../images/rvme_sc2.png "Regio Vinco Map Editor")

This software is the first "big" project with user interface I have done, and which I learned the whole process of releasing a software, from software design to beta test and review.

<br><br>

### Seawolf Script
A simple "console" parser implemented with PLY (Python Lex-Yacc). Supports if statements, while loops and functions (procedures).

Sample executable code:

```python
 #global variables
 fibonacciTable = [ 0, 0, 0, 0, 0 ];
 
 #procedure definition
 fibonacci(index) {
     if (index == 0) {
         return 0;
     }
     if (index == 1) {
         fibonacciTable[1]=1;
         return fibonacciTable[1];
     }
     if(fibonacciTable[index] <> 0) {
         return fibonacciTable[index];
     } else {
         fibonacciTable[index] = fibonacci(index - 1) + fibonacci(index - 2);
         return fibonacciTable[index];
     }
 }
 
 #main execution
 {
     print(fibonacci(4));
 }
 ```

<br><br>

### Memory Allocator
This is a Dynamic Memory Allocator for Unix Systems, using fixed-size block allocation with "first fit" algorithm. Functions such as malloc, free and realloc is supported.

<br><br>

### (Bash-like) Unix Shell
A beta version. The basic functions and commands are same as Bash. Supports additional keyboard shortcuts.

![screenshot](../images/shell_sc.jpg "Custom Shell")

<br><br>

### Digital Alarm Clock - A Real One!
An LED alarm clock with a USB charger which I made in a Electical Engineering course. Seconds are indicated by the six LED diodes on the bottom in binary.

![screenshot](../images/clock.JPG "Clock")
![screenshot](../images/clock_usb.JPG "USB port")
