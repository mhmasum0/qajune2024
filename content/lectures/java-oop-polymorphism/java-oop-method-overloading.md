---
title: "Java OOP Method Overloading"
menu:
  main:
    parent: "java-oop-polymorphism"
    name: "Java OOP Method Overloading"
    weight: 2
---

### Java OOP Method Overloading( Changing the number of arguments):

```java
class Adder {
    static int add(int a, int b) {
        return a + b;
    }
    static int add(int a, int b, int c) {
        return a + b + c;
    }
}
```

### Java OOP Method Overloading( Changing the data type of arguments):

```java
class Adder {
    static int add(int a, int b) {
        return a + b;
    }
    static double add(double a, double b) {
        return a + b;
    }
}
```
