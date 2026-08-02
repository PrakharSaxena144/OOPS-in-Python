# Object-Oriented Programming (OOP) Practice in Python

## Overview

This repository contains my hands-on practice of **Object-Oriented Programming (OOP)** concepts and commonly used **Design Patterns** in Python. The programs are written to strengthen the understanding of object-oriented principles through practical examples rather than large-scale applications.

The folder covers the implementation of core OOP concepts such as abstraction, encapsulation, inheritance, polymorphism, and several popular design patterns including **Decorator, Factory, Singleton, and Proxy**.

---

# Topics Covered

## 1. Decorators

Implemented function decorators to separate logging and monitoring logic from business logic.

### Features

* Function logging
* Generic decorators using `*args` and `**kwargs`
* Execution time monitoring
* Comparison of code with and without decorators

### Concepts Practiced

* Higher-order functions
* Wrapper functions
* Code reusability
* Cross-cutting concerns

---

## 2. Encapsulation

Demonstrates how Python supports encapsulation using public, protected, and private members.

### Features

* Public variables and methods
* Protected members (`_member`)
* Private members (`__member`)
* Private helper methods hidden behind public interfaces
* Student grade management example

### Concepts Practiced

* Data hiding
* Access control
* Information security
* Controlled object interaction

---

## 3. Abstract Classes (Abstraction)

Uses Python's `abc` module to create abstract base classes that define a common interface for derived classes.

### Example

* Vehicle
* Car
* Motorcycle

### Concepts Practiced

* Abstract Base Classes (ABC)
* `@abstractmethod`
* Interface implementation
* Runtime polymorphism

---

## 4. Factory Design Pattern

Implements a **Factory** that centralizes object creation instead of allowing the client to instantiate classes directly.

### Features

* Creates different vehicle objects
* Supports optional constructor parameters
* Hides object creation logic
* Easily extensible for future vehicle types

### Concepts Practiced

* Factory Method
* Loose coupling
* Centralized object creation
* Static factory methods

---

## 5. Singleton Design Pattern

Implements the Singleton pattern using the `__new__()` method to ensure only one object of a class exists.

### Example

Family hierarchy:

* Multiple Kid objects can be created.
* Only one Father object is allowed.

Even if another father object is requested with a different name, the previously created instance is returned.

### Concepts Practiced

* Singleton pattern
* Object lifecycle management
* Shared global instance
* Controlled initialization

### Real-world Use Cases

* Logger
* Database connection
* Configuration manager
* Cache manager
* Application settings

---

## 6. Proxy Design Pattern

Implements the **Proxy Design Pattern**, where a proxy object controls access to a real object by acting as an intermediary.

In this implementation, users interact with **CarProxy** instead of directly creating a **RealCar** object. The proxy performs authentication and authorization before allowing sensitive operations.

### Implementation

#### Vehicle Interface

Defines the common contract:

* `start_engine()`
* `drive()`
* `get_info()`

#### RealCar

Represents the actual object that performs the real operations.

Responsibilities:

* Stores car information
* Starts the engine
* Allows driving
* Displays vehicle information

#### CarProxy

Acts as a protective layer between the client and the real car.

Responsibilities:

* Lazily creates the `RealCar` object only when required.
* Verifies whether the driver is the owner before granting access.
* Delegates requests to the real object after successful authorization.
* Prevents unauthorized users from driving the vehicle.

### Features

* Authentication based on owner and driver identity
* Authorization before accessing protected operations
* Lazy initialization of the real object
* Transparent delegation to the actual implementation

### Concepts Practiced

* Proxy Design Pattern
* Access control
* Authentication
* Authorization
* Lazy object creation
* Object delegation

### Real-world Applications

* Login authentication systems
* Banking transaction authorization
* API gateways
* Payment gateways
* Cloud resource access
* File access permissions
* Database proxies
* Remote Proxy (RPC)
* Virtual Proxy for expensive object creation

---

# Python Concepts Practiced

* Classes and Objects
* Constructors (`__init__`)
* `__new__()`
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

# Folder Structure

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

# Learning Objectives

This repository was created to:

* Strengthen Object-Oriented Programming concepts.
* Learn commonly used software design patterns.
* Understand real-world applications of design patterns.
* Practice writing modular and maintainable Python code.
* Build a strong foundation for technical interviews and software engineering projects.

---

# Technologies Used

* Python 3.10+
* Jupyter Notebook

### Standard Libraries

* `abc`
* `time`

---

# Future Improvements

Planned additions include:

* Strategy Pattern
* Observer Pattern
* Builder Pattern
* Adapter Pattern
* Command Pattern
* State Pattern
* SOLID Principles
* Dependency Injection
* UML diagrams
* Real-world mini projects using multiple design patterns

---

# Purpose

This repository serves as a personal learning resource for mastering Object-Oriented Programming and Software Design Patterns in Python. Each notebook focuses on a specific concept with simple, practical examples that build intuition before applying these principles to larger software systems.
