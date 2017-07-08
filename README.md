# Head First Design Patterns 
## by Eric Freeman & Elisabeth Robson 
I've also included notes from *Design Patterns* by the GOF and *Clean Code* by Uncle Bob.
This is a really great book.  10/10 would buy again.  

## Code
Code and notes are in `/src/designpatterns/<pattern>/`
as well as basics and principles for OO design :smiley: 

## Index (follow along with the book)
1) [Object Oriented Programming Basics](./src/headfirst/OoBasics.md)
2) [Design Principles](./src/headfirst/designprinciples.md)
3) Design Patterns! 
    1. [Strategy](./src/headfirst/designpatterns/strategy/strategy.md)
    2. [Observer](./src/headfirst/designpatterns/observer/observer.md)
    3. [Decorator](./src/headfirst/designpatterns/decorator/decorator.md)
    4. [Factory](./src/headfirst/designpatterns/factory/factory.md)
    5. [Singleton](./src/headfirst/designpatterns/singleton/singleton.md)
    6. [Command](./src/headfirst/designpatterns/command/command.md)
    7. [Adapter](./src/headfirst/designpatterns/adapter/adapter.md)
    8. [Facade](./src/headfirst/designpatterns/facade/facade.md)
    9. [Template Method](./src/headfirst/designpatterns/templatemethod/templatemethod.md)
    10. [Iterator](./src/headfirst/designpatterns/iterator/iterator.md)
    11. [Composite](./src/headfirst/designpatterns/composite/composite.md)
    12. [State](./src/headfirst/designpatterns/state/state.md)
    13. [Proxy](./src/headfirst/designpatterns/proxy/proxy.md)
    14. [Compound Patterns (MVC)](./src/headfirst/designpatterns/combined/mvc.md)
    15. [Misc Patterns](./src/headfirst/designpatterns/miscpatterns.md)
        * Bridge
        * Builder 
        * Chain of Responsibility 
        * Flyweight 
        * Interpreter 
        * Mediator 
        * Memento 
        * Prototype 
        * Visitor 

## To run from command line (bash)

1. `cd` into `Head-First-Design-Patterns/src` directory 
2. compile java files in directory with `javac headfirst/designpatterns/<dir_name>/*.java`
3. run file with `java headfirst.designpatterns.<dir_name>.<class_name>`

#### e.g. to run strategy/MiniDuckSimulator

1. `cd Head-First-Design-Patterns/src`
2. `javac headfirst/designpatterns/strategy/*.java`
3. `java headfirst.designpatterns.strategy.MiniDuckSimulator`

----
*Original README below* : 


# Head First Design Patterns (2014 update)

I have recently updated all the code for Head First Design Patterns to be compatible
with Java 8. This new code accompanies an update for the book, released in July, 2014.

Download the code and compile and run from the command line, or load the code into 
project in Eclipse (Kepler, with the Java 8 beta patch).

https://wiki.eclipse.org/JDT/Eclipse_Java_8_Support_For_Kepler


Other links for the book are available on the book page at <a href="http://wickedlysmart.com/head-first-design-patterns/">wickedlysmart.com</a>.
