# Java Design Patterns

This repository contains Java implementations of several common design patterns. Each design pattern is implemented in its own package.

## Design Patterns Implemented

*   **Adapter:** Adapts the interface of an existing class to another interface that clients expect.
*   **Composite:** Composes objects into tree structures to represent part-whole hierarchies.
*   **Creational:** Deals with object creation mechanisms, trying to create objects in a manner suitable to the situation. This includes the Factory Method and Singleton patterns.
*   **Decorator:** Attaches additional responsibilities to an object dynamically.
*   **Observer:** Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
*   **Proxy:** Provides a surrogate or placeholder for another object to control access to it.

## Getting Started

### Prerequisites

*   Java Development Kit (JDK) 8 or higher
*   Gradle

### Building

To build the project, run the following command in the root directory:

```bash
./gradlew build
```

### Running the Tests

To run the tests, run the following command in the root directory:

```bash
./gradlew test
```

The test files in `src/test/java/com/edu/designPatterns/test/` demonstrate the usage of each design pattern.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
