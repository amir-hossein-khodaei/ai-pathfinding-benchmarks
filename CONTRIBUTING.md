# Contributing to Pathfinding Benchmarks

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
- [Styleguides](#styleguides)
  - [Java Styleguide](#java-styleguide)
  - [Python Styleguide](#python-styleguide)
  - [Commit Messages](#commit-messages)

## Code of Conduct

This project and everyone participating in it is governed by the
[Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## I Want To Contribute

### Legal Notice
When contributing to this project, you must agree that you have authored the content, that you have the rights to the content, and that the content you contribute may be provided under the project license.

### Development Workflow

1.  **Fork** the repository on GitHub.
2.  **Clone** your fork locally:
    \\\ash
    git clone https://github.com/your-username/pathfinding-benchmarks.git
    \\\
3.  **Create a Branch** for your edit:
    \\\ash
    git checkout -b feat/amazing-heuristic
    # or
    git checkout -b fix/memory-leak
    \\\
4.  **Commit** your changes using meaningful commit messages.
5.  **Push** to your fork and **Submit a Pull Request**.

## Styleguides

### Java Styleguide
- We follow standard **Java naming conventions** (CamelCase for classes, camelCase for methods/variables).
- Indentation: **4 spaces**.
- Javadoc is required for all public interfaces and complex algorithms.
- **No raw types**: Use generics (e.g., \List<Node>\ not \List\).

### Python Styleguide
- Follow **PEP 8** standards.
- Use **snake_case** for functions and variables.
- Type hinting is strongly encouraged for the ML pipeline.

### Commit Messages
We follow the **Conventional Commits** specification:

- \eat:\ A new feature (e.g., \eat: add bidirectional search\)
- \ix:\ A bug fix (e.g., \ix: resolve null pointer in SMA*\)
- \docs:\ Documentation only changes
- \style:\ Changes that do not affect the meaning of the code (white-space, formatting, etc)
- \efactor:\ A code change that neither fixes a bug nor adds a feature
- \perf:\ A code change that improves performance
- \	est:\ Adding missing tests or correcting existing tests
- \chore:\ Changes to the build process or auxiliary tools

## Testing

Before submitting a PR, please ensure:
1.  The Java engine compiles without warnings.
2.  Run the benchmark suite (\Option 1\) locally to ensure no regressions in path optimality.
3.  If modifying \ML.py\, ensure it generates valid weight files.

Happy coding!
