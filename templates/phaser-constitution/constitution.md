# Phaser Game Development Constitution

## Core Principles

1. This constitution governs the structure, organization, and standards of Phaser game code and documentation within this repository
2. All code and documentation changes must adhere to these principles
3. Cross-platform compatibility must be verifiable through repository contents
4. Code maintainability and readability are fundamental requirements

## Code Organization

### Source Structure

1. Game scenes must be organized as:
   - One scene per file
   - Grouped in a `scenes` directory
   - Named with `.scene.ts` or `.scene.js` suffix
   - Documented with standardized JSDoc comments

2. Asset references must be:
   - Declared in type-safe asset manifests
   - Organized by asset type (sprites, audio, etc.)
   - Include explicit dimensions and formats in comments
   - Reference relative paths from an `assets` directory

### Cross-Platform Standards

1. Input handling code must:
   - Use abstract input interfaces
   - Include type definitions for all input methods
   - Maintain separate touch and mouse handler implementations
   - Document platform-specific behavior in code comments

2. Platform-specific code must:
   - Be isolated in clearly marked conditional blocks
   - Include explanatory comments for platform differences
   - Be accompanied by unit tests for each platform
   - Use standardized platform detection utilities

## Documentation Requirements

### Code Documentation

1. All scene files must document:
   - Required assets and their specifications
   - Input handling expectations
   - Platform-specific behaviors
   - Performance considerations

2. Game configuration must document:
   - Required renderer capabilities
   - Minimum memory requirements
   - Asset loading strategies
   - Platform support matrix

### Asset Documentation

1. Asset manifest files must specify:
   - Required dimensions and formats
   - Memory usage estimates
   - Platform compatibility notes
   - Optimization requirements

2. Asset pipeline documentation must include:
   - Format conversion specifications
   - Compression requirements
   - Platform-specific variants
   - Loading sequence dependencies

## Testing Standards

1. Repository must include tests for:
   - Platform-specific code paths
   - Input handling implementations
   - Asset loading procedures
   - Scene transitions

2. Test files must:
   - Reside alongside source files
   - Use `.test.ts` or `.test.js` suffix
   - Include platform-specific test cases
   - Verify memory management

## Code Quality Standards

1. All source files must:
   - Pass ESLint/TSLint with provided config
   - Include complete type definitions
   - Follow project naming conventions
   - Maintain cyclomatic complexity below agreed threshold

2. Scene implementations must:
   - Implement standard lifecycle methods
   - Document asset dependencies
   - Handle cleanup in shutdown/destroy
   - Use dependency injection where appropriate

## Amendment Process

1. Changes to this constitution require:
   - Pull request with explanation
   - Updates to affected documentation
   - Corresponding test updates
   - Maintainer approval

2. Emergency fixes must still:
   - Follow code organization rules
   - Include minimal required tests
   - Update relevant documentation
   - Be reviewed post-implementation
