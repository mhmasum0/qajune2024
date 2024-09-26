---
title: "Else If Statement"
menu:
  main:
    parent: "java-operators-and-control-statements"
    name: "Else If Statement"
    weight: 2
---

```java
public class ElseIfStatement {
    public static void main(String[] args) {
        int number = 0;
        if (number > 0) {
            System.out.println("The number is positive.");
        } else if (number < 0) {
            System.out.println("The number is negative.");
        } else {
            System.out.println("The number is zero.");
        }
    }
}
```

## Another example:

```java
public class Main {

    public static void main(String[] args) {
        int number = 50;

        if(number <= 20) {
            System.out.println("Number is less than or equal to 20");
        } else if(number < 40) {
            System.out.println("Number is between 20 and 40");
        } else {
            System.out.println("Number is greater than or equal 40");
        }
    }
}
```