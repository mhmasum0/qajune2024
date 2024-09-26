---
title: "Java Multi-Dimensional Array"
menu:
  main:
    parent: "java-arrays"
    name: "Java Multi-Dimensional Array"
    weight: 2
---

### Example 1:

```java
class JavaMultidimensionalArray{
    public static void main(String[] args) {
        int[][] intArray = new int[2][3];
        intArray[0][0] = 10;
        intArray[0][1] = 20;
        intArray[0][2] = 30;
        intArray[1][0] = 40;
        intArray[1][1] = 50;
        intArray[1][2] = 60;
        for (int i = 0; i < intArray.length; i++) {
            for (int j = 0; j < intArray[i].length; j++) {
                System.out.println(intArray[i][j]);
            }
        }
    }
}
```

### Example 2:

```java
class JavaMultidimensionalArray2{
    public static void main(String[] args) {
        int[][] intArray = {{10, 20, 30}, {40, 50, 60}};
        for (int i = 0; i < intArray.length; i++) {
            for (int j = 0; j < intArray[i].length; j++) {
                System.out.println(intArray[i][j]);
            }
        }
    }
}
```