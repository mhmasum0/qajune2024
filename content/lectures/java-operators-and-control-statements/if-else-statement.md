---
title: "If-Else Statement"
menu:
  main:
    parent: "java-operators-and-control-statements"
    name: "If-Else Statement"
    weight: 1
---

```java
public class IfElseStatement {
    public static void main(String[] args) {
        int number = 10;
        if (number > 0) {
            System.out.println("The number is positive.");
        } else {
            System.out.println("The number is negative.");
        }
    }
}
```

## Another example:

```java
public class Main {

    public static void main(String[] args) {
        boolean isLightOn = false;

        if(isLightOn) {
            System.out.println("The light is turned on");
        } else {
            System.out.println("The light is turned off");
        }
    }
}
```