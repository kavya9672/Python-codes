# Beginner Python: Factorial and Fibonacci

This repository contains a first Python program in `factorial-fibonacci.py`. It is a simple script with hardcoded values. It does not take user input, define functions, or import libraries.

## What the program does

The file runs three sequential print sections, then includes lecture notes as comments.

1. **Print a number**  
   Prints `5`.

2. **Factorial**  
   Sets `n = 5` and `fact = 1`. A `for` loop multiplies `fact` by each integer from `1` through `n` (`range(1, n+1)`), then prints `fact`.

3. **Fibonacci section**  
   Sets `n = 10`, `a = 0`, and `b = 1`. A `for` loop over `range(n)` prints `a` on one line, separated by spaces (`end=" "`). The lines that compute `next = a + b` and update `a` and `b` are indented at the same level as the `for` loop, so they run once after the loop finishes.

The rest of the file is lecture notes comparing C structs/types with Python dictionaries and dynamic typing. Those notes are not executed.

## How to run it

You need Python 3 installed. From this directory:

```bash
python factorial-fibonacci.py
```

On some systems the command is `python3` instead of `python`.

## Learning objective

This file is an introductory look at:

- using variables
- `for` loops and `range`
- multiplying values in a loop (factorial)
- printing on one line with `end`
- how indentation decides whether code runs inside a loop or after it
