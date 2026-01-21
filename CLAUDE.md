# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Alfred is a Java application built with Gradle. Currently a simple console application with minimal implementation serving as a project template.

## Build Commands

```bash
# Build the project
./gradlew build

# Run tests (currently no tests implemented)
./gradlew test

# Clean build artifacts
./gradlew clean

# Compile Java classes only
./gradlew classes
```

## Project Structure

The codebase follows standard Gradle/Java conventions:
- **Source code**: `src/main/java/io/butler/`
- **Tests**: `src/test/java/` (empty, ready for JUnit 5)
- **Build configuration**: `build.gradle`
- **Entry point**: `io.butler.Main` class

## Technology Stack

- **Java**: JDK 21 (LTS)
- **Build Tool**: Gradle 8.14
- **Test Framework**: JUnit 5 (configured but no tests yet)
- **IDE**: IntelliJ IDEA configured

## Architecture

Currently a single-class application (`Main.java`) with no architectural patterns implemented. The project is set up as a starting point for Java development with:
- Maven Central repository configured for dependencies
- JUnit 5 testing framework ready
- Standard Gradle project structure

## Development Notes

- The project uses Gradle wrapper (`./gradlew`) - no need to install Gradle separately
- Group ID: `io.butler`, Version: `1.0-SNAPSHOT`
- No external runtime dependencies beyond Java standard library
- `.gitignore` is comprehensive, covering IDE files and build artifacts