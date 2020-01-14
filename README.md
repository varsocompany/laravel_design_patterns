# Laravel Design Patterns

## About

This repository holds many resources related to the general information, use cases, implementation and reasoning behind multiple design patterns that are commonly used or can be applied to applications developed in the Laravel framework.

## What is a design pattern?

A design pattern is a known, used and tested architectural solution to an application design problem. Design patterns can be language/framework-agnostic, but within specific languages and frameworks they are adapted to leverage the specific features and behaviors exhibited by the technology.

The main advantage of design patterns is that they present a reusable and optimized solution to standard problems that show up in most software applications. The fact that they are abstracted solutions that can be easily adapted to the problem's custom specifics with ease implies that one need not waste time coming up with a solution to the same problem in a different application. To a trained software engineer, design patterns are virtually an extension of a language's control structures and particular statements, such as `if`, `else`, and `for`. Although design patterns are not actually features of a language, they still qualify as tools in the software engineer's toolbox.

### Examples of known design patterns

- Factory pattern
- Facade pattern
- Decorator pattern
- Singleton pattern

### Why we use design patterns

- Cleaner, standardized, more readable and maintainable code.
- Faster, more effective development.
- Easier, more direct debugging.
- Not re-inventing the wheel.
- We know when and where they work.

### Design Pattern type

#### Creational patterns

Creational patterns are used to build, insantiate, or otherwise create objects in ways that decouple their design from their representation. This can be achieved by either encapsulating the object creation process or by outsourcing it do a specialized class.

**Advantages provided by creational patterns:**

- Generic instantiation: Objects can be created without specifying the class type in code (reduces duplicated code).
- Simplicity: Object creation is made easier and cleaner when deletaged to specialized classes in accordance to each design pattern.
- Creation constraints: Creational patterns usually place constraints on who, how and when objects are created (more control of object instantiation)

**Examples of Creational patterns:**

- [Abstract Factory](/patterns/creational/abstract_factory.md)
- [Factory](/patterns/creational/factory.md)
- [Builder](/patterns/creational/builder.md)
- [Prototype](/patterns/creational/prototype.md)
- [Singleton](/patterns/creational/singleton.md)

#### Structural patterns

Structural patterns define simple and easy to follow ways of communicating amongst objects, classes and interfaces.

**Examples of Structural patterns:**

- [Composition](/patterns/structural/composition.md)
- [Decorator](/patterns/structural/decorator.md)
- [Facade](/patterns/structural/facade.md)
- [Proxy](/patterns/structural/proxy.md)

#### Behavioral patterns

Behavioral patterns deal with communication between objects specifically. They focus on "protocols" of communication and interaction between instantiated objects.

**Examples of Structural patterns:**

- [Command](/patterns/behavioral/command.md)
- [Iterator](/patterns/behavioral/iterator.md)
- [Mediator](/patterns/behavioral/mediator.md)
- [Strategy](/patterns/behavioral/strategy.md)
