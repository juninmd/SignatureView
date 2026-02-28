```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the creation and maintenance of high-quality, maintainable, and reliable AI coding agents. Adherence to these principles is mandatory for all development activities.

## 1. DRY (Don't Repeat Yourself)

*   **Module Design:** Each module should have a single, well-defined purpose. Avoid creating redundant code blocks.
*   **Function Reusability:** Implement functions and classes that fulfill similar requirements across multiple files.
*   **Abstraction:** Introduce abstract classes and interfaces to decouple concerns and facilitate code reuse.
*   **Single Responsibility Principle:** Each class/module should have one primary responsibility.

## 2. KISS (Keep It Simple, Stupid)

*   **Code Clarity:** Prioritize readability and understandability.  Use meaningful variable and function names.
*   **Minimal Complexity:**  Keep functions and classes concise and avoid unnecessary complexity.
*   **Early Error Handling:**  Implement basic error handling where appropriate, but avoid excessive logging or complex error management.
*   **Simple Logic:**  Favor straightforward logic over convoluted algorithms.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have only one reason to change.
*   **Open/Closed Principle:**  The system should be extensible through the addition of new features without modifying existing code.  (This is less directly applicable to code agents, but important for design.)
*   **Liskov Substitution Principle:**  Subclasses must be substitutable for their base classes without altering the correctness of the program. (This doesn’t apply to code agents, but relates to the design.)
*   **Interface Segregation Principle:** Each client-supplier interface should have no more dependencies (interfaces) than necessary.
*   **Dependency Inversion Principle:** High-level modules should be dependent on their specific interface, not their concrete implementations.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Don’t implement functionality that is not currently required.  Refactor and remove code as needed.
*   **Focus on Requirements:** Write code that directly addresses the stated requirements, not potential future requirements.
*   **Keep it Lightweight:**  Avoid adding features or complexity that aren’t immediately necessary.

## 5. Development Practices

*   **Code Reviews:** All code changes must be reviewed by at least one other developer before merging.
*   **Unit Testing:** All significant code changes must be thoroughly tested through unit tests.
*   **Static Analysis:** Utilize static analysis tools to identify potential issues and enforce coding standards.
*   **Documentation:**  Include comments explaining complex logic or design decisions.
*   **Version Control:**  Use a version control system (e.g., Git) and follow established branching strategies.
*   **Code Style:**  Adhere to a consistent code style guide (e.g., PEP 8 for Python).

## 6. Production-Ready Code

*   **Error Handling:** Implement robust error handling to prevent crashes and provide informative error messages.
*   **Logging:** Use logging for debugging and monitoring purposes, but avoid excessive logging.
*   **Data Validation:**  Validate input data to prevent invalid or unexpected behavior.
*   **Performance Considerations:**  While not a primary focus, consider potential performance bottlenecks and optimize code where necessary.

## 7. Code Length Constraint

*   **Maximum Lines:** Each file should be no more than 180 lines of code.

## 8. Test Coverage Requirements

*   **Target:** 80% minimum test coverage.  Test cases should cover all critical paths and edge cases.

## 9.  Specific Considerations for AI Coding Agents

*   **State Management:**  Clearly define how the agent's state is managed and updated.
*   **Model Loading:**  The system must gracefully handle model loading and initialization.
*   **Data Handling:**  Implement safe and secure data handling practices, including encryption and access control.
*   **API Design:** Ensure API design is sound and scalable for future expansion.



These guidelines are intended as a foundation and should be adapted to specific project requirements. Regular review and updates are important to ensure continued adherence to best practices.
```