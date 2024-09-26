---
title: "Java OOP Method Overriding"
menu:
  main:
    parent: "java-oop-polymorphism"
    name: "Java OOP Method Overriding"
    weight: 1
---

## Java OOP Method Overriding:

```java
class Animal {
    void sound() {
        System.out.println("Animals make sound");
    }
}
class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Dog barks");
    }
}
class Cat extends Animal {
    @Override
    void sound() {
        System.out.println("Cat meows");
    }
}
public class Main {
    public static void main(String[] args) {
        Animal myAnimal;

        myAnimal = new Dog();
        myAnimal.sound();  // Calls Dog's sound method

        myAnimal = new Cat();
        myAnimal.sound();  // Calls Cat's sound method
    }
}
```
