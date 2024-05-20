################################################################################
Name: Maitland Huffman
Class: CS2318-253 (Assembly Language, Spring 2023)
Subject: Assignment 3 Part 1
Date: 4/30/2023
################################################################################

MIPS Assembly Program: Reverse Array
################################################################################

Description:
This MIPS assembly language program serves as a translation of a given C++ program,
designed to take a user-specified number of integers as input, store them in an array,
reverse the order of the array elements, and then display the reversed array.
It consists of several "trivial" functions, each of which is a leaf function and does
not require local storage on the stack. The main function orchestrates the process,
calling these trivial functions as necessary.

Algorithm:
- The program starts by prompting the user to input the number of integers to be entered.
- It then proceeds to prompt the user for each integer, storing them in an array.
- Once the array is filled, it displays the original array.
- It then reverses the order of the array elements.
- Finally, it displays the reversed array.
- The program then prompts the user if they want to perform the operation again.
- It repeats the process until the user decides to exit.

Register Usage:
- $t0: Temporary register holder for various values.
- $t1: Iterator variable used in loops.
- $t2: Another iterator variable used in loops.

Sample Test Run:
- The program prompts the user for the number of integers to input.
- User inputs the integers.
- Original array is displayed.
- Reversed array is displayed.
- User is prompted if they want to repeat the process.
- Program terminates when the user decides to exit.

Instructions for Running:
- The MIPS assembly program can be run using a suitable MIPS emulator or simulator.
- Load the program into the emulator/simulator environment.
- Execute the program.
- Follow the on-screen prompts to input integers and observe the results.

Note:
- This program is primarily an exercise in MIPS assembly language translation of a given
C++ program, focusing on understanding MIPS function-call mechanism, pass-by-value,
pass-by-address, and basics of array manipulation.
- It does not adhere to function-call conventions and serves as a learning tool rather
than a production-ready solution.

Credits:
- Maitland Huffman: Author of the MIPS assembly translation.
- CS2318-253 (Assembly Language, Spring 2023): Course details.
