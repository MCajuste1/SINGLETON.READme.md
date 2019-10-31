# SINGLETON.READme.md

Java Singleton Pattern is one of the Gangs of Four Design patterns and comes in the Creational Design Pattern category.

Singleton pattern restricts the instantiation of a class and ensures that only one instance of the class exists in the java virtual machine.

Singleton design pattern is used in core java classes also, for example java.lang.Runtime, java.awt.Desktop.

Private constructor to restrict instantiation of the class from other classes.

Singleton pattern implementation
- Eager intitalization
- Static block initialization
- Lazy initialization 
- Thread Safe Singleton
- Enum Singleton

Public static method that returns the instance of the class, this is the global access point for outer world to get the instance of the singleton class.


Singleton is one class that can only have one object at a time per JVM instance.


Singleton is one of the 23 known "Gang of Four" design patterns.

Other classes would use a a constructor where as the singleton patterns uses a "getInstance method".
