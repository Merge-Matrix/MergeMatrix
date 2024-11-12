# Contributing to MergeMatrix

Thank you for your interest in contributing to MergeMatrix! Contributions from the community are vital to make MergeMatrix a powerful, user-friendly, and flexible tool. We welcome contributions of all types, including code, documentation, design, and feature suggestions. This document will guide you through the contribution process.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [How Can I Contribute?](#how-can-i-contribute)
    - [Reporting Bugs](#reporting-bugs)
    - [Suggesting Enhancements](#suggesting-enhancements)
    - [Submitting Code](#submitting-code)
    - [Improving Documentation](#improving-documentation)
3. [Getting Started](#getting-started)
    - [Setting Up Your Environment](#setting-up-your-environment)
    - [Working with Issues](#working-with-issues)
4. [Development Guidelines](#development-guidelines)
    - [Coding Standards](#coding-standards)
    - [Commit Message Guidelines](#commit-message-guidelines)
    - [Testing and Quality Assurance](#testing-and-quality-assurance)
5. [Pull Request Process](#pull-request-process)
6. [Community and Support](#community-and-support)

---

## Code of Conduct

MergeMatrix follows a [Code of Conduct](./CODE_OF_CONDUCT.md) to ensure a welcoming environment for all contributors. Please read and adhere to it when participating in the project.

---

## How Can I Contribute?

### Reporting Bugs

If you encounter any issues with MergeMatrix:

1. **Check for duplicates:** Look at [existing issues](https://github.com/merge-matrix/mergematrix/issues) to see if your bug has already been reported.
2. **Create a new issue:** If no existing issue matches, open a new one and include:
   - A clear and descriptive title.
   - Steps to reproduce the issue.
   - Expected and actual behavior.
   - Environment details (operating system, browser, or any relevant configuration).
3. **Provide screenshots** if applicable.

### Suggesting Enhancements

We welcome suggestions for new features or improvements. To suggest an enhancement:

1. **Search for existing suggestions:** Check if a similar feature request already exists.
2. **Open a new issue:** If it doesn’t exist, create a new issue in the [issue tracker](https://github.com/merge-matrix/mergematrix/issues).
3. **Describe your idea** in detail, explaining why it would benefit the project.

### Submitting Code

If you’d like to contribute code to MergeMatrix:

1. **Check the roadmap and issues** to ensure the feature or bug is not already in progress.
2. **Fork the repository** to your GitHub account.
3. **Clone your fork** and set up the environment as described below.
4. **Follow our coding standards and guidelines** outlined below.

### Improving Documentation

Documentation is critical! To contribute:

1. Check the [documentation issues](https://github.com/merge-matrix/mergematrix/issues?q=is%3Aissue+is%3Aopen+label%3Adocumentation).
2. Submit a pull request for any updates, clarifications, or expansions you make to documentation.

---

## Getting Started

### Setting Up Your Environment

1. **Fork the repository** on GitHub.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/your-username/mergematrix.git
   ```
3. **Install dependencies** as required:
   ```bash
   cd mergematrix
   npm install
   ```
4. **Configure your environment** according to the `.env.example` provided.

5. **Run the project** to ensure everything is working:
   ```bash
   npm start
   ```

### Working with Issues

1. Browse open issues and choose one to work on.
2. Comment on the issue to let others know you're working on it.
3. Ensure the issue is assigned to you before starting.

---

## Development Guidelines

### Coding Standards

- **Languages & Frameworks:** This project uses JavaScript/TypeScript, React, and Node.js.
- **Linting:** We use ESLint and Prettier to maintain code consistency. Run `npm run lint` to ensure your code passes.
- **File Naming:** Use kebab-case for filenames and PascalCase for component files.
- **Documentation:** Comment code where necessary, especially for complex logic.

### Commit Message Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/) for clear, structured commit messages:

- **feat:** A new feature
- **fix:** A bug fix
- **docs:** Documentation updates
- **style:** Code style changes (formatting, missing semi-colons, etc.)
- **refactor:** Code changes that neither fix a bug nor add a feature
- **test:** Adding or updating tests
- **chore:** Maintenance or changes that don’t modify src or test files

Example:
```
feat(auth): add JWT authentication for secure user login
```

### Testing and Quality Assurance

- **Testing Framework:** We use Jest and React Testing Library.
- **Write tests:** Cover new code with tests to ensure reliability.
- **Run tests** before submitting: 
  ```bash
  npm test
  ```

---

## Pull Request Process

1. **Create a branch**:
   ```bash
   git checkout -b feature/your-feature
   ```
2. **Commit changes** following the commit guidelines above.
3. **Push to your fork** and create a pull request from your branch to `main`:
   ```bash
   git push origin feature/your-feature
   ```
4. **Create the pull request**:
   - Provide a descriptive title and summary.
   - Reference the issue you are addressing, if applicable (e.g., `Closes #123`).
5. **Ensure CI passes:** Your pull request will run through automated checks.
6. **Review Process:** A project maintainer will review your PR. Be open to feedback and make changes as requested.

---

## Community and Support

- **Discussions:** Join us in the [Discussions section](https://github.com/merge-matrix/mergematrix/discussions) on GitHub to ask questions, suggest features, or chat about the project.
- **Slack/Discord:** Coming soon! Stay tuned for more ways to connect.
- **Issues:** For support, please use GitHub issues for transparency and so others can benefit from solutions.

By following these guidelines, you’ll help make MergeMatrix a valuable tool for all its users. Thank you for being a part of our community and helping to shape the future of this project!

