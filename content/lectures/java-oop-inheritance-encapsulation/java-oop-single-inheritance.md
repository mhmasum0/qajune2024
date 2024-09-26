---
title: "Java OOP Single Inheritance"
menu:
  main:
    parent: "java-oop-inheritance-encapsulation"
    name: "Java OOP Single Inheritance"
    weight: 1
---

## Java OOP Single Inheritance:

```java
class Animal {
  void eat() {
    System.out.println("eating...");
  }
}

class Dog extends Animal {
  void bark() {
    System.out.println("barking...");
  }
}

class TestInheritance {
  public static void main(String[] args) {
    Dog dog = new Dog();
    dog.bark();
    dog.eat();
  }
}
```