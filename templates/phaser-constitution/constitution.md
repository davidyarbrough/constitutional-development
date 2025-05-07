
# Phaser Game Development Constitution

## 1. Core Principles

### 1.1. Authority
1.1.1. This constitution governs the structure, organization, and standards of Phaser game code and documentation within this repository.
1.1.2. All developers and AI assistants must follow these rules.
1.1.3. The repository maintainer has final authority on all changes.

### 1.2. Mission

1.2.1. All code, documentation, and other content must promote clear, AI-friendly, and human-readable governance.

## 2. Code Organization

### 2.1. Source Structure

2.1.1. Each game scene must be defined in a separate file.
2.1.2. All scene files must reside in a `scenes` directory.
2.1.3. Scene files must be named with a `.scene.ts` suffix.
2.1.4. Scene files must include standardized comments.
2.1.5. Asset references must be declared in type-safe asset manifests.
2.1.6. Asset manifests must be organized by asset type (sprites, audio, etc.).
2.1.7. Asset comments must specify explicit dimensions and formats.
2.1.8. Asset references must use relative paths from the `assets` directory.

### 2.2. Cross-Platform Standards

2.2.1. Input handling code must use abstract input interfaces.
2.2.2. Input handling code must include type definitions for all input methods.
2.2.3. Touch and mouse handler implementations must be maintained separately.
2.2.4. Platform-specific behavior must be documented in code comments.
2.2.5. Platform-specific code must be isolated in clearly marked conditional blocks.
2.2.6. Platform-specific code must include explanatory comments for platform differences.
2.2.7. Platform-specific code must be accompanied by unit tests for each platform.
2.2.8. Platform-specific code must use standardized platform detection utilities.

## 3. Documentation Standards

### 3.1. Code Documentation

3.1.1. All scene files must document required assets and their specifications.
3.1.2. All scene files must document input handling expectations.
3.1.3. All scene files must document platform-specific behaviors.
3.1.4. All scene files must document performance considerations.
3.1.5. Game configuration must document required renderer capabilities.
3.1.6. Game configuration must document minimum memory requirements.
3.1.7. Game configuration must document asset loading strategies.
3.1.8. Game configuration must document the platform support matrix.

### 3.2. Asset Documentation

3.2.1. Asset manifest files must specify required dimensions and formats.
3.2.2. Asset manifest files must specify memory usage estimates.
3.2.3. Asset manifest files must specify platform compatibility notes.
3.2.4. Asset manifest files must specify optimization requirements.
3.2.5. Asset pipeline documentation must include format conversion specifications.
3.2.6. Asset pipeline documentation must include compression requirements.
3.2.7. Asset pipeline documentation must include platform-specific variants.
3.2.8. Asset pipeline documentation must include loading sequence dependencies.

## 4. Code Standards

### 4.1. Testing Standards

4.1.1. The repository must include tests for platform-specific code paths.
4.1.2. The repository must include tests for input handling implementations.
4.1.3. The repository must include tests for asset loading procedures.
4.1.4. The repository must include tests for scene transitions.
4.1.5. Test files must reside alongside source files.
4.1.6. Test files must use the `.test.ts` or `.test.js` suffix.
4.1.7. Test files must include platform-specific test cases.
4.1.8. Test files must verify memory management.

### 4.2. Code Quality

4.2.1. All source files must pass ESLint/TSLint with the provided configuration.
4.2.2. All source files must include complete type definitions.
4.2.3. All source files must follow project naming conventions.
4.2.4. All code components must be single-responsibility.
4.2.5. All scene implementations must implement standard lifecycle methods.
4.2.6. All scene implementations must document asset dependencies.
4.2.7. All scene implementations must handle cleanup in shutdown/destroy methods.
4.2.8. All scene implementations must use dependency injection where appropriate.
