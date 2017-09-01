---
layout: project
type: project
image: images/vacay-square.png
title: Sudoku Solver
permalink: projects/sudoku-solver
date: 2015
labels:
  - Java
  
summary: A sudoku solving program I wrote for ICS 211.
---

Sudoku Solver
For a project in ICS 211, I was tasked to create a Sudoku solver using recursion. This was a fun one that involved some thinking beforehand and was a good introduction to the idea that some techniques that would be awful for people are peanuts for computers. Much like my snake project, this isnft the most original project but it does represent perhaps my favorite solo project. 

As one would expect from a recursive sudoku solver, the program would brute force its way through a sudoku. First, it would find the first blank and try every number 1 through 9 on that space, and then choose the first one that fulfills the immediate row, column, and square. It then moved on to the next space and tried the same thing and if it found a space where it couldnft put anything in, the program would fall back to the most recent space it filled and try another, and so on and so forth. 

It was a fun project to work on and it reinforced the difference between solo and group projects. Solo projects are great because you donft have to answer to anyone but your boss for your code, dependenceis, and features. However, as a group, people rely on you to finish what they need you to do so therefs a lot more stress, but also a lot more motivation to finish. This project probably took longer than it needed to
