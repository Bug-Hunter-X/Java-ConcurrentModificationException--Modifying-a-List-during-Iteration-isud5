# Java ConcurrentModificationException Example

This repository demonstrates a common error in Java: the `ConcurrentModificationException`.  This exception occurs when attempting to modify a collection (like an ArrayList) while iterating over it using an iterator that doesn't support concurrent modification.

The `ConcurrentModificationExceptionExample.java` file contains code that throws this exception.  The `ConcurrentModificationExceptionSolution.java` file shows how to safely modify the list using an `Iterator` and its `remove()` method.

## How to Run

1. Clone this repository.
2. Compile the Java files: `javac *.java`
3. Run the example: `java ConcurrentModificationExceptionExample`
4. Observe the exception.  Then, run `java ConcurrentModificationExceptionSolution` to see the correct solution.