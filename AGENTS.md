# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code development for the AGENTS repository. Adherence to these principles is crucial for long-term success.

## 1. DRY (Don't Repeat Yourself)

*   All code should have single, well-defined responsibilities.
*   Avoid duplication of logic, data structures, and functionality.
*   When a feature requires adaptation, create a new module or class instead of modifying existing code.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for the simplest possible solution that meets the requirements.
*   Avoid unnecessary complexity.
*   Prioritize clarity and readability over theoretical optimization.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module/component should have one primary responsibility.
*   **Open/Closed Principle:**  The system should be extensible through public interfaces without modifying the internal code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on interfaces they do not use.
*   **Dependency Inversion Principle:** Client code should not depend on implementation details; instead, they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement features that are currently needed.
*   Refactor and improve code as needed, rather than adding functionality that is not currently required.
*   Don’t introduce “just in case” logic.

## 5. Code Structure and Organization

*   **Modularization:** Break down the codebase into logical modules/components.
*   **Naming Conventions:** Follow established naming conventions (e.g., camelCase, snake_case).
*   **Comments:**  Provide clear and concise comments explaining complex logic, assumptions, and design choices.  Don't comment on obvious code.
*   **Documentation:**  Use docstrings to document classes, functions, and modules.
*   **Clear Code Flow:**  Ensure code flows logically and is easy to follow.
*   **Error Handling:** Implement robust error handling and logging.
*   **Data Structures:** Choose appropriate data structures for the task; consider efficiency and readability.
*   **Unit Testing:** All code must be thoroughly unit tested.

## 6. Testing & Quality Assurance

*   **Unit Tests:** Write at least 80% of the code using unit tests.  Each function/class/module should have a corresponding test.
*   **Test Coverage:**  Ensure comprehensive test coverage (at least 80%).  Use a coverage tool to identify gaps.
*   **Test-Driven Development:** Write tests *before* implementation, if possible.
*   **Mocking:** Use mocks and stubs exclusively for testing.  Do not use real dependencies in tests.

## 7. File Size Limit

*   Each file must be no more than 180 lines of code.

## 8.  Project Standards

*   All code should adhere to the defined project style guide (available at [link to style guide]).
*   Consistent use of indentation and spacing.
*   Follow established coding conventions.

## 9.  Commit Strategy

*   Commit changes frequently and frequently.
*   Keep small, focused commits.
*   Write clear commit messages.

## 10.  Documentation of API Interfaces

*   Each class/module/component should have a clear API description.
*   Include API documentation using a tool like Swagger/OpenAPI.

## 11.  Dependency Management

*   Maintain a dependency management system (e.g., pip, maven, etc.) to track dependencies.
*   Regularly update dependencies to security vulnerabilities.


This document is intended to serve as a guiding framework.  Any deviations should be justified and discussed.  Continuous improvement and refinement of these guidelines are encouraged.