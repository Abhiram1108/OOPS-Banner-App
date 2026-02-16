# OOPS Banner App

## Overview
The OOPS Banner App is built incrementally using multiple use cases.
Each use case extends the previous one while following a structured Git workflow.

---

## Use Case 1 (UC1)
Prints the literal text `OOPS` to the console using a simple Java program.

---

## Use Case 2 (UC2): Print OOPS as Banner

### Goal
Extend UC1 by displaying the word **OOPS** in a large banner format using
asterisks (`*`) and spaces.

### Description
In this use case, the program prints a **multi-line ASCII banner** representation
of the word **OOPS**.  
Each letter is constructed manually using `*` and spaces and printed using
individual `System.out.println()` statements.

This use case focuses on understanding:
- ASCII art creation
- Manual string construction
- Sequential print statements
- Output alignment and readability

No loops, functions, or data structures are used in this use case, as the goal
is to understand the basic visual construction before refactoring in later use cases.

---

### Key Concepts Used
- ASCII Art using characters
- String literals and string concatenation
- Multiple print statements
- Console output formatting
- Incremental development using Git feature branches

---

## Use Case 3 (UC3): String.join Refactor

UC3 refactors the banner rendering logic from UC2 by replacing
string concatenation using the `+` operator with the `String.join()` method.

This improves memory efficiency by reducing intermediate String object creation
while preserving the same visual banner output.

### How to Run
```bash
javac OOPSBannerApp.java
java OOPSBannerApp
