# Dart Reduce Method Error Handling with Empty Lists

This repository demonstrates a common error encountered when using the `reduce` method in Dart with empty lists. The `reduce` method requires at least one element to perform the accumulation.  Attempting to use it on an empty list will result in an error.

The `bug.dart` file shows the error-causing code. The `bugSolution.dart` file offers a solution to handle this scenario gracefully.

## Solution

The solution involves checking if the list is empty before calling the `reduce` method. If the list is empty, a default value can be returned to prevent errors.