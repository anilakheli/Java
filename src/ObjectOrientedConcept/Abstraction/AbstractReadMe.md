# Java Abstraction

### Abstract Classes and Methods

Data **abstraction** is the process of hiding certain details and showing only essential information to the user. it is the property by virtue of which only the essential details are displayed to the user. The trivial or the non-essential units are not displayed to the user.Ex: A car is viewed as a car rather than its individual components.
Data **Abstraction** may also be defined as the process of identifying only the required characteristics of an object ignoring the irrelevant details. The properties and behaviors of an object differentiate it from other objects of similar type and also help in classifying/grouping the objects.

Abstraction can be achieved with either abstract classes or interfaces. In java, abstraction is achieved by interfaces and abstract classes. We can achieve 100% abstraction using interfaces.

#### Abstract classes and Abstract methods :

1. An abstract class is a class that is declared with an _**abstract**_ keyword.
2. An abstract method is a method that is declared without implementation.
3. An abstract class may or may not have all abstract methods. Some of them can be concrete methods.
4. A method-defined abstract must always be redefined in the subclass, thus making overriding compulsory or making the subclass itself abstract.
5. Any class that contains one or more abstract methods must also be declared with an abstract keyword.
6. There can be no object of an abstract class. That is, an abstract class can not be directly instantiated with the new operator.
7. An abstract class can have parameterized constructors and the default constructor is always present in an abstract class.

###### **When to use abstract classes and abstract methods with an example**

There are situations in which we will want to define a superclass that declares the structure of a given abstraction without providing a complete implementation of every method. Sometimes we will want to create a superclass that only defines a generalization form that will be shared by all of its subclasses, leaving it to each subclass to fill in the details.

### **Encapsulation vs Data Abstraction**

Encapsulation is data hiding(information hiding) while Abstraction is detailed hiding(implementation hiding).
While encapsulation groups together data and methods that act upon the data, data abstraction deal with exposing the interface to the user and hiding the details of implementation.
Encapsulated classes are java classes that follow data hiding and abstraction while We can implement abstraction by using abstract classes and interfaces.
Encapsulation is a procedure that takes place at the implementation level, while abstraction is a design-level process.

Mostly, we don't know about the implementation class (which is hidden to the end user) and an object of the implementation class is provided by the factory method.
A factory method is a method that returns the instance of the class. We will learn about the factory method later.

**RULE**: IF we are extending an abstract class that has an abstract method, we myst either provide the implementation of the method or make this class abstract.
