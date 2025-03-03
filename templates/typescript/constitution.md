# TypeScript Project Constitution

## Core Principles

1. This constitution governs all code and documentation in this repository
2. All developers and AI assistants must follow these rules
3. The repository maintainer has final authority on all changes

## TypeScript-Specific Standards

### Code Organization

1. Use modules (import/export)
2. Follow a clear directory structure
3. Keep files focused and cohesive
4. Group related functionality

### Type System

1. Enable strict mode in tsconfig.json
2. Use explicit type annotations for public APIs
3. Prefer interfaces over type aliases for public APIs
4. Use union types over enums
5. Make proper use of generics
6. Avoid type assertions unless necessary
7. Use unknown over any

### Code Style

1. Follow TypeScript ESLint recommendations
2. Use camelCase for variables and functions
3. Use PascalCase for types, interfaces, and classes
4. Use UPPER_SNAKE_CASE for constants
5. Prefix interfaces with 'I' only when required by project convention

### Best Practices

1. Make use of TypeScript's type system
2. Use readonly where applicable
3. Use async/await over raw promises
4. Use null coalescing and optional chaining
5. Leverage discriminated unions
6. Use type predicates for type narrowing
7. Make proper use of access modifiers

### Error Handling

1. Create custom error types
2. Use type-safe error handling
3. Handle promise rejections
4. Include context in error messages
5. Use Error objects, not strings

### Testing

1. Write tests using Jest and ts-jest
2. Maintain minimum 80% code coverage
3. Use type-aware testing utilities
4. Test type definitions
5. Mock with type safety

### Documentation

1. Use TSDoc for documentation
2. Document complex type relationships
3. Keep README.md up to date
4. Include type usage examples

### Dependencies

1. Use package.json for dependency management
2. Include appropriate @types packages
3. Lock dependencies with package-lock.json
4. Regularly update dependencies for security

### Configuration

1. Maintain strict tsconfig.json
2. Use project references for large projects
3. Configure source maps appropriately
4. Use appropriate module resolution

### Build Process

1. Use TypeScript compiler (tsc)
2. Generate declaration files
3. Configure appropriate output structure
4. Optimize compilation settings

## Quality Assurance

1. Run type checker
2. Run linter
3. Run test suite
4. Address all warnings

## Amendments

1. Constitutional changes require maintainer approval
2. Approved changes take effect immediately
