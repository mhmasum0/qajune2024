---
title: "Switch Statement"
menu:
  main:
    parent: "java-operators-and-control-statements"
    name: "Switch Statement"
    weight: 3
---

### Example 1:
```java
public class SwitchStatement {
    public static void main(String[] args) {
        int day = 3;
        String dayString;

        switch (day) {
            case 1:
                dayString = "Monday";
                break;
            case 2:
                dayString = "Tuesday";
                break;
            case 3:
                dayString = "Wednesday";
                break;
            case 4:
                dayString = "Thursday";
                break;
            case 5:
                dayString = "Friday";
                break;
            case 6:
                dayString = "Saturday";
                break;
            case 7:
                dayString = "Sunday";
                break;
            default:
                dayString = "Invalid day";
                break;
        }

        System.out.println(dayString);
    }
}
```

### Example 2:
```java
public class Main {

    public static void main(String[] args) {
        int number = 3;
        String numberString;

        switch (number) {
            case 1:
                numberString = "One";
                break;
            case 2:
                numberString = "Two";
                break;
            case 3:
                numberString = "Three";
                break;
            case 4:
                numberString = "Four";
                break;
            case 5:
                numberString = "Five";
                break;
            default:
                numberString = "Invalid number";
                break;
        }

        System.out.println(numberString);
    }
}
```