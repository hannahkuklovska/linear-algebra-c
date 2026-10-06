# Linear Algebra in C

A C project implementing matrix operations and methods for solving systems of linear equations.

The project includes dynamic matrix allocation, matrix multiplication, matrix inversion, file input/output, and Gaussian elimination.

## Overview

This project was created to practice implementing linear algebra algorithms in C.

Instead of relying on external libraries, the main matrix operations are implemented directly using custom data structures, dynamically allocated memory, and numerical algorithms.

The project demonstrates work with:

- C
- Dynamic memory allocation
- Pointers
- Structs
- Matrix operations
- Gaussian elimination
- Numerical methods
- File input/output
- Multi-file project organization
- Makefiles

## Features

- Dynamic matrix allocation
- Matrix creation
- Matrix initialization
- Loading matrices from files
- Printing matrices
- Matrix multiplication
- Matrix inversion
- Gaussian elimination
- Solving systems of linear equations
- Makefile-based compilation

## Matrix Representation

Matrices are represented using a custom structure and dynamically allocated memory.

This allows the program to work with matrices of different dimensions while keeping the implementation modular and reusable.

The project separates matrix-related functionality into dedicated source and header files.

## Matrix Operations

The project implements several common matrix operations.

These include:

- Creating matrices
- Loading matrix values from files
- Displaying matrix contents
- Multiplying matrices
- Computing matrix inverses
- Solving linear systems

## Solving Linear Systems

The project includes functionality for solving systems of linear equations.

One of the implemented approaches uses Gaussian elimination.

The system is transformed step by step into a simpler form from which the solution can be obtained.

The project also explores solving linear systems using matrix inversion.

For a system of equations written as:

```text
A × x = b
```

the solution can be expressed as:

```text
x = A⁻¹ × b
```

when the matrix `A` is invertible.

## Gaussian Elimination

Gaussian elimination transforms a matrix into an equivalent form using elementary row operations.

The process typically involves:

1. Selecting a pivot element
2. Eliminating values below the pivot
3. Repeating the process for the remaining rows
4. Solving for the unknown values

This project implements the algorithm directly in C.

## Project Structure

```text
linear-algebra-c/
│
├── main.c
├── mat.c
├── mat.h
├── makefile
├── mat_a.dat
├── mat_a.txt
└── README.md
```

### Main Files

- `main.c` — example usage and program entry point
- `mat.c` — implementation of matrix operations
- `mat.h` — matrix structure and function declarations
- `makefile` — build configuration
- `mat_a.dat` — example matrix data
- `mat_a.txt` — example matrix input
- `README.md` — project documentation

## Building the Project

### Requirements

To build the project, you need:

- GCC or another C compiler
- Make

### Clone the Repository

```bash
git clone https://github.com/hannahkuklovska/linear-algebra-c.git
cd linear-algebra-c
```

### Compile

```bash
make
```

Then run the generated executable defined in the Makefile.

## Concepts Demonstrated

This project demonstrates several important C and numerical-programming concepts:

- Dynamic memory allocation
- Pointers
- Structs
- Arrays
- File input/output
- Header and source file separation
- Matrix algebra
- Numerical algorithms
- Gaussian elimination
- Matrix inversion
- Multi-file project structure
- Makefiles

## What I Learned

Through this project, I practiced implementing mathematical algorithms directly in C.

I also gained experience with:

- representing matrices using custom data structures,
- allocating and managing memory dynamically,
- working with pointers,
- splitting a C project into reusable source and header files,
- implementing matrix multiplication,
- implementing matrix inversion,
- solving systems of linear equations,
- implementing Gaussian elimination,
- reading matrix data from files,
- and compiling multi-file projects with a Makefile.

## Possible Improvements

Future improvements could include:

- Better input validation
- Improved error handling
- Detection of singular matrices
- Improved numerical stability
- Partial pivoting during Gaussian elimination
- Automated tests
- Additional matrix operations
- Command-line input
- Performance improvements for larger matrices
- Improved documentation of individual functions

## Author

Hannah Kuklovska
