---
title: "Java Variables"
menu:
  main:
    parent: "introduction-to-java"
    name: "Java Variables"
    weight: 2
---

```java
public class JavaVariables {
    public static void main(String[] args) {
        // Declare variables
        int number1;
        int number2;
        int sum;

        // Assign values to variables
        number1 = 5;
        number2 = 10;

        // Perform arithmetic operation
        sum = number1 + number2;

        // Display result
        System.out.println("The sum of " + number1 + " and " + number2 + " is " + sum);
    }
}
```