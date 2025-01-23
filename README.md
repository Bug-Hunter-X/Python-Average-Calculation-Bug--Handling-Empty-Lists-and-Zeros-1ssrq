# Python Average Calculation Bug: Handling Empty Lists and Zeros

This repository demonstrates a common error in Python when calculating the average of a list of numbers.  The original code lacked proper handling for empty lists and lists containing only zeros, potentially leading to unexpected results (like ZeroDivisionError).

The `bug.py` file contains the buggy code, while `bugSolution.py` offers a corrected version.

## Bug Description:
The `calculate_average` function fails to gracefully handle empty lists and lists composed entirely of zeros, resulting in a `ZeroDivisionError` in the former case and unexpected 0 in the latter case. 

## Solution:
The corrected code in `bugSolution.py` includes explicit checks to handle these edge cases, providing a more robust and reliable average calculation.