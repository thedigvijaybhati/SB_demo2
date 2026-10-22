# python_programs Factorial Calculator 🧮

This is a simple Python program that calculates the **factorial of a number** entered by the user.

## Features

- Takes a number as input from the user.
- Checks whether the number is negative, zero, or positive.
- Displays an appropriate message for negative numbers.
- Calculates the factorial for positive numbers.
- Displays `1` as the factorial of zero.
- Prints a `hello` message at the end.

## How It Works

The program uses a `for` loop to calculate the factorial:

```python
factorial = 1

for i in range(1, num + 1):
    factorial = factorial * i
