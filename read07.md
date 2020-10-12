### Domain Modeling


_Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model._

> Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.
------------
### Creating and using constructors


> Constructors are like regular functions, but we use them with the new keyword. There are two types of constructors: built-in constructors such as Array and Object, which are available automatically in the execution environment at runtime; and custom constructors, which define properties and methods for your own type of object.

**A constructor is useful when you want to create multiple similar objects with the same properties and methods. It’s a convention to capitalize the name of constructors to distinguish them from regular functions. Consider the following code:** 

![domain](https://miro.medium.com/max/1724/1*uO_3V9tJ0ZD0LI-Hi7x2FA.png)


**Here's some tips to follow when building your own domain models.**

- When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
- Model its attributes with a constructor function that defines and initializes properties.
- Model its behaviors with small methods that focus on doing one job well.
- Create instances using the new keyword followed by a call to a constructor function.
- Store the newly created object in a variable so you can access its properties and methods from outside.
- Use the this variable within methods so you can access the object's properties and methods from inside.
-----------

### What is a table ?

_A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data. 

![table](https://flaviocopes.com/html-tables/no-styling.png)