# 10-20-23---10-24-23
Continuing Text Based Games:

## A few Key Concepts:

A class is like a blueprint for creating an object.

To create an object using your class, you call a special method named the constructor. Instantiating an object of a class is a bit like saying, “Hey Python, you remember that blueprint I gave you? Well, I'd like you to use it to make an object.”

You need your object to have attributes; these are pieces of data stored inside the object. Assigning an object's attributes is a bit like taking several variables, each with its own name, and grouping them together with the object. Inside the constructor you define what attributes your object has and what their starting values will be. In your game so far, each room object has a name, a description, and a dictionary of the rooms linked to it.

The object must also have methods — ways for you to tell it what to do. Imagine writing methods as taking several functions, each with its own name, and making them available for use on the object. So inside the class, you define various methods for interacting with the object. In your example, you defined some getters and setters, and also methods to move between rooms and print out the details of each room.

Finally, each object you create is called an instance of its class, so each room object you made was an instance of Room.


## A few Key Words:


Constructor: a special method to tell Python how to create an object of this class: in Python, the constructor method is always called __init__ with a double underscore on each side of ‘init'

Dictionary: similar to a list, but allows you to give each element a name

Element: one item in a dictionary

Getter: a method whose purpose it is to get a value from within an object

Instantiate: create an object of a particular class

Parameter: a way of providing data so that it can be used within a method

Self: used within the code for an object to mean ‘this object'

Setter: a method whose purpose it is to set an attribute within an object

Key points
When you create a subclass, that class will inherit all of the attributes and methods from the superclass. You used inheritance to extend a class written by somebody else, customising it and overriding its methods as necessary. Moreover, inheritance is also useful because it allows you to write code only once in a base class, and then extend that code with subclasses. It therefore helps you to avoid code duplication.

Polymorphism allows us to treat a subclass as if it were an object of the superclass, and yet still have the subclass behave differently. You saw this demonstrated where you wrote some code for a character object, and then successfully used the same code on an enemy object. This was possible because Enemy is a subclass of Character.

When an object contains another object, you can describe their relationship with 'has a', and you call this aggregation. For example, your room object now has a character inside it. In practice, the object might be of the Character class or the Enemy class: because of polymorphism, an enemy is a character, and therefore it doesn't matter which type of object is used.

Next week, you will investigate class variables and finish writing the game. You will also look at ways of sharing your code and making it easy for other people to use.


A Few Key Terms
Aggregation: when an object contains an instance of (or ‘has a') another object

Extend: a class that uses the functionality of an existing class, but also adds to or overwrites some of it

Inherit: a class that inherits from another class is able to use all of the attributes and methods from that class

Polymorphism: if a class inherits from another class, it can also be considered to be (‘is a') object of that class, but can behave differently

Subclass: inherits the properties of another class and adds some specialised methods of its own

Superclass: provides methods and attributes that are used by another class
