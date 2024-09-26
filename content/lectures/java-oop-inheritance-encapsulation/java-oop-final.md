---
title: "Java OOP: Final Keyword"
menu:
  main:
    parent: "java-oop-inheritance-encapsulation"
    name: "Java OOP: Final Keyword"
    weight: 4
---

## Java OOP Final Keyword:

```java
class Bike {
    final int speedlimit = 90; // final variable
    void run() {
        speedlimit = 400; // Compile Time Error
    }
}

class Main {
    public static void main(String args[]) {
        Bike obj = new Bike();
        obj.run();
    }
}
```