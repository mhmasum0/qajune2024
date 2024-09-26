---
title: "Java Method Declaration"
menu:
  main:
    parent: "introduction-to-java"
    name: "Java Method Declaration"
    weight: 3
---

## Example 1:

```java
public int sum(int number1, int number2) {
    // Perform arithmetic operation
    int sum = number1 + number2;
    
    // Return result
    return sum;
}
```

## Example 2:

```java
public void displayMessage() {
    System.out.println("Hello, World!");
}
```

## Example 3:

```java
public int max(int number1, int number2) {
    if (number1 > number2) {
        return number1;
    } else {
        return number2;
    }
}
```