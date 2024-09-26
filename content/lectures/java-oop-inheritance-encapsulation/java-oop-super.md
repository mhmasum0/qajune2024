---
title: "Java OOP: Super Keyword"
menu:
  main:
    parent: "java-oop-inheritance-encapsulation"
    name: "Java OOP: Super Keyword"
    weight: 3
---

## Java OOP Super Keyword:

```java
class Animal {
    void eat() {
        System.out.println("Animal is eating...");
    }
}

class Dog extends Animal {
    void eat() {
        super.eat();  // Calls the parent class method
        System.out.println("Dog is eating...");
    }
}

public class TestSuper {
    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.eat();
    }
}
```