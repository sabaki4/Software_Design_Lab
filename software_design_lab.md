# Software Design

1. *What do we mean by coupling and cohesion when discussing structured design?*

In software design, the term coupling and cohesion is used to judge how well code is put together.

Coupling refers to how much one class relies on another - high coupling means if you change one class, it could mess up others. Low coupling means classes can stand alone without much impact from changes elsewhere.

Cohesion, on the other hand, is about how focused and clear the purpose of a class or method is. High cohesion means everything in a class or method works towards one goal. Low cohesion means it is doing different things that are not closely related.

The ideal code would have low coupling and high cohesion to make it more manageable and cleaner.

2. *What is the difference between top-down and bottom-up design? Which best describes a function oriented design?*

Top-down design begins by dissecting a large problem into smaller, more manageable modules through modularisation. This approach is characteristic of structured and function oriented designs, where the focus is on hierarchical decomposition.

Conversely, bottom-up design involves creating individual methods or components, which are then integrated to form the complete system or algorithm. This method is commonly associated with object oriented design, where smaller, reusable objects are developed and combined to construct larger systems.

3. *In which design methodology would a class diagram be most useful?*

A class diagram would be most useful in the Object Oriented Design methodology.


4. *What are the four pillars of object oriented programming? Give a single-sentence description of each.*

- **Encapsulation**: Involves restricting access to certain parts of an object's internal state by making properties private, enabling the object to control its own state.

- **Abstraction**: Refers to the process of hiding unnecessary details while exposing essential features, allowing methods to be called without needing to understand their inner workings.

- **Inheritance**: Allows objects to acquire properties and behaviors from other objects, fostering code reuse and hierarchical organisation.

- **Polymorphism**: Enables objects to take on multiple forms, allowing them to be treated as instances of their superclass while also possessing unique behaviors.


5. *What is the strategy pattern? How would its implementation differ between a functional and object oriented system?*

The Strategy Pattern, which is a behavioral design pattern, separates behaviors from objects, enabling the object's behavior to change dynamically at runtime.

In an Object Oriented system, this pattern adheres to the principles of programming to an interface, single responsibility of classes, and the open for extension but closed for modification rule. It's typically implemented using interfaces and concrete classes, allowing different algorithms to be encapsulated and swapped at runtime.

On the other hand, in a functional system, the implementation doesn't rely on interfaces or different classes. Instead, higher-order functions are used, allowing strategies to be represented as functions. This approach emphasises function composition and flexibility in changing behaviors at runtime.


6. *Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.*

In this case, I believe Object Oriented design for the online payment system would be best. With inheritance, code reusability is facilitated, while encapsulation ensures privacy of properties, allowing seamless adaptation for any type of indsutry using this online payment system. This approach promotes high cohesion, ensuring that each component maintains a single, well-defined purpose, while accommodating different types of purchases.