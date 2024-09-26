---
title: "Java OOP Abstract Class"
menu:
  main:
    parent: "java-oop-abstraction"
    name: "Java OOP Abstract Class"
    weight: 1
---

### Java OOP Abstract Class:

```java
abstract class Animal {
    abstract void sound();
    void eat() {
        System.out.println("Eating...");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Bark");
    }
}

class AbstractClassExample {
    public static void main(String[] args) {
        Animal animal = new Dog();
        animal.sound();
        animal.eat();
    }
}
```