# Experiment 1 - Introduction to C++

---

## Aim: Hello World and Calculator Program
- To write a program that prints "Hello World".
- To write a program for a simple calculator (addition of two numbers).

---

## Software Required
- Visual Studio Code

---

## Theory

In C++, input and output are performed in the form of a sequence of bytes, more commonly known as **streams**.

- **Input Stream**: If the direction of flow of bytes is from the device (e.g., keyboard) to the main memory, then this process is called input.
- **Output Stream**: If the direction of flow of bytes is opposite (i.e., from main memory to device such as display screen), then this process is called output.

All these streams are defined inside the `<iostream>` header file, which contains the standard input and output tools of C++.

The two commonly used objects are:
- **cout** → Standard output stream, used with the insertion operator `<<` to display data on the screen.
- **cin** → Standard input stream, used with the extraction operator `>>` to take input from the user.

---

## Algorithm / Logic

### Program 1: Hello World
1. Start
2. Include header file `<iostream>`
3. Use `cout` to print "Hello World"
4. End

### Program 2: Basic Calculator
1. Start
2. Include header file `<iostream>`
3. Declare integer variables `num1`, `num2`, and `sum`
4. Take input for `num1` and `num2` using `cin`
5. Perform addition: `sum = num1 + num2`
6. Display the result using `cout`
7. End

---

## Conclusion

The basics of C++ input and output operations were demonstrated using two simple programs:

A program to print "Hello World".

A program to add two numbers using basic arithmetic operators.

This helped in understanding the concept of streams (cin and cout) and their usage in C++.
