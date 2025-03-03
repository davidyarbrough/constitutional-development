# JavaScript Project Constitution

## Core Principles

1. This constitution governs all JavaScript code and documentation in this repository
2. All developers and AI assistants must follow these rules
3. The repository maintainer has final authority on all changes

## JavaScript-Specific Standards

### Code Organization

1. Use ES modules (import/export)
2. Follow a clear directory structure
3. Keep files focused and cohesive
4. Separate business logic from UI components

### Code Style

1. Follow Airbnb JavaScript Style Guide
2. Use camelCase for variables and functions
3. Use PascalCase for classes and components
4. Use UPPER_SNAKE_CASE for constants
5. Use meaningful and descriptive names

### Best Practices

1. Use strict mode ('use strict')
2. Prefer const over let, avoid var
3. Use async/await over raw promises
4. Use destructuring assignment
5. Use template literals for string interpolation
6. Use spread/rest operators appropriately
7. Use optional chaining and nullish coalescing

### Error Handling

1. Use try-catch blocks appropriately
2. Create custom error classes when needed
3. Handle promise rejections
4. Include context in error messages
5. Use Error objects, not strings

### Testing

1. Write tests using Jest
2. Maintain minimum 80% code coverage
3. Use meaningful test descriptions
4. Mock external dependencies
5. Test edge cases and error conditions

### Documentation

1. Use JSDoc for documentation
2. Document complex algorithms
3. Keep README.md up to date
4. Include examples in documentation

### Dependencies

1. Use package.json for dependency management
2. Lock dependencies with package-lock.json
3. Regularly update dependencies for security
4. Keep dependencies minimal

### Environment and Tools

1. Use ESLint for linting
2. Use Prettier for formatting
3. Use Babel when needed
4. Use npm or yarn consistently

### Browser Compatibility

1. Define minimum browser support
2. Use appropriate polyfills
3. Test across supported browsers
4. Consider progressive enhancement

### Performance

1. Minimize bundle size
2. Use code splitting where appropriate
3. Optimize images and assets
4. Follow performance best practices

## Quality Assurance

1. Run linter before committing
2. Run test suite
3. Check bundle size
4. Address all warnings

## Amendments

1. Constitutional changes require maintainer approval
2. Approved changes take effect immediately
