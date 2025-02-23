# C Pointers: Subtle Issues and Unexpected Behavior

This repository contains a simple C program that highlights a common source of confusion and potential errors when working with pointers:  unintended modification of values via pointers passed to functions.

## The Problem

The `bug.c` file demonstrates how modifying a variable indirectly through a pointer can lead to unexpected results if not handled carefully. While the code itself is correct, it showcases a potential pitfall that could arise in larger, more complex projects.

## The Solution

The `bugSolution.c` file doesn't fundamentally change the code's functionality,  but it improves code clarity by clearly showing the use of pointers and how they modify the value.  The comments have been enhanced to explain this.