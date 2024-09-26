---
title: "While Loop"
menu:
  main:
    parent: "java-loops"
    name: "While Loop"
    weight: 3
---

### Example 1:

```java
public class WhileLoopExample1 {
    public static void main(String[] args) {
        int i = 1;
        while (i <= 5) {
            System.out.println("Hello World");
            i++;
        }
    }
}
```

### Example 2 (Infinite Loop):

```java
public class WhileLoopExample2 {
    public static void main(String[] args) {
        while (true) {
            System.out.println("Infinite Loop");
        }
    }
}
```

