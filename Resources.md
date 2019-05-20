## Quant developer interview resources
Guide for how to start preparing for Quant developer position: https://www.quantstart.com/articles/Self-Study-Plan-for-Becoming-a-Quantitative-Developer

### Clean code and the importance
Tips on writing clean code: https://www.investigatii.md/uploads/resurse/Clean_Code.pdf
 * Bad code is like being able to point out a bad painting, you get to know its bad only after seeeing examples of bad code.
 Good code characteristics (according to Bjarne stroustrup)
  1. elegant, efficient, straightforward logic (so that bugs can be avoided), 
  2. dependecies minimal to ease maintenance, 
  3. error handling, 
  4. performance close to optimal
  5. has unit test (high cohesion in one block) and acceptance test(Given-when-then for stakeholder sake)
  6. meaningful names for functions, classes, declaration.
  
### Design Patterns
* https://sophia.javeriana.edu.co/~cbustaca/docencia/DSBP-2018-01/recursos/Erich%20Gamma,%20Richard%20Helm,%20Ralph%20Johnson,%20John%20M.%20Vlissides-Design%20Patterns_%20Elements%20of%20Reusable%20Object-Oriented%20Software%20%20-Addison-Wesley%20Professional%20%281994%29.pdf
1. Each pattern describes a problem which occurs over and over again and describes the solution to the problem in a way that could be used
a million times without doing it same twice.
2. Popular and most used - Factory, Decorator, Singleton
3. Pattern has 4 elements
    * Pattern name (handle to describe a design problem)
    * Problem (when to apply the pattern)
    * Solution (elements that make up the design, relationships, responsibilties and collaboration)
    * consequences (reuslts and trade-offS)

4. MVC (model view controller)
   * model - underlying application data
   * view - different presentation of the same underlying data
   * controller - the way the user interacts with the user input.
5. Main types of patterns:
   * Creational patterns 
       - Abstract Factory : Provide interface for <b> creating families of related objects </b> without specifying their <b>concrete classes.</b>
       - Builder : Separate construction of complex object from representation.
       - Factory method: Define interface for object creation, but lets subclasses decide which  class to instantiate.
       - Prototype : Specify kinds of object to create using prototypical inheritance, creates new objects by copying this prototype.
       - Singleton : Ensure class has only one instance and provide global point of access.
    * Structural patterns
       - Adapter : Convert interface of one class to another, lets classes work together that couldnt work otherwise.
       - Bridge : Decouple abstraction from implementation.
       - Composite : Compose object into tree structure - part whole hierarchies.
       - Decorator: attach additional responsibilities to object dynamically.
       - Facade : provide unified interface to set of interfaces in subsystem.
       - Flyweight : use sharing to support large numbers of fine grained objects efficiently.
       - Proxy : provide surrogate/placeholder for another object to control access to it.
   * Behavioral patterns
       - Chain of responsibility
       - Command
       - Interpreter
       - Iterator
       - Mediator
       - Observer
       - Template method
       - Visitor
       
  ##### REST API
  REST - Representational state transfer API is an application program interface that uses HTTP requests to GET, POST, PUT and DELETE data. It is an architectural style for distributed hypermedia systems.
  Guiding principles of REST
  1. Client-server: Separate user interface concerns from the data storage concerns.
  2. Stateless - Request from client must contain all information to understand request. No usage of stored context on server. Hence session state is kept entirely on client.
  3. Cacheable : 
  
