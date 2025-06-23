# Design Patterns vs. SOLID Principles

## Key Differences

| Aspect | Design Patterns | SOLID Principles |
|--------|----------------|------------------|
| **Definition** | Reusable solutions to common software design problems | Principles for creating maintainable and extensible object-oriented software |
| **Purpose** | Provide templates for solving specific implementation challenges | Guide overall software design philosophy |
| **Scope** | Tactical solutions to specific problems | Strategic guidelines for overall code structure |
| **Origin** | Documented by Gang of Four (GoF) in their 1994 book | Introduced by Robert C. Martin (Uncle Bob) in early 2000s |
| **Nature** | Concrete implementations | Abstract principles |
| **When to Apply** | When facing a known recurring problem | Throughout the entire development process |

## Design Patterns

Design patterns are specific, proven solutions to common software design problems. They are like templates that can be applied to solve particular challenges.

### Examples:
- **Singleton**: Ensures a class has only one instance
- **Factory**: Creates objects without specifying the exact class
- **Observer**: Defines a one-to-many dependency between objects
- **Strategy**: Defines a family of algorithms and makes them interchangeable

## SOLID Principles

SOLID is an acronym for five design principles that help make software more maintainable and extensible.

- **S - Single Responsibility Principle**: A class should have only one reason to change
- **O - Open/Closed Principle**: Software entities should be open for extension but closed for modification
- **L - Liskov Substitution Principle**: Subtypes must be substitutable for their base types
- **I - Interface Segregation Principle**: Clients should not be forced to depend on interfaces they don't use
- **D - Dependency Inversion Principle**: High-level modules should not depend on low-level modules; both should depend on abstractions

## How They Work Together

Design patterns often implement SOLID principles:
- The **Strategy Pattern** follows the Open/Closed Principle by allowing new strategies to be added without modifying existing code
- The **Decorator Pattern** follows the Single Responsibility Principle by separating core functionality from additional features

## In Practice

- SOLID principles guide your overall architecture and class design
- Design patterns provide specific implementations to solve common problems within that architecture
- Following SOLID principles often leads to recognizable design patterns emerging naturally in your code

Think of SOLID principles as the "rules" for good object-oriented design, while design patterns are specific "tools" you can use to follow those rules in particular situations.
