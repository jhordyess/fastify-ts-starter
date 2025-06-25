# Fastify TypeScript Starter

This is a starter project for building a backend application using Fastify, TypeScript and Webpack.

## Features

- **Fastify**: A fast and low-overhead web framework for Node.js. (v. 5)
- **TypeScript**: Strongly typed JavaScript for better development experience. (v. 5)
- **ESLint**: Linting for maintaining code quality. (v. 9)
- **Prettier**: Code formatting for consistent style. (v. 3)
- **Husky**: Git hooks for enforcing pre-push checks. (v. 9)
- **pnpm**: Package manager for managing dependencies. (v. 10)

## Prerequisites

1. Install [Node.js](https://nodejs.org/en/download) (LTS version recommended).
2. Enable Corepack to use a stable version of pnpm:

```sh
corepack enable pnpm
```

## Getting Started

1. Clone the repository:

```sh
git clone https://github.com/jhordyess/fastify-ts-starter.git
```

2. Navigate to the project folder:

```sh
cd fastify-ts-starter
```

3. Install dependencies:

```sh
pnpm i
```

4. Start the development server:

```sh
pnpm dev
```

5. Open your browser or API client and interact with the server running at [http://localhost:8080](http://localhost:8080).

## Project Structure

```md
fastify-ts-starter/
├── .gitignore              # List of files and directories to be ignored by version control.
├── .prettierrc.json        # Prettier configuration file.
├── eslint.config.js        # ESLint configuration file.
├── package.json            # Project configuration and dependencies.
├── pnpm-lock.yaml          # pnpm lock file for dependency versions.
├── pnpm-workspace.yaml     # pnpm workspace configuration file.
├── README.md               # Project documentation.
├── tsconfig.json           # TypeScript configuration file.
├── .husky/                 # Directory for Git hooks managed by Husky.
│   ├── pre-push            # Pre-push hook to run linting and TypeScript checks.
├── src/
│   ├── index.ts            # Main entry point of the application.
```

## Commands

### Start the development server

```sh
pnpm dev
```

### Build the project for production

```sh
pnpm build
```

### Build the project for production with linting

```sh
pnpm build:lint
```

### Start the production server

```sh
pnpm start
```

### Run TypeScript checks

```sh
pnpm ts-check
```

### Lint the code

```sh
pnpm lint
```

### Validate the project (lint + TypeScript checks)

```sh
pnpm validate
```

### Format the code

```sh
pnpm format
```

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.

---

Happy coding!
