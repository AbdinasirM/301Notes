notes from the Chapter 1 and C++ interlude 1: 
1.Encapsulation:

Definition: Encapsulation is a way of organizing code by bundling data (variables) and the methods that operate on the data within a single unit (class). It restricts direct access to some of an object's components and only allows access through designated methods.
In simple terms: Think of it like putting data in a secure box (class) with a lock (private access). The box provides methods (keys) to interact with the data, controlling how it's accessed and modified.

2. Polymorphism:

Definition: Polymorphism allows objects of different types to be treated as objects of a common type. In programming, it often involves inheriting methods from a base class and providing specific implementations in derived classes.
In simple terms: Consider using a universal remote control (base class) to operate different brands of TVs (derived classes). Each TV may respond differently to the same button press.
Abstraction:

Definition: Abstraction is the process of hiding complex implementation details and showing only the necessary features of an object. It often involves creating abstract classes that define essential methods without specifying their detailed implementations.
In simple terms: It's like having a blueprint for a car that outlines the essential features (wheels, engine) without specifying the brand of tires or the type of engine.

3. Inheritance:

Definition: Inheritance is a mechanism in which a new class (derived class) inherits properties and behaviors from an existing class (base class). It promotes code reuse and allows the creation of specialized classes based on a general template.
In simple terms: Think of having a master template (base class) for an object and creating specific versions (derived classes) by inheriting and modifying the template.

4. typedef:

Definition: typedef is used in some programming languages, including C++, to create aliases (nicknames) for existing data types. It provides a way to simplify complex type names.
In simple terms: It's like giving a nickname to a data type – saying, "Instead of calling it 'int,' I'll call it 'myInt.'"

5. Template:

Definition: Templates in programming allow the creation of generic classes or functions that can work with multiple data types. They provide flexibility by allowing code to be written without specifying the exact data type.
In simple terms: Imagine creating a versatile tool that can adapt to different shapes or sizes – a generic plan (template) that accommodates various situations.


6. Header File and Implementation File Descriptions:

Header File: A header file in C++ (with .h or .hpp extension) contains declarations, such as class definitions and function prototypes. It acts as a reference, providing an interface to other parts of the code and promoting organization and reusability.

Implementation File: An implementation file in C++ (with .cpp extension) contains the actual code or implementation of functions and methods declared in the corresponding header file. It encapsulates the logic and behavior, keeping the details separate from the declarations for better code management.
