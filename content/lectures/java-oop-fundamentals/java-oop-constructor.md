---
title: "Java OOP Constructor"
menu:
  main:
    parent: "java-oop-fundamentals"
    name: "Java OOP Constructor"
    weight: 1
---

## Java OOP Constructor:

```java
public class ConstructorExample {
    int x;
    int y;

    // Default Constructor
    public ConstructorExample() {
        x = 10;
        y = 20;
    }

    // Parameterized Constructor
    public ConstructorExample(int x, int y) {
        this.x = x;
        this.y = y;
    }

    public void display() {
        System.out.println("x = " + x + " y = " + y);
    }

    public static void main(String[] args) {
        ConstructorExample obj1 = new ConstructorExample();
        obj1.display();

        ConstructorExample obj2 = new ConstructorExample(100, 200);
        obj2.display();
    }
}
```