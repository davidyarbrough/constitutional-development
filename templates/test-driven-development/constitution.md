# Test-Driven Development Constitution

## Core Principles

1. **Tests First, Code Second**: No feature code shall be written before corresponding tests have been created and shown to fail appropriately.

2. **Minimum Viable Implementation**: Code only what is necessary to make the tests pass - no more, no less.

3. **Continuous Validation**: After implementing a feature, tests must be run again to verify they now pass.

4. **Iterative Development**: Development shall proceed in small, verifiable cycles of test-code-refactor.

5. **Complete Test Coverage**: All functionality must be verified by tests.

## Mandatory Development Workflow

The following workflow shall be strictly adhered to for all code development:

### 1. Test Creation Phase
- Write comprehensive tests for the functionality to be implemented
- Tests must clearly define expected inputs and outputs
- Tests must cover normal operation, edge cases, and error conditions
- Document the purpose of each test

### 2. Test Validation Phase
- Run the newly created tests
- Verify that tests fail as expected
- Tests that pass before implementation indicate either:
  - Test is incorrect or insufficient
  - Feature already exists
  - Test is not testing what it claims to

### 3. Implementation Phase
- Write the minimum code required to make tests pass
- Focus exclusively on functionality, not optimization
- Make no assumptions beyond what tests specify

### 4. Verification Phase
- Run tests to verify implementation
- All tests must pass before proceeding
- If tests fail, return to implementation phase

### 5. Refactoring Phase
- Clean up, optimize, and refine the implementation
- Run tests after each significant change
- If tests fail during refactoring, revert changes or fix implementation

### 6. Integration Phase
- Integrate new code with the existing codebase
- Run the full test suite to verify no regressions
- If integration tests fail, fix integration issues

### 7. Documentation Phase
- Document the new functionality
- Reference tests as living documentation of expected behavior

## Prohibitions

The following practices are expressly prohibited:

1. Writing implementation code before tests
2. Modifying tests to match flawed implementations
3. Skipping any phase of the workflow
4. Implementing functionality without tests
5. Accepting code with failing tests
6. Committing code that has not passed all tests

## Exception Handling

In rare circumstances where strict TDD is impractical:

1. Document the specific reason for the exception
2. Create tests immediately after implementation
3. Ensure tests would have failed before implementation
4. Return to strict TDD for subsequent development

## Compliance

All AI assistance must enforce this constitution by:

1. Refusing to write implementation code before tests
2. Requiring test execution before and after implementation
3. Guiding the user through each phase of the workflow
4. Rejecting requests that violate these principles
5. Suggesting test cases when implementation is requested first

This constitution shall be the supreme guide for all development work. No code, documentation, or assistance may contradict these principles.
