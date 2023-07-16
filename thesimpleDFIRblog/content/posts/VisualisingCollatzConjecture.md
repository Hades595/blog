---
title: "Visualising Collatz Conjecture"
date: 2023-07-16T14:37:21+12:00
tags: ['Other Cool Stuff', 'Python']
---

This is a simple visualisation of the Collatz Conjecture Problem.

The conjecture is take a positive integer: 
- If it is an odd number: 
      We multiple by 3 and add 1

- If it is an even number: 
      We divide by 2

We keep applying these rules, until we reach a loop of 4 -> 2 -> 1.

Because every positive number will end up in the 4,2,1 loop. 

I based it off [Veritasium's explanation](https://www.youtube.com/watch?v=094y1Z2wpJg)

So far this is the result I have gotten with 1000:

![Figure1](/imgs/CollatzConjecturePicture.png)

Increasing the number only follows the same pattern. 

Here's the animated version:

![animated](/imgs/CollatzAnimation.gif)


This is just a simple project, in no way I am a expert at math or this conjecture.
I just thought this would be a interesting project.

The code is avaliable [here](https://github.com/Hades595/Visualising-Collatz-Conjecture).