---
title: "#2. Design patterns in a nutshell"
description: "Design patterns are ready-made solutions to common problems that can be encountered in object-oriented design. They show dependencies between classes and objects, enabling the creation of maintainable code."
pubDate: "Aug 28 2023"
heroImage: "/assets/posts/2023_08_28__design-patterns-in-a-nutshell.webp"
---

## Table of Contents

1. [What are Design Patterns?](#what-are-design-patterns)
2. [How to learn?](#how-to-learn)

## What are Design Patterns?

Design Patterns are _ready-made_ solutions to common problems that can be encountered in object-oriented design. They
show dependencies between classes and objects, enabling the creation of maintainable code. They were popularized in the
book _Design Patterns: Elements of Reusable Object-Oriented Software_ by the so-called Gang of Four (Eric Gamma, Richard
Helm, Ralph Johnson and John Vlissides).

However, when I write _ready-made_, I don’t mean something similar to libraries, that we can ~~mindlessly~~ throw into
our application and enjoy the solved problem. Nor is it an algorithm whose steps we can follow and get the desired
result. Design Patterns are similar to a strategy - we know the result and the assumptions, but we have to adjust the
implementation ourselves to get what we want.

Design Patterns are divided into:

- **Creational** - they present various mechanisms for creating objects that facilitate code reuse. They include:
    - Factory Method
    - Abstract Factory
    - Builder
    - Prototype
    - Singleton
- **Structural** - they explain how objects and classed can be assembled into larger structures, while maintaining the
  flexibility and efficiency of these structures. They include:
    - Adapter
    - Bridge
    - Composite
    - Decorator
    - Facade
    - Flyweight
    - Proxy
- **Behavioral** - deal with algorithms and the distribution of responsibilities among objects. They include:
    - Chain of Responsibility
    - Command
    - Iterator
    - Mediator
    - Memento
    - Observer
    - State
    - Strategy
    - Template Method
    - Visitor

[[Back to top]](#top)

## How to learn?

I suggest the following:

1. **Be sure you understand the basics.** There is no point in learning Design Patterns if you don't know
   object-oriented programming. If you are not sure what is the difference between a class and an object, what is
   inheritance, polymorphism - fill in the gaps, and then get into Design Patterns.
2. **Start with simple patterns.** My suggestions for getting started are Singleton, Factory Method, Builder.
3. **Books and online courses.** Where to learn? By reading my following posts. :-) The book mentioned above is a good
   source for learning. I also recommend the website [refactoring.guru](https://refactoring.guru/) which presents Design
   Patterns in an accesible and cool way, along with examples in code.
4. **Practice, practice, practice.** Create simple project using Design Patterns.
5. **Analyze, read, repeat.** Review code from open source that use Design Patterns. Rewrite existing code (maybe from
   old, first projects?) to include Design Patterns.
6. **Be patient.** You've probably heard it more than once, but I'll repeat it. This is a marathon, not a sprint.
   Everything comes with practice.

[[Back to top]](#top)
