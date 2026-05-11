````md id="k7m2qp"
# Java Programming – UNIT III : Arrays

This repository contains Java programs and notes related to **Arrays in Java Programming**.

---

# 📘 Topics Covered

## 1. Introduction to Arrays

An array is a collection of elements of the same data type stored in contiguous memory locations.

### Features of Arrays
- Stores multiple values in a single variable
- Fixed size
- Easy access using index values

---

# 📦 Declaration of Arrays

## Syntax

```java
dataType[] arrayName;
````

## Example

```java id="a1b2c3"
int[] numbers;
```

---

# 🛠 Initialization of Arrays

## Method 1: Declaration with Size

```java id="d4e5f6"
int[] numbers = new int[5];
```

## Method 2: Direct Initialization

```java id="g7h8i9"
int[] numbers = {10, 20, 30, 40, 50};
```

---

# 💾 Storage of Arrays in Computer Memory

* Arrays are stored in contiguous memory locations.
* Each element is identified using an index.
* Array indexing starts from `0`.

Example:

```text
Index : 0   1   2   3   4
Value : 10  20  30  40  50
```

---

# 🔍 Accessing Elements of Arrays

Elements are accessed using index values.

## Example

```java id="j1k2l3"
int[] numbers = {10, 20, 30, 40};

System.out.println(numbers[0]);
System.out.println(numbers[2]);
```

---

# 🔁 Using for Loop with Arrays

## Example

```java id="m4n5o6"
class ArrayDemo {

    public static void main(String args[]) {

        int[] numbers = {10, 20, 30, 40, 50};

        for(int i = 0; i < numbers.length; i++) {
            System.out.println(numbers[i]);
        }
    }
}
```

---

# 🔄 Enhanced for-each Loop

## Example

```java id="p7q8r9"
class ForEachDemo {

    public static void main(String args[]) {

        int[] numbers = {1, 2, 3, 4, 5};

        for(int num : numbers) {
            System.out.println(num);
        }
    }
}
```

---

# 💻 Sample Program

## Sum of Array Elements

```java id="s1t2u3"
class ArraySum {

    public static void main(String args[]) {

        int[] arr = {10, 20, 30, 40, 50};

        int sum = 0;

        for(int i = 0; i < arr.length; i++) {
            sum = sum + arr[i];
        }

        System.out.println("Sum = " + sum);
    }
}
```

---

# 🛠 Requirements

* Java JDK 8 or above
* Any Java IDE or VS Code

---

# ▶️ How to Run

## Compile

```bash id="v4w5x6"
javac FileName.java
```

## Run

```bash id="y7z8a9"
java FileName
```

---

# 🎯 Learning Outcomes

* Understand arrays and memory storage
* Learn array declaration and initialization
* Access array elements using index values
* Implement loops with arrays

---

# 👨‍💻 Author

Vinayak Goud Kasani

```
```

