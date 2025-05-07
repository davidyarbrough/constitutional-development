# Python Project Constitution

## 1. Core Principles

### 1.1. Governance
1.1.1. This constitution governs all Python code and documentation in this repository.
1.1.2. All developers and AI assistants must follow these rules.
1.1.3. The repository maintainer has final authority on all changes.

## 2. Python-Specific Standards

### 2.1. Code Organization
2.1.1. Follow the Python package structure.
2.1.2. Use meaningful module names in snake_case.
2.1.3. Keep modules focused and cohesive.
2.1.4. Organize tests in a parallel structure to source code.

### 2.2. Code Style
2.2.1. Follow PEP 8 style guide.
2.2.2. Use snake_case for functions and variables.
2.2.3. Use PascalCase for class names.
2.2.4. Use UPPER_SNAKE_CASE for constants.
2.2.5. Maximum line length of 88 characters (Black default).

### 2.3. Best Practices
2.3.1. Follow the Zen of Python (PEP 20).
2.3.2. Use type hints for function signatures.
2.3.3. Make functions and classes as small as possible.
2.3.4. Use list comprehensions judiciously.
2.3.5. Prefer explicit over implicit.
2.3.6. Use context managers (with statements) for resource management.
2.3.7. Favor composition over inheritance.

### 2.4. Error Handling
2.4.1. Use exceptions rather than return codes.
2.4.2. Create custom exceptions when appropriate.
2.4.3. Handle exceptions at the appropriate level.
2.4.4. Include context in error messages.
2.4.5. Use finally blocks for cleanup.

### 2.5. Testing
2.5.1. Write tests using pytest.
2.5.2. Maintain minimum 80% code coverage.
2.5.3. Use fixtures for test setup.
2.5.4. Write descriptive test names.
2.5.5. Use parametrized tests where appropriate.

### 2.6. Documentation
2.6.1. Use docstrings (Google style) for modules, classes, and functions.
2.6.2. Keep README.md up to date.
2.6.3. Document non-obvious implementation decisions.
2.6.4. Include type hints in docstrings.

### 2.7. Dependencies
2.7.1. Use requirements.txt or pyproject.toml.
2.7.2. Pin dependency versions.
2.7.3. Use virtual environments.
2.7.4. Regularly update dependencies for security.

### 2.8. Environment and Tools
2.8.1. Use Python 3.8+ features.
2.8.2. Use Black for code formatting.
2.8.3. Use isort for import sorting.
2.8.4. Use flake8 for linting.
2.8.5. Use mypy for type checking.

## 3. Quality Assurance

### 3.1. Code Review
3.1.1. Run automated formatters before committing.
3.1.2. Run type checker and linter.
3.1.3. Run tests before committing code.
3.1.4. Address all warnings.

## 4. Amendments

### 4.1. Process
4.1.1. Constitutional changes require maintainer approval.
4.1.2. Approved changes take effect immediately.
