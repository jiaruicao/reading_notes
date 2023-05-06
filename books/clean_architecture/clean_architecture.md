# Clean Architecture by Robert C. Martin: Key Takeaways


# table of contents
- [Clean Architecture by Robert C. Martin: Key Takeaways](#clean-architecture-by-robert-c-martin-key-takeaways)
  - [Chapter 1: What Is Design and Architecture?](#chapter-1-what-is-design-and-architecture)
  - [Chapter 2: A Tale of Two Values](#chapter-2-a-tale-of-two-values)
  - [Chapter 3: Paradigm Overview](#chapter-3-paradigm-overview)
  - [Chapter 4: Structured Programming](#chapter-4-structured-programming)
  - [Chapter 5: Object-Oriented Programming](#chapter-5-object-oriented-programming)
  - [Chapter 6: Functional Programming](#chapter-6-functional-programming)
  - [Chapter 7: SRP: The Single Responsibility Principle](#chapter-7-srp-the-single-responsibility-principle)
  - [Chapter 8: OCP: The Open-Closed Principle](#chapter-8-ocp-the-open-closed-principle)
  - [Chapter 9: LSP: The Liskov Substitution Principle](#chapter-9-lsp-the-liskov-substitution-principle)
  - [Chapter 10: ISP: The Interface Segregation Principle](#chapter-10-isp-the-interface-segregation-principle)
  - [Chapter 11: DIP: The Dependency Inversion Principle](#chapter-11-dip-the-dependency-inversion-principle)
  - [Chapter 12: The Dependency Rule](#chapter-12-the-dependency-rule)
  - [Chapter 13: Components](#chapter-13-components)
  - [Chapter 14: Component Cohesion](#chapter-14-component-cohesion)
  - [Chapter 15: Component Coupling](#chapter-15-component-coupling)
  - [Chapter 16: Architecture](#chapter-16-architecture)
  - [Chapter 17: The Main Component](#chapter-17-the-main-component)
  - [Chapter 18: The Database is a Detail](#chapter-18-the-database-is-a-detail)
  - [Chapter 19: The Web is a Detail](#chapter-19-the-web-is-a-detail)
  - [Chapter 20: The Clean Architecture](#chapter-20-the-clean-architecture)

## Chapter 1: What Is Design and Architecture?
- Design and architecture are about making intentional decisions that shape a system's structure and behavior.
- Good architecture enables the system to be easily understood, maintained, and modified over time.
- Architecture is the art of balancing competing forces, such as performance, maintainability, and scalability.

## Chapter 2: A Tale of Two Values
- The two primary values of software are behavior and structure.
- Behavior is what the system does, while structure is how the system is organized and how its components interact.
- Architecture is primarily concerned with structure, but structure should be designed to support the desired behavior.

## Chapter 3: Paradigm Overview
- There are several paradigms for structuring software, including structured programming, object-oriented programming, and functional programming.
- Each paradigm has its own strengths and weaknesses, and the choice of paradigm should be guided by the requirements of the system and the preferences of the development team.

## Chapter 4: Structured Programming
- Structured programming emphasizes the use of control structures, such as loops and conditionals, to create clear and easy-to-understand code.
- Good structured programming requires clear and meaningful names, small and focused functions, and careful handling of control flow.

## Chapter 5: Object-Oriented Programming
- Object-oriented programming emphasizes the use of objects to represent the entities and behaviors of the system.
- Good object-oriented design requires a clear understanding of the responsibilities of each object and the relationships between them.

## Chapter 6: Functional Programming
- Functional programming emphasizes the use of pure functions, which have no side effects and return a value based only on their input parameters.
- Good functional programming requires a clear separation of pure and impure code, and careful handling of state.

## Chapter 7: SRP: The Single Responsibility Principle
- The Single Responsibility Principle (SRP) states that a module or class should have only one reason to change.
- Violating the SRP can lead to code that is difficult to understand, maintain, and modify over time.

## Chapter 8: OCP: The Open-Closed Principle
- The Open-Closed Principle (OCP) states that software entities (classes, modules, etc.) should be open for extension but closed for modification.
- Good software design should allow new functionality to be added without modifying existing code.

## Chapter 9: LSP: The Liskov Substitution Principle
- The Liskov Substitution Principle (LSP) states that objects of a superclass should be substitutable for objects of a subclass without affecting the correctness of the program.
- Violating the LSP can lead to unexpected behavior and make the code difficult to understand and maintain.

## Chapter 10: ISP: The Interface Segregation Principle
- The Interface Segregation Principle (ISP) states that clients should not be forced to depend on methods they do not use.
- Good software design should provide small and focused interfaces that are tailored to the needs of each client.

## Chapter 11: DIP: The Dependency Inversion Principle
- The Dependency Inversion Principle (DIP) states that high-level modules should not depend on low-level modules; both should depend on abstractions.
- Good software design should separate the high-level policy from the low-level details.

## Chapter 12: The Dependency Rule
- The Dependency Rule states that source code dependencies should only point inwards, towards higher-level policies and abstractions.
- Violating the Dependency Rule can lead to code that is difficult to understand, maintain, and modify over time.

## Chapter 13: Components
- Components are independent units of software that can be replaced or upgraded without affecting the rest of the system.
- Good component design requires clear interfaces, well-defined boundaries, and separation of concerns.

## Chapter 14: Component Cohesion
- Component cohesion refers to the degree to which the responsibilities of a component are related and focused.
- Good component design should strive for high cohesion, which leads to code that is easier to understand, maintain, and modify over time.

## Chapter 15: Component Coupling
- Component coupling refers to the degree to which a component depends on other components.
- Good component design should strive for low coupling, which leads to code that is more flexible, reusable, and testable.

## Chapter 16: Architecture
- Architecture is the organization of a system's components and their relationships, with an emphasis on meeting the system's functional and non-functional requirements.
- Good architecture requires a clear understanding of the system's goals, constraints, and stakeholders.

## Chapter 17: The Main Component
- The Main Component is the top-level component of a system, responsible for orchestrating the interactions between the other components.
- Good Main Component design requires a clear understanding of the system's functional and non-functional requirements, and the ability to evolve as those requirements change over time.

## Chapter 18: The Database is a Detail
- The database is an implementation detail that should be hidden behind an abstraction layer.
- Good database design requires a clear understanding of the system's data needs and the ability to change the database schema without affecting the rest of the system.

## Chapter 19: The Web is a Detail
- The web is an implementation detail that should be hidden behind an abstraction layer.
- Good web design requires a clear understanding of the system's interaction with the web, and the ability to evolve as web technologies and standards change over time.

## Chapter 20: The Clean Architecture
- The Clean Architecture is a layered architecture that separates the concerns of the system into different layers, with clear boundaries and well-defined interfaces.
- Good Clean Architecture design requires a clear understanding of the system's goals and requirements, and the ability to evolve as those requirements change over time.
