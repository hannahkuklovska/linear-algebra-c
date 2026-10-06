# Linear Algebra in C

A small linear algebra project written in C that implements basic matrix operations and methods for solving systems of linear equations.

The project focuses on working with matrices using dynamically allocated memory and includes functionality for matrix multiplication, inversion, file input/output, and Gaussian elimination.

## Features

- Dynamic matrix allocation
- Matrix creation and initialization
- Loading matrices from files
- Printing matrices
- Matrix multiplication
- Matrix inversion
- Gaussian elimination
- Solving systems of linear equations
- Makefile-based compilation

## Project Structure

- `mat.h` — matrix structure and function declarations
- `mat.c` — implementation of matrix operations
- `main.c` — example usage and testing
- `makefile` — build configuration
- `mat_a.dat` / `mat_a.txt` — example matrix input data

## Matrix Representation

Matrices are represented using a custom structure and dynamically allocated memory.

This allows the program to work with matrices of different sizes while keeping the implementation modular and reusable.

## Solving Linear Systems

The project includes functionality for solving systems of linear equations.

One of the implemented approaches uses Gaussian elimination, where the system is transformed step by step into a form from which the solution can be obtained.

The project also explores solving systems using matrix inversion.

## Building the Project

Clone the repository:

```bash
git clone https://github.com/hannahkuklovska/E2.git
cd E2

