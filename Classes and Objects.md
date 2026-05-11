````md id="u9xk3p"
# Java Programming – UNIT II : Classes and Objects

This repository contains Java programs and notes related to **Classes and Objects** concepts in Java programming.

---

# 📘 Topics Covered

## 1. Introduction to Classes and Objects

- Basics of Object Oriented Programming
- Definition of Class and Object
- Real-world examples of classes and objects

---

# 🏛 Class Declaration and Modifiers

## Class Declaration

```java
class Student {
}
````

## Access Modifiers

* public
* private
* protected
* default

## Non-Access Modifiers

* final
* abstract
* static

---

# 👨‍💻 Class Members

Class members include:

* Variables (Data Members)
* Methods (Member Functions)
* Constructors

Example:

```java id="m1k4qp"
class Student {
    int id;
    String name;

    void display() {
        System.out.println(id + " " + name);
    }
}
```

---

# 📦 Declaration of Class Objects

Creating objects using `new` keyword:

```java id="r7n2vx"
Student s1 = new Student();
```

---

# 🏗 Constructor Methods for Class

## Default Constructor

```java id="t8y5lc"
class Demo {
    Demo() {
        System.out.println("Constructor Called");
    }
}
```

## Parameterized Constructor

```java id="q5v8bz"
class Student {
    int id;

    Student(int i) {
        id = i;
    }
}
```

---

# 🔑 Keyword `this`

The `this` keyword refers to the current object.

Example:

```java id="w3j6dn"
class Student {
    int id;

    Student(int id) {
        this.id = id;
    }
}
```

---

# ⚙ Methods in Java

## Defining Methods

```java id="a4p7mh"
class Demo {
    void show() {
        System.out.println("Method Example");
    }
}
```

---

# 🔁 Overloaded Methods

Method overloading means defining multiple methods with the same name but different parameters.

Example:

```java id="z2f9ks"
class Addition {

    int add(int a, int b) {
        return a + b;
    }

    double add(double a, double b) {
        return a + b;
    }
}
```

---

# 🧩 Attributes `final` and `static`

## final Keyword

Used to declare constants.

```java id="b8n1qt"
final int MAX = 100;
```

## static Keyword

Used for memory management and shared variables/methods.

```java id="c7v2rm"
class Test {
    static int count = 0;
}
```

---

# 💻 Sample Program

```java id="d6x4pl"
class Student {

    int id;
    String name;

    Student(int id, String name) {
        this.id = id;
        this.name = name;
    }

    void display() {
        System.out.println(id + " " + name);
    }

    public static void main(String args[]) {

        Student s1 = new Student(101, "Vinayak");
        s1.display();
    }
}
```

---

# 🛠 Requirements

* Java JDK 8 or above
* Java IDE or VS Code

---

# ▶️ How to Run

## Compile

```bash id="n4q7wc"
javac FileName.java
```

## Execute

```bash id="f8t1yv"
java FileName
```

---

# 🎯 Learning Outcomes

* Understand classes and objects
* Learn constructors and methods
* Implement method overloading
* Use `this`, `final`, and `static` keywords effectively

---

# 👨‍💻 Author

Vinayak Goud Kasani

```
```

