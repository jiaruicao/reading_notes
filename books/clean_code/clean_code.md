# Clean Code

This is my personal kety takeaway on the book [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) by Robert C. Martin.

# table of contents
- [Clean Code by Robert C. Martin: Key Takeaways](#clean-code-by-robert-c-martin-key-takeaways)
  - [Chapter 1: Clean Code](#chapter-1-clean-code)
  - [Chapter 2: Meaningful Names](#chapter-2-meaningful-names)
  - [Chapter 3: Functions](#chapter-3-functions)
  - [Chapter 4: Comments](#chapter-4-comments)
  - [Chapter 5: Formatting](#chapter-5-formatting)
  - [Chapter 6: Objects and Data Structures](#chapter-6-objects-and-data-structures)
  - [Chapter 7: Error Handling](#chapter-7-error-handling)
  - [Chapter 8: Boundaries](#chapter-8-boundaries)
  - [Chapter 9: Unit Tests](#chapter-9-unit-tests)
  - [Chapter 10: Classes](#chapter-10-classes)
  - [Chapter 11: Systems](#chapter-11-systems)
  - [Chapter 12: Emergence](#chapter-12-emergence)
  - [Chapter 13: Concurrency](#chapter-13-concurrency)
  - [Chapter 14: Successive Refinement](#chapter-14-successive-refinement)
  - [Chapter 15: JUnit Internals](#chapter-15-junit-internals)
  - [Chapter 16: Refactoring SerialDate](#chapter-16-refactoring-serialdate)

# Clean Code by Robert C. Martin: Key Takeaways

## Chapter 1: Clean Code
- The primary goal of software development is to create code that is easy to read and maintain.
- Good code is like a good joke: it needs to be well-timed, have a clear punchline, and be easy to understand.

## Chapter 2: Meaningful Names
- Names should be descriptive and convey the purpose and meaning of the variable, function, or class.
- Avoid using ambiguous, generic, or misleading names.

## Chapter 3: Functions
- Functions should be small, focused, and do one thing well.
- The name of a function should be a clear indication of what it does.
- Functions should have a limited number of arguments and should not have side effects.

## Chapter 4: Comments
- Comments should be used sparingly and only to explain why code is written the way it is.
- Good code should be self-explanatory, and comments should not be used to compensate for poorly written code.

## Chapter 5: Formatting
- Consistent formatting makes code easier to read and understand.
- Use consistent indentation, spacing, and line breaks.

## Chapter 6: Objects and Data Structures
- Objects should hide their implementation details and expose a clear and simple interface.
- Data structures should expose their data and have no significant behavior.

## Chapter 7: Error Handling
- Error handling code should be separated from the normal code path and handled in a consistent and uniform way.
- Use exceptions rather than error codes to handle errors.

## Chapter 8: Boundaries
- Code should be separated into distinct layers with clear boundaries.
- Avoid exposing implementation details across layers.

## Chapter 9: Unit Tests
- Unit tests should be written for every piece of code, and should be automated and run frequently.
- Tests should be small, focused, and cover all possible edge cases.

## Chapter 10: Classes
- Classes should be small, focused, and have a single responsibility.
- The dependencies between classes should be minimized.

## Chapter 11: Systems
- A system should be made up of smaller, independent components that can be easily understood and modified.
- A good architecture should allow for easy scalability and maintenance.

## Chapter 12: Emergence
- Good code emerges from a series of small, incremental changes.
- Code should be refactored frequently to improve its quality.

## Chapter 13: Concurrency
- Concurrency should be handled explicitly and with great care.
- Avoid shared data where possible, and use message passing between threads or processes.

## Chapter 14: Successive Refinement
- Good code is the result of a series of successive refinements.
- Start with a simple implementation and refine it over time.

## Chapter 15: JUnit Internals
- JUnit is a powerful tool for automated testing, and understanding its internals can help improve test quality and reliability.
- Tests should be designed to be repeatable and deterministic.

## Chapter 16: Refactoring SerialDate
- Refactoring is the process of improving code without changing its behavior.
- Refactoring can help improve code quality, readability, and maintainability.
