# Java Functions (Methods)

## What is a Function?
A function (or method) is a block of code that performs a specific task. Functions help organize code and avoid repetition.

## Key Points
- Functions can take inputs (parameters) and return outputs (return values)
- Defined inside a class
- Can be reused multiple times

## Example
```java
public class Main {

    // Function that adds two numbers
    static int add(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        int sum = add(5, 3);
        System.out.println("Sum is: " + sum);
    }
}
##Practice

Write a Java method called multiply that takes two integers as input and returns their product.
