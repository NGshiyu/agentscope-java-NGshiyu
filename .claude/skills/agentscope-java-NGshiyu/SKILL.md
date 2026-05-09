```markdown
# agentscope-java-NGshiyu Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns, coding conventions, and workflows used in the `agentscope-java-NGshiyu` repository. The project is written in Java, with no specific framework detected. It follows clear naming conventions, structured commit messages, and a modular code organization. This guide will help you contribute code that matches the project's established style and practices.

## Coding Conventions

### File Naming
- **Convention:** PascalCase is used for all file names.
- **Example:**
  ```
  AgentManager.java
  TaskHandler.java
  ```

### Import Style
- **Convention:** Use relative imports for referencing classes within the project.
- **Example:**
  ```java
  import com.ngshiyu.agentscope.AgentManager;
  import com.ngshiyu.agentscope.tasks.TaskHandler;
  ```

### Export Style
- **Convention:** Use named exports (public classes and methods).
- **Example:**
  ```java
  public class AgentManager {
      public void startAgent() {
          // ...
      }
  }
  ```

### Commit Messages
- **Convention:** Conventional commits with the `feat` prefix are used for new features.
- **Example:**
  ```
  feat: add support for multi-agent coordination in AgentManager
  ```

## Workflows

_No automated workflows detected in the repository._

## Testing Patterns

- **Framework:** Unknown (no standard Java testing framework detected).
- **File Pattern:** Test files are named with the `.test.ts` suffix, which suggests some TypeScript-based tests, possibly for frontend or API stubs.
- **Example:**
  ```
  AgentManager.test.ts
  ```

  > Note: For Java code, consider using JUnit or another Java testing framework for consistency.

## Commands
| Command | Purpose |
|---------|---------|
| /commit-feature | Start a new feature with a conventional commit message (`feat:`) |
| /new-class | Create a new Java class file using PascalCase naming |
| /import-relative | Add a relative import statement for a class in the project |
| /run-tests | Run all test files matching `*.test.ts` pattern |
```
