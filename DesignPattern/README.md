    # Design Patterns
    
    Design Pattern: Design pattern is a general repeatable solution to a commonly occurring problem in software design.
    
    Types of design pattern:
        A. Creational Pattern: ~ is a way to create new objects which increases the flexibility and reusability of existing code.
        B. Structural Pattern: ~ is a way to assemble objects and classes into a large structure which keeps the structure flexible and efficient.
        C. Behavioral Pattern: ~ is a way to communicate between objects and the assignment of responsibilities between objects.
        D. Concurrency Pattern:
      
        A.Creational Pattern:
          1. Abstract Factory: Abstract Factory is a creational design pattern which provides an interface for creating families of related or 
              dependent objects without specifying their concrete classes.
	      // ~ is a creational design pattern which creates factory method.
          2. Factory: Factory method is a creational design pattern which provides an interface for creating an object but let the subclasses decide which class
              to instantiate.
	     // ~ is a creational design pattern which creates another object. Also known as Virtual Constructor.
          3. Builder: Builder is a creational design pattern which separates the construction of a complex object from its representation so that 
              the same construction process can create different representations.
          4. Lazy Initialization: Lazy Initialization is a way to delaying initialization of resources or objects until they’re actually needed to 
	  	improve performance and save system resources. 
          5. Singleton: Singleton is creational design pattern which creates one instance of a class in the duration of runtime.
          6. Prototype: Prototype is creational design pattern that lets you copy existing objects without making your code dependent on their classes.
      
        B. Structural Patter:
          1. Adapter: The Adapter pattern is a design pattern which converts the interface of a class into another interface clients expect.
              It is often used to make existing classes work with others without modifying their source code.
	      //Adapter pattern lets you wrap an otherwise incompatible object in an adapter to make it compatible with another class.
          2. Decorator: The Decorator pattern is a design pattern which gives to add new functionality to an existing object without altering its stucture.
          3. Facade: Facade is a structural design pattern which gives us a simplified interface of a complex sub system.
          4. Bridge: Bridge is a structural design pattern that decouples an abstraction from its implementation so that the two can vary independently.
		//Bridge is a structural design pattern that lets split a large class or a set of closely related classes into two separate hierarchies—abstraction and 
	  	implementation—which can be developed independently of each other.
          5. Proxy: Proxy is a structural design pattern which provides a substitute or placeholder for another object.
          6. Flyweight: Flyweight is a structural design pattern that allows programs to support vast quantities of objects by keeping their memory consumption low.
          7. Composite: Composite is a structural design pattern that allows composing objects into a tree-like structure and work with it as a singular object.
          
        C.Behavioral Pattern: 
          1. Chain of Responsibility: Chain of Responsibility is a behavioral design pattern that lets us pass requests along a chain of handlers.
              Upon receiving a request, each handler decides either to process the request or to pass it to the next handler in the chain.
          2. Strategy Pattern: Strategy Pattern is a design pattern in which a class behavior or its algorithm can be changed at run time.
              //Define a family of algorithms, put each of then into a separate class and make their objects interchangeable.
          3. Iterator: Iterator is a behavioral design pattern that lets us traverse elements of a collection without exposing its underlying representation.
          4. Observer: Observer is a behavioral design pattern that lets us define a subscription mechanism to notify multiple objects about any events that
              happen to the object they're observing. //When one object change its state, all dependent objects are notified & updated automatically(Event-Subscriber-Listener).
          5. State: State is a behavioral design pattern that lets an object to alter its behavior when its internal state changes.
          6. Command: Command is a behavioral design pattern that converts a request into a stand-alone object that contains all information about the request.
          7. Template: Template is a behavioral design pattern that allows to define a skeleton of an algorithm in a base class and let subclasses override the steps without
	  	changing the overall algorithm’s structure.
          8. Visitor: Visitor is a behavioral design pattern that allows adding new behaviors to existing class hierarchy without altering any existing code.
          9. Interpreter: 
          10. Mediator: Mediator is a behavioral design pattern that defines an object that encapsulates how a set of objects interact. It reduces the coupling between the
		classes communicating with each other.
          11. Memento: Memento pattern is a behavioral design pattern that provides the ability to restore an object to its previous state (undo via rollback).
          
    * The main difference between a "factory method" and an "abstract factory" is that the factory method is a single method, and an abstract factory is an object.    
    Coupling: Coupling means the degree of one module depend on other module.
      	$storage = new Storage();
      	$user->new User($storage);//$user depend on $storage//
      	
    Dependency Injection: Dependency Injection is where components are given through their constructor,method or directly into field as a dependency.
      	//storage components gives as constructor to user. 
	
    Dispatch: Dispatch is a process of select a method at run time.
	  Trait: Trait is simply a group of methods that you want include within another class. A Trait, like an abstract class, cannot be instantiated on it’s own.
