# Object Oriented Programming
## Foundation
1.  <details>
    <summary>Shortly explain what is OOP.</summary>
    Object-oriented programming is a fundamental programming paradigm centered around the concept of classes and objects to enhance code organization, reusability, and maintainability.
    </details>

2.  <details>
    <summary>What are classes and instances in OOP?</summary>
    
    ### Class

    A class is a blueprint or a template for creating objects, defining a set of attributes (data) and methods (functions) that the created objects will have. 

    ### Instance
    While the class is the blueprint, an instance is an object that is built from a class and contains real data. An instance of the Dog class is not a blueprint anymore. It’s an actual dog with a name, like Miles, who’s four years old.
    </details>

3.  <details>
    <summary>Explain advantages of OOP</summary>

    * Flexibility to define customised data structures. 
    
    * Ability to standardise similar objects into a template. This helps making them more manageable.  
    </details>

4.  <details>
    <summary>Differences between class attributes and instance attributes</summary>

    * Class attributes are the attributes that all objects of the same class share. They are initialised to the same values at the time they are created.  
    
    * Instance attributes on the other hand are attributes of the specific instance.

    * By default, both class and instance attributes are mutable after initialisation. All objects of same class have same set of attributes (but could be of different values)
    </details>

5.  <details>
    <summary>What are dunder methods?</summary>
    Dunder methods are methods that are (typically) called implicitly by the language, they start and end with double underscore for example `__init__` or `__str__`.  

    A nice [write up](https://mathspp.com/blog/pydonts/dunder-methods) about that. 
    </details>

### Inheritance

1.  <details>
    <summary>Explain inheritance</summary>
    * Inheritance is the process by which one class (child class) takes on the attributes and methods of another (parent class).
    
    * Child class can overwrite and or extend the attributes and methods of parent classes.
    
    * All object created from a child class are instances of the parent class. 
    </details>

1.  <details>
    <summary>What does `super().method()` do?</summary>
    * This is usually called inside the method of a child class, where the input arguments need some modification before it is passed to the given method of the parent class. 

    </details>