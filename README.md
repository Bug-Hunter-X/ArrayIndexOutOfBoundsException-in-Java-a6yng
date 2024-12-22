# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common Java bug: the `ArrayIndexOutOfBoundsException`. The `bug.java` file contains code that attempts to access an array element beyond its valid range, leading to this exception.  The solution, `bugSolution.java`, shows how to prevent this error by checking array bounds before accessing elements.

## How to reproduce
1. Compile `bug.java` using a Java compiler (e.g., `javac bug.java`)
2. Run the compiled code (e.g., `java MyClass`)
3. Observe the `ArrayIndexOutOfBoundsException`

## Solution
The solution involves adding a check to ensure the index is within the valid range of the array before accessing the element.