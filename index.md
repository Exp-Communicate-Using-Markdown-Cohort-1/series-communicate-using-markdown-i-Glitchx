# This is my markdown test page
## I love github
##### Im going to have the career I always dreamed of!
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
# Factorial Calculation in Python

## Description
This example demonstrates how to calculate the factorial of a number using a recursive function in Python.

## Code Example

```python
def factorial(n):
    """
    Calculate the factorial of a number using recursion.

    Parameters:
    n (int): The number to calculate the factorial of.

    Returns:
    int: The factorial of the number.
    """
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Example usage
number = 5
print(f"The factorial of {number} is {factorial(number)}")
