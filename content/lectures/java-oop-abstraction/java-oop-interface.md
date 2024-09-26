---
title: "Java OOP Interface"
menu:
  main:
    parent: "java-oop-abstraction"
    name: "Java OOP Interface"
    weight: 2
---

### Java OOP Interface:

```java
interface Animal {
    void sound();
    void eat();
}

class Dog implements Animal {
    public void sound() {
        System.out.println("Bark");
    }
    public void eat() {
        System.out.println("Eating...");
    }
}

class InterfaceExample {
    public static void main(String[] args) {
        Animal animal = new Dog();
        animal.sound();
        animal.eat();
    }
}
```

### Java OOP Multiple Inheritance:

```java
interface Animal {
    void sound();
}
interface Mammal {
    void eat();
}
class Dog implements Animal, Mammal {
    public void sound() {
        System.out.println("Bark");
    }
    public void eat() {
        System.out.println("Eating...");
    }
}
class InterfaceExample {
    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.sound();
        dog.eat();
    }
}
```