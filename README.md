# Pointers-in-C
A beginner-friendly C programming repository that demonstrates the concept of pointers, including pointer declaration, initialization, dereferencing, and basic pointer operations.

This repository contains a simple C program that explains the **concept of pointers** in C programming.
Pointers are variables that store the memory address of another variable.

## 🔹 What is a Pointer?
A pointer is a variable that holds the address of another variable.
Pointers are widely used for memory management, arrays, strings, and functions.

## 🔹 Concepts Covered
- Pointer declaration
- Pointer initialization
- Dereferencing
- Address-of operator (&)
- Value at address operator (*)

## 🔹 Source Code
```c
#include <stdio.h>

int main() {
    int num = 10;
    int *ptr;

    ptr = &num;

    printf("Value of num: %d\n", num);
    printf("Address of num: %p\n", &num);
    printf("Value stored in ptr: %p\n", ptr);
    printf("Value pointed by ptr: %d\n", *ptr);

    return 0;
}
