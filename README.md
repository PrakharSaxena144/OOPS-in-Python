# Object-Oriented Programming (OOP) Practice in Python

## Overview

This repository contains my hands-on practice of **Object-Oriented Programming (OOP)** concepts and commonly used **Design Patterns** in Python. The programs are written to strengthen the understanding of object-oriented principles through practical examples rather than large-scale applications.

The folder covers the implementation of core OOP concepts such as abstraction, encapsulation, inheritance, polymorphism, and several popular design patterns including Factory, Singleton, Proxy, and Decorator.

---

## Topics Covered

### 1. Decorators

* Understanding function decorators
* Logging function execution
* Passing arguments using `*args` and `**kwargs`
* Monitoring function execution time
* Comparing implementation with and without decorators

**Key Concepts**

* Higher-order functions
* Function wrapping
* Code reusability
* Cross-cutting concerns (logging, timing)

---

### 2. Encapsulation

Implementation of data hiding using:

* Public members
* Protected members (`_variable`)
* Private members (`__variable`)
* Public interfaces to access private functionality

The example demonstrates:

* Adding grades
* Calculating average
* GPA calculation
* Hidden pass/fail logic

**Key Concepts**

* Data hiding
* Controlled access
* Private helper methods
* Information security

---

### 3. Abstract Classes (Abstraction)

Uses Python's `abc` module to define abstract base classes.

Examples include:

* Vehicle base class
* Car implementation
* Motorcycle implementation

**Key Concepts**

* Abstract Base Classes (ABC)
* `@abstractmethod`
* Interface implementation
* Runtime polymorphism

---

### 4. Factory Design Pattern

Implements a simple factory responsible for creating different vehicle objects.

Features:

* Centralized object creation
* Eliminates direct object instantiation by the client
* Supports optional parameters using `**kwargs`

**Key Concepts**

* Factory Method
* Loose coupling
* Object creation abstraction

---

### 5. Singleton Design Pattern

Implements the Singleton pattern using the `__new__()` method.

Example:

* Family member hierarchy
* Only one Father object can exist
* Multiple Kid objects are allowed

**Key Concepts**

* Single instance creation
* Shared global object
* Controlled initialization

Example use cases:

* Logger
* Database connection
* Configuration manager
* Cache manager

---

### 6. Proxy Design Pattern

Introduces the Proxy pattern where one class controls access to another class.

The example models:

* Vehicle interface
* RealCar implementation
* Authentication/authorization layer (concept)

**Key Concepts**

* Access control
* Lazy initialization
* Security layer
* Proxy object

---

## Python Concepts Practiced

* Classes and Objects
* Constructors (`__init__`)
* `__new__()` method
* Inheritance
* Method Overriding
* Abstraction
* Encapsulation
* Polymorphism
* Static Methods
* Decorators
* Abstract Base Classes
* Design Patterns

---

## Folder Structure

```text
OOPS_Practice/
│
├── Decorators.ipynb
├── Encapsulation.ipynb
├── Factory_Design_Pattern.ipynb
├── Proxy_Design_Pattern.ipynb
├── Singleton_Design_Pattern.ipynb
└── README.md
```

*(File names may vary depending on your local folder structure.)*

---

## Learning Objectives

This practice repository was created to:

* Build a strong understanding of Object-Oriented Programming in Python.
* Learn how design patterns solve common software engineering problems.
* Improve code modularity and maintainability.
* Practice writing reusable and extensible Python code.
* Prepare for technical interviews and real-world software development.

---

## Technologies Used

* Python 3.10+
* Jupyter Notebook
* Python Standard Library

  * `abc`
  * `time`

---

## Future Improvements

Planned additions include:

* Strategy Design Pattern
* Observer Design Pattern
* Builder Pattern
* Adapter Pattern
* Command Pattern
* State Pattern
* Dependency Injection examples
* SOLID Principles
* Real-world mini projects demonstrating multiple design patterns together

---

## Purpose

This repository serves as a personal learning resource and reference while studying Object-Oriented Programming and Software Design Patterns in Python. Each notebook focuses on a specific concept with simple examples to build intuition before applying these patterns to larger software projects.
