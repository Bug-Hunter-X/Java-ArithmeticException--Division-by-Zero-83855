# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` that occurs when dividing by zero.  The `bug.java` file contains the erroneous code, while `bugSolution.java` provides a solution to handle this exception gracefully.

## Understanding the Problem

Dividing any number by zero is undefined in mathematics and results in an `ArithmeticException` in Java. This exception halts the program's execution and throws an error message.

## Solution

To prevent this error, you need to check for the possibility of division by zero before performing the operation. This can be done using an `if` statement or a `try-catch` block.  The `bugSolution.java` file shows how to effectively handle the potential `ArithmeticException`.

## How to Run

1. Clone this repository.
2. Compile and run the `bug.java` (to observe the error) and `bugSolution.java` (to see the corrected code) files using a Java compiler (like `javac`) and runtime environment (like `java`).