# Java Method and Function Reference

This repository provides a comprehensive reference guide for methods and functions in the Java programming language. Whether you're a beginner looking to understand basic concepts or an experienced developer seeking clarification on advanced features, this guide aims to assist you in navigating through Java's extensive library of methods and functions.

## Table of Contents

1. [Introduction](#introduction)
2. [Basic Methods](#basic-methods)
3. [Standard Library Functions](#standard-library-functions)
4. [Advanced Techniques](#advanced-techniques)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

Java is a versatile programming language widely used for developing various types of applications, including web, mobile, and enterprise software. Methods and functions play a crucial role in Java programming, allowing developers to organize code into reusable blocks and perform specific tasks efficiently.

## Basic Methods

In Java, a method is a collection of statements that perform a specific task and is defined within a class. Here are some fundamental types of methods:

### Instance Methods

Instance methods are associated with objects of a class and can access instance variables and other instance methods.

```java
public class MyClass {
    int x;

    // Instance Method
    void setX(int newValue) {
        x = newValue;
    }

    public static void main(String[] args) {
        MyClass obj = new MyClass();
        obj.setX(10);
        System.out.println("Value of x: " + obj.x); // Output: 10
    }
}
```
### Static Methods
Static methods belong to the class rather than any specific instance and can be invoked without creating an object of the class.

```java
public class MyClass {
    static int square(int num) {
        return num * num;
    }

    public static void main(String[] args) {
        int result = MyClass.square(5);
        System.out.println("Square of 5: " + result); // Output: 25
    }
}
```
