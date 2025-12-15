# Simplex-method-python

# Linear Programming Solver (Python)

This project is a **command-line Linear Programming (LP) solver** written in Python.  
It allows the user to define and solve **minimization or maximization problems** with linear constraints using `scipy.optimize.linprog`.

---

## Features

- Supports **min** and **max** optimization problems
- Handles any number of variables and constraints
- Supports constraint types:
  - `<=`
  - `>=` (automatically converted)
  - `=`
- Uses the **HiGHS** optimization method (fast and reliable)
- Interactive input via terminal

---

## Requirements

Make sure you have Python 3 installed, then install the required libraries:

```bash
pip install numpy scipy
