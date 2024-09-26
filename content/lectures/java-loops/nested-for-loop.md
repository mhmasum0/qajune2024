---
title: "Nested For Loop"
menu:
  main:
    parent: "java-loops"
    name: "Nested For Loop"
    weight: 2
---

### Example 1:

```java
public class NestedForLoopExample1 {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= 5; j++) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

### Example 2:

```java
public class NestedForLoopExample2 {
    public static void main(String[] args) {
        for (int i = 0; i < 3; i++) { // Outer loop
            for (int j = 0; j < 3; j++) { // Inner loop
                System.out.println("i: " + i + ", j: " + j);
            }
        }
    }
}
```

