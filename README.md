# Quadratic Equations Solver

The program calculates the roots of a quadratic equation of the general form: y = ax ^ 2 + bx + c = 0

# How to use

The function get_roots, takes 3 required arguments get_roots (a, b, c)

Example:
```python
import quadratic_equation

print (quadratic_equation.get_roots (1, 2, -3))
```
The output is output to the console: (-3.0, 1.0)

# How to start

The script requires the installed Python interpreter version 3.5

Running on Linux:
```bash
python tests.py # You might need a python3 call instead of python, depending on the settings of the operating system
```
Running on Windows is similar.

# Pre-commit hook

To autorun tests when you try to make commit

1. Add the pre-commit file to the directory 14_pre_commit_hook/.git/hooks
2. Give permission to run:
```bash
chmod +x .git/hooks/pre-commit
```
# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
