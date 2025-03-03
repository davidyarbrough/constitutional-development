# Ruby Project Constitution

## Core Principles

1. This constitution governs all code and documentation in this repository
2. All developers and AI assistants must follow these rules
3. The repository maintainer has final authority on all changes

## Ruby-Specific Standards

### Code Organization

1. Follow the Ruby gem structure when applicable
2. Use meaningful module and class names
3. Keep files focused and cohesive
4. Organize tests to mirror the lib directory structure

### Code Style

1. Follow the Ruby Style Guide
2. Use snake_case for methods and variables
3. Use PascalCase for classes and modules
4. Use SCREAMING_SNAKE_CASE for constants
5. Two-space indentation

### Best Practices

1. Follow the Principle of Least Surprise
2. Keep methods small and focused
3. Use blocks and yield for flexibility
4. Prefer symbols over strings when appropriate
5. Use Ruby's built-in enumerable methods
6. Favor composition over inheritance
7. Use modules for shared behavior

### Error Handling

1. Use exceptions for exceptional conditions
2. Create custom exceptions when needed
3. Use ensure blocks for cleanup
4. Include context in error messages
5. Use retry judiciously

### Testing

1. Write tests using RSpec
2. Maintain minimum 90% code coverage
3. Use factories with FactoryBot
4. Write descriptive test names
5. Use shared examples where appropriate

### Documentation

1. Use RDoc/YARD for documentation
2. Document public API methods
3. Keep README.md up to date
4. Include usage examples in documentation

### Dependencies

1. Use Bundler for dependency management
2. Pin dependency versions in Gemfile
3. Use .ruby-version for Ruby version
4. Regularly update dependencies for security

### Environment and Tools

1. Use Rubocop for style enforcement
2. Use SimpleCov for coverage reporting
3. Use Rake for task automation
4. Use Pry for debugging

### Performance

1. Use frozen_string_literal: true
2. Avoid unnecessary object allocation
3. Use appropriate data structures
4. Profile code when performance is critical

## Quality Assurance

1. Run Rubocop before committing
2. Run test suite
3. Check documentation coverage
4. Address all warnings

## Amendments

1. Constitutional changes require maintainer approval
2. Approved changes take effect immediately
