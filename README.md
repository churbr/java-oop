# The 6 Fundamental concepts of OOP:
- Objects
- Classes
- Abstraction
- Encapsulation
- Inheritance
- Polymorphism

## Objects
A *representation of a real-world entity*, it's like a general term for a thing.

e.g: _Person, Book, Place, Animal, Product etc._ 

_Anything that you want to store & process data about._

## Classes

To create an object, you need a Class. A class is a blueprint or template that defines the attributes & operations/behavior of an object. Put it simply, a class is a template for creating objects.

Inside a class, there are attributes and operations:

#### Attributes
Attributes describes the object, they sometimes refer to as fields. Because they contain data. Most developers know them as properties. 

*Example:*

We have a class of a Person, and we know that a person has firstname, middlename, and lastname, gender, date of birth and occupation, etc. These informations are called *attributes/fields/properties* of the Person class.
<br />

#### Operations

Operations are actions that can be done to or perform to an object. They sometimes referred to as behaviors, but more commonly methods.

*Example:*

Let's say we have a class of a Person, and we know that a person has information like firstname, lastname, occupation, etc. We want to save the person's information, and we can update it too.

There's also occupation in the attributes, so this person could be an employee. If it's an employee, we can pay the person wage and give a promotion.

With that said, we now have an idea of what operation to put in this class. We will translate these operations from common language to code. See table below:

| Common Language | Code (Methods) |
| --- | --- |
| Save the person's information | ```saveInfo()``` |
| Update the person's information | ```updateInfo()``` |
| Pay the person wage | ```payWage()``` |
| Give a promotion | ```setPromotion()``` |