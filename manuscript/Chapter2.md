# Chapter 2 : Foundations


## Object Oriented Programming

### Encapsulation
Encapsulation comes from the verb *encapsulate*, which means "to enclose or be enclosed in or as if in a capsule" [^Collins2009]. This properly describes the concept of encapsulation in object oriented programming. The principle of encapsulation motivates us to keep together data and the logic operates on it. 

By consolidating (I mean, encapsulating) the logic and data, we can hide some of the data or logic from the outside world since it is only needed by the logic inside the encapsulation. By hiding these details, the system as a whole becomes easier to understand and maintain. This is why encapsulation is sometimes referred to as "information hiding".

In OO programming, you encapsulate logic and data into objects. An object consists of data (properties/fields/etc) and logic (functions/methods). Some of the properties and fields are public, meaning they can be seen and accessed from code outside the object. However, some are private--only accessible by code running inside the object. 

The principle of encapsulation suggests that we make private any methods or data that are only used by logic inside the object. Only make public anything that needs to be accessible by logic outside the object.

Let's look at an example:
<example here>

[^Collins2009]: Collins English Dictionary - Complete & Unabridged 10th Edition; 2009 © William Collins Sons & Co. Ltd. 1979, 1986 © HarperCollins Publishers 1998, 2000, 2003, 2005, 2006, 2007, 2009

http://en.wikipedia.org/wiki/Information_hiding
“The hiding of design decisions in a computer program that are most likely to change” - Wikipedia

### Polymorphism
Replace an object of a class with an object of its subclasses
Abstraction
    Code against an interface, not implementation
    Depend on abstractions, not concretions

### Low Coupling / High Cohesion
Low Coupling
    Unit tests promote low coupling. Highly coupled code is difficult to test.
    Links
        Coupling And Cohesion on c2.com
            http://c2.com/cgi/wiki?CouplingAndCohesion
    “The degree to which each program module relies on each one of the other modules” – Wikipedia
        http://en.wikipedia.org/wiki/Coupling_(computer_science)
High Cohesion
    http://codebetter.com/blogs/jeremy.miller/pages/129542.aspx
    “A measure of how strongly-related and focused the various responsibilities of a software module are” - Wikipedia
        http://en.wikipedia.org/wiki/Cohesion_(computer_science)


## UML

### Class Diagrams

### Activity Diagrams

### Sequence Diagrams