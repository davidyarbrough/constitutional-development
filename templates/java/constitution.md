# Java Project Constitution

## Core Principles

1. This constitution governs all code and documentation in this repository
2. All developers and AI assistants must follow these rules
3. The repository maintainer has final authority on all changes

## Java-Specific Standards

### Code Organization

1. Follow standard Java package naming conventions (e.g., `com.company.project`)
2. Each class must reside in its own file with matching name
3. Use meaningful package structure that reflects the application's architecture
4. Keep source files in `src/main/java` and tests in `src/test/java`

### Code Style

1. Follow Oracle's Java Code Conventions
2. Use camelCase for method and variable names
3. Use PascalCase for class and interface names
4. Use UPPER_SNAKE_CASE for constants
5. Prefix interface names with 'I' only when there is a single implementation

### Best Practices

1. Favor composition over inheritance
2. Program to interfaces, not implementations
3. Follow SOLID principles
4. Use dependency injection where appropriate
5. Make classes final by default unless designed for inheritance
6. Make fields private by default
7. Avoid raw type usage with generics

### Exception Handling

1. Never catch Exception without proper handling
2. Use unchecked exceptions for programming errors
3. Document all checked exceptions in Javadoc
4. Include appropriate context in exception messages

### Testing

1. Write unit tests using the latest version of JUnit
2. Maintain minimum 80% code coverage
3. Use meaningful test names that describe the scenario
4. Follow AAA pattern (Arrange, Act, Assert)
5. Use mocking frameworks judiciously

### Documentation

1. Use Javadoc for all public APIs
2. Include package-info.java for package documentation
3. Document non-obvious implementation decisions
4. Keep documentation close to the code it describes

### Build and Dependencies

1. Use Maven or Gradle for dependency management
2. Pin dependency versions explicitly
3. Regularly update dependencies for security
4. Maintain a clean and organized build file

## Quality Assurance

1. Run static analysis tools (e.g., SpotBugs, PMD)
2. Use checkstyle for style enforcement
3. Run tests before committing code
4. Address compiler warnings

## Amendments

1. Constitutional changes require maintainer approval
2. Approved changes take effect immediately
