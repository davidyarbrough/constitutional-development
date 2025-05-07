
# Phaser Game Development Constitution

## 1. Core Principles

1.1. Authority
1.1.1. This constitution governs the structure, organization, and standards of Phaser game code and documentation within this repository.
1.1.2. All developers and AI assistants must follow these rules.
1.1.3. The repository maintainer has final authority on all changes.

1.2. Mission
1.2.1. All code, documentation, and templates must promote clear, AI-friendly, and human-readable governance.

## 2. Template Standards

2.1. Constitutional Structure
2.1.1. This constitution follows a standardized structure with rules as specific directives treated as supreme guidance.
2.1.2. Each rule has a unique reference number.
2.1.3. Each rule is expressed as a clear, actionable statement.
2.1.4. Sections are numbered categorizations that group related rules.

2.2. Numbering System
2.2.1. Major sections are numbered sequentially (1., 2., 3., etc.).
2.2.2. Subsections use decimal notation (2.1., 2.2., 2.3., etc.).
2.2.3. Rules continue the hierarchy (2.1.1., 2.1.2., etc.).
2.2.4. All decimal points are followed by a space.

2.3. Hierarchy Best Practices
2.3.1. The hierarchy is kept as flat as possible to prevent confusion.
2.3.2. Each rule is a leaf in the hierarchy tree.
2.3.3. Avoid combining rules; if a rule contains "and", it is split into separate rules.
2.3.4. Higher-level nodes only serve as categorization for rules beneath them.

2.4. General Requirements
2.4.1. This template includes clear core principles.
2.4.2. This template includes specific governance rules.
2.4.3. This template includes an amendment process.
2.4.4. This template includes documentation standards.
2.4.5. This template includes code standards.
2.4.6. All rules and documentation are clear and unambiguous.
2.4.7. All rules and documentation are easy to understand by both humans and AI.
2.4.8. The template is maintainable and extensible.

## 3. Code Organization

3.1. Source Structure
3.1.1. Each game scene must be defined in a separate file.
3.1.2. All scene files must reside in a `scenes` directory.
3.1.3. Scene files must be named with a `.scene.ts` suffix.
3.1.4. Scene files must include standardized JSDoc comments.
3.1.5. Asset references must be declared in type-safe asset manifests.
3.1.6. Asset manifests must be organized by asset type (sprites, audio, etc.).
3.1.7. Asset comments must specify explicit dimensions and formats.
3.1.8. Asset references must use relative paths from the `assets` directory.

3.2. Cross-Platform Standards
3.2.1. Input handling code must use abstract input interfaces.
3.2.2. Input handling code must include type definitions for all input methods.
3.2.3. Touch and mouse handler implementations must be maintained separately.
3.2.4. Platform-specific behavior must be documented in code comments.
3.2.5. Platform-specific code must be isolated in clearly marked conditional blocks.
3.2.6. Platform-specific code must include explanatory comments for platform differences.
3.2.7. Platform-specific code must be accompanied by unit tests for each platform.
3.2.8. Platform-specific code must use standardized platform detection utilities.

## 4. Documentation Standards

4.1. Code Documentation
4.1.1. All scene files must document required assets and their specifications.
4.1.2. All scene files must document input handling expectations.
4.1.3. All scene files must document platform-specific behaviors.
4.1.4. All scene files must document performance considerations.
4.1.5. Game configuration must document required renderer capabilities.
4.1.6. Game configuration must document minimum memory requirements.
4.1.7. Game configuration must document asset loading strategies.
4.1.8. Game configuration must document the platform support matrix.

4.2. Asset Documentation
4.2.1. Asset manifest files must specify required dimensions and formats.
4.2.2. Asset manifest files must specify memory usage estimates.
4.2.3. Asset manifest files must specify platform compatibility notes.
4.2.4. Asset manifest files must specify optimization requirements.
4.2.5. Asset pipeline documentation must include format conversion specifications.
4.2.6. Asset pipeline documentation must include compression requirements.
4.2.7. Asset pipeline documentation must include platform-specific variants.
4.2.8. Asset pipeline documentation must include loading sequence dependencies.

## 5. Code Standards

5.1. Testing Standards
5.1.1. The repository must include tests for platform-specific code paths.
5.1.2. The repository must include tests for input handling implementations.
5.1.3. The repository must include tests for asset loading procedures.
5.1.4. The repository must include tests for scene transitions.
5.1.5. Test files must reside alongside source files.
5.1.6. Test files must use the `.test.ts` or `.test.js` suffix.
5.1.7. Test files must include platform-specific test cases.
5.1.8. Test files must verify memory management.

5.2. Code Quality
5.2.1. All source files must pass ESLint/TSLint with the provided configuration.
5.2.2. All source files must include complete type definitions.
5.2.3. All source files must follow project naming conventions.
5.2.4. All source files must maintain cyclomatic complexity below the agreed threshold.
5.2.5. All scene implementations must implement standard lifecycle methods.
5.2.6. All scene implementations must document asset dependencies.
5.2.7. All scene implementations must handle cleanup in shutdown/destroy methods.
5.2.8. All scene implementations must use dependency injection where appropriate.

## 6. Amendment Process

6.1. Changes to this constitution require a pull request with explanation.
6.2. Changes to this constitution require updates to affected documentation.
6.3. Changes to this constitution require corresponding test updates.
6.4. Changes to this constitution require maintainer approval.
6.5. Emergency fixes must still follow code organization rules.
6.6. Emergency fixes must include minimal required tests.
6.7. Emergency fixes must update relevant documentation.
6.8. Emergency fixes must be reviewed post-implementation.
