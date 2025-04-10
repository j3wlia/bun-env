# Bun TypeScript Project

This is a TypeScript project set up with **Bun**, **ESLint**, **Prettier**, **Jest**, **Husky**, and **lint-staged** to help maintain clean and formatted code.

## Prerequisites

- **Bun**: [Install Bun](https://bun.sh)
- **Git**: Make sure Git is installed on your system.

## Getting Started

### 1. Install Dependencies
`bun install`

### 2. Install Husky
`npx husky install`

### 3. Manually Run Linting & Formatting
```bun run lint```
```bun run format```

### 4. Run tests with Jest
`bun jest`

## Configuration Files
`eslint.config.js`: ESLint configuration for linting TypeScript files with Prettier integration.

`.prettierrc`: Configuration file for Prettier formatting options.

`tsconfig.json`: Configuration for Typescript.

`jest.config.js`: Jest configuration for running tests in the project.
