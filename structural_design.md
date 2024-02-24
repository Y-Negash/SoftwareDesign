# STRUCTURAL DESIGN LAB 

**Q1 . What do we mean by coupling and cohesion when discussing structured design?**

Coupling describes how dependent one module is to another. For example, if editing one class changes another, this is considered tight coupling. Whereas, when modules are independent, it's considered loose coupling. 

On the other hand, cohesion looks within the modules and describes how cohesive the elements are to each other. If a module's elements are all related to a single responsibility, it is said to have high cohesion. The opposite is true for low cohesion. 


**Q2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?**

Top-down design starts with a design of the system first, that is then broken down into smaller parts. This process of starting from the top is then followed with the smaller parts until the whole system is designed. Whereas, starting the design from the smallest parts and working your way up, is coined as the bottom-up approach. 

For function oriented design, Top-down design would be better because working from the top would give a better understanding of the functions related to the system. High cohesion would also be easier to achieve as it would become clearer which functions should remain separate or be grouped together, depending on the module.


**Q3. In which design methodology would a class diagram be most useful?**

It would be more beneficial for the top down design, as it brings clarity on how and where the sub sections of the system should be divided. It is easier to start with the superclass and move down than it is to start with the smaller classes and move up, especially when the system is more complex.

It also helps to visualise the whole process as well as modify the classes to create high cohesion and loose coupling. Whereas, it would take more iterations to do the same for the bottom up design as it wouldn't be clear until you continue moving up in the design.


**Q4. What are the four pillars of object oriented programming? Give a single-sentence description of each.**

1. Abstraction

    Abstraction is to interact with an object without having to know how it works.

2. Encapsulation

    Encapsulation is to hide data from other parts of the program or those who aren't authorised to access it.

3. Inheritance

    This is when an object can inherit its functions and properties from another class.

4. Polymorphism

    This is when an object can take different forms depending on where in the inheritance chain, the object's datatype is called from.

**Q5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?**

The strategy pattern takes a method and puts it in an interface which is then implemented into sub-classes that do variations of that method. Using composition, the superclass and subclasses are then able to use the different variations of the method without modifying or overriding existing code. This is within the scope of an object oriented system, the same idea is true with functional oriented systems expect, rather than dealing with classes and interfaces, a function is passed in another function so that the method has different variations too. In both systems, using the strategy pattern promotes the open-closed principle.

**Q6. Imagine your creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.**

I would use the object oriented design and take the top-down approach because this would help me break down the overarching online payment system. Using class-diagrams, I would be able to filter down and visualise how the payment system can be divided into smaller objects. By abstracting away how the payments will be implemented, encapsulating data to decrease tight coupling, using composition over inheritance to allow the use of the strategy pattern and polymorphism to reduce DRY code, the final code would abide by all the SOLID principles. This would give me the advantage of creating code that won't be "tied to a particular sector". 

