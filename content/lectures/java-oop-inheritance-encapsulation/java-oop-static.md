---
title: "Java OOP: Static Keyword"
menu:
  main:
    parent: "java-oop-inheritance-encapsulation"
    name: "Java OOP: Static Keyword"
    weight: 4
---

## Java OOP Static Keyword:

```java
class Student {
    int studentId; // instance variable
    String studentName;
    static String collegeName = "XYZ"; // static variable
    
    // constructor
    Student(int studentId, String studentName) {
        this.studentId = studentId;
        this.studentName = studentName;
    }
    
    // method to display the values
    void display() {
        System.out.println(studentId + " " + studentName + " " + collegeName);
    }
    
    public static void main(String args[]) {
        Student s1 = new Student(111, "Karan");
        Student s2 = new Student(222, "Aryan");
        
        s1.display();
        s2.display();
    }
}
```

### Static Method:

```java
class Student {
    int studentId;
    String studentName;
    static String collegeName = "XYZ";
    
    // constructor
    Student(int studentId, String studentName) {
        this.studentId = studentId;
        this.studentName = studentName;
    }
    
    // method to display the values
    void display() {
        System.out.println(studentId + " " + studentName + " " + collegeName);
    }
    
    // static method to change the value of static variable
    static void change() {
        collegeName = "ABC";
    }
    
    public static void main(String args[]) {
        Student s1 = new Student(111, "Karan");
        Student s2 = new Student(222, "Aryan");
        
        s1.display();
        s2.display();
        
        // calling change method
        Student.change();
        
        s1.display();
        s2.display();
    }
}
```

