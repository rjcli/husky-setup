# Husky Setup Repository

This repository demonstrates how you can setup Husky for managing Git hooks, along with ESLint and Prettier for code quality and formatting.

## Features

- **Husky**: Pre-commit hooks to ensure code quality before committing.
- **ESLint**: Linting for JavaScript and React code.
- **Prettier**: Code formatting to maintain consistency.
- **Lint-Staged**: Runs Prettier on staged files during commits.

## Setup Husky

```bash
npm run husky:setup
```

## Lint the code

```bash
npm run lint
```

## Check code formatting

```bash
npm run lint
```

## Fix code formatting

```bash
npm run prettier:write
```

## Husky Pre-Commit Hook

The pre-commit hook is defined in in `.husky/pre-commit` and ensure the following:

1. Runs ESLint to check for linting errors.
2. Formats staged files using Prettier via `lint-staged`.

## ESLint and Prettier Configuration

- **ESLint**: Configured in `.eslintrc.json` and `eslint.config.mjs` to follow recommended rules for JavaScript and React.
- **Prettier**: Configured in `.prettierrc` and `.prettierignore` to maintain code formatting.
