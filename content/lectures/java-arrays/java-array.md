---
title: "Java Array"
menu:
  main:
    parent: "java-arrays"
    name: "Java Array"
    weight: 1
---

### Example 1:

```java
public class ArrayExample {
    public static void main(String[] args) {
        int[] numbers = new int[5];
        numbers[0] = 10;
        numbers[1] = 20;
        numbers[2] = 30;
        numbers[3] = 40;
        numbers[4] = 50;

        for (int i = 0; i < numbers.length; i++) {
            System.out.println(numbers[i]);
        }
    }
}
```

### Example 2:

```java
public class ArrayExample2 {
    public static void main(String[] args) {
        int[] numbers = {10, 20, 30, 40, 50};

        for (int i = 0; i < numbers.length; i++) {
            System.out.println(numbers[i]);
        }
    }
}
```

### Example 3:

```java
public class ArrayExample3 {
    public static void main(String[] args) {
        int[] intArray = getArray();
        for (int i = 0; i < intArray.length; i++) {
            System.out.println(intArray[i]);
        }
    }

    public static int[] getArray() {
        int[] intArray = new int[5];
        intArray[0] = 10;
        intArray[1] = 20;
        intArray[2] = 30;
        intArray[3] = 40;
        intArray[4] = 50;
        return intArray;
    }
}
```