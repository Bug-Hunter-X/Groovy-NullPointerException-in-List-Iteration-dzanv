# Groovy NullPointerException in List Iteration

This repository demonstrates a common Groovy error: a `NullPointerException` occurring when a method iterates over a list that might be null.  The issue arises when the method doesn't handle the possibility of a null list being passed as an argument.

The `bug.groovy` file contains the buggy code, while `bugSolution.groovy` provides the corrected version.

## How to reproduce the bug

Simply run the `bug.groovy` script. It will throw a `NullPointerException` because the `each` method is called on a null list.

## Solution

The `bugSolution.groovy` file demonstrates how to avoid the exception by checking for null before iterating.