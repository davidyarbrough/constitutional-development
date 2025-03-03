# Python Project Constitution

## Core Principles

1. This constitution governs all Python code and documentation in this repository
2. All developers and AI assistants must follow these rules
3. The repository maintainer has final authority on all changes

## Python-Specific Standards

### Code Organization

1. Follow the Python package structure
2. Use meaningful module names in snake_case
3. Keep modules focused and cohesive
4. Organize tests in a parallel structure to source code

### Code Style

1. Follow PEP 8 style guide
2. Use snake_case for functions and variables
3. Use PascalCase for class names
4. Use UPPER_SNAKE_CASE for constants
5. Maximum line length of 88 characters (Black default)

### Best Practices

1. Follow the Zen of Python (PEP 20)
2. Use type hints for function signatures
3. Make functions and classes as small as possible
4. Use list comprehensions judiciously
5. Prefer explicit over implicit
6. Use context managers (with statements) for resource management
7. Favor composition over inheritance

### Error Handling

1. Use exceptions rather than return codes
2. Create custom exceptions when appropriate
3. Handle exceptions at the appropriate level
4. Include context in error messages
5. Use finally blocks for cleanup

### Testing

1. Write tests using pytest
2. Maintain minimum 80% code coverage
3. Use fixtures for test setup
4. Write descriptive test names
5. Use parametrized tests where appropriate

### Documentation

1. Use docstrings (Google style) for modules, classes, and functions
2. Keep README.md up to date
3. Document non-obvious implementation decisions
4. Include type hints in docstrings

### Dependencies

1. Use requirements.txt or pyproject.toml
2. Pin dependency versions
3. Use virtual environments
4. Regularly update dependencies for security

### Environment and Tools

1. Use Python 3.8+ features
2. Use Black for code formatting
3. Use isort for import sorting
4. Use flake8 for linting
5. Use mypy for type checking

## Quality Assurance

1. Run automated formatters before committing
2. Run type checker and linter
3. Run tests before committing code
4. Address all warnings

## Amendments

1. Constitutional changes require maintainer approval
2. Approved changes take effect immediately
