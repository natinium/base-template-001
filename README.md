
# Base Template 001

This template provides a ready-to-use base setup for starting a new JavaScript or Node.js application with pre-configured tools and development practices.

## Features

- **Commitizen**: Use `cz commit` to create commits with Gitmoji and Commitizen, ensuring consistent commit messages.
- **Yarn**: Package manager set to Yarn v1.22.22.
- **Husky**: Automates Git hooks.
- **Commitlint**: Enforces consistent commit messages.
- **Lint-staged**: Runs linters on staged Git files.
- **ESLint**: JavaScript linter with ES6 support.
- **Prettier**: Code formatter for consistent code style.
- **ES6**: Support for modern JavaScript syntax.
- **Module Type**: Configured as a module with ES6 `import` and `export`.

## Installation

To start a new project using this template, you can use `degit`:

```bash
npx degit <repository-url> new-project
cd new-project
yarn install
```

## Setup for Commitizen

Before using Commitizen, ensure you have the Commitizen Python package installed and set up. For detailed installation instructions, refer to the official [Commitizen documentation](https://commitizen-tools.github.io/commitizen/).

## Scripts

The template includes the following npm scripts for development:

- **`yarn test`**: Placeholder for running tests. (No tests specified by default.)
- **`yarn prepare`**: Initializes Husky for Git hooks.
- **`yarn lint`**: Runs ESLint to check JavaScript files.
- **`yarn lint:fix`**: Runs ESLint and automatically fixes issues.
- **`yarn format`**: Formats all files with Prettier.
- **`yarn format:check`**: Checks file formatting with Prettier.
- **`yarn lint-staged`**: Runs lint-staged on committed files.
- **`yarn validate`**: Runs both `lint` and `format:check` scripts.

## Using Commitizen

To create commits with Commitizen after setting up:

```bash
cz commit
```

## Development Workflow

1. **Linting and Formatting**: Code is automatically checked and formatted before commits.
2. **Consistent Commit Messages**: Commitlint and Gitmoji enforce consistent commit messages.

--- 
