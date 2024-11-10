# Lab-7
---
# Parallel Matrix Operations

This project implements parallel matrix addition, subtraction, and dot product using pthreads in C. Given two 20x20 matrices, the operations are divided across 10 threads to improve performance.

## Files
- matrix.c: Source code for matrix operations.
- Makefile: Compiles the project.

## Compilation and Execution

1. Compile the Code:
   ```bash
   gcc -std=c99 -o matrix_program matrix.c -lpthread
   ```

2. Run the Program:
   ```bash
   ./matrix_program
   ```

## Features
- Matrix Addition: Computes element-wise addition.
- Matrix Subtraction: Computes element-wise subtraction.
- Matrix Dot Product: Computes the dot product.

Each operation uses 10 threads, where each thread processes a 4x20 section of the matrix.

## Output
The program displays the two input matrices and the results of the addition, subtraction, and dot product operations.
