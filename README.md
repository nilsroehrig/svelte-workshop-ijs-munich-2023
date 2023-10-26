# Web Apps with Svelte

## A Practical Introduction

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/fork/github/nilsroehrig/svelte-workshop-ijs-munich-2023?title='Svexpensr'&startScript=stackblitz)

In this repository, you'll find the code for the workshop's companion app. The examples are organized by chapters, and they build upon each other. Each chapter is tagged separately, allowing you to jump back to the start of a chapter at any time.

### Requirements

The following tools are required to work with this repository:
- Node.js 18
- npm 9

### Getting Started

To work with the repository, you need to install the project dependencies first:

```bash
npm ci
```

After that, you can use the development environment. Start a development server that continuously watches files, applies changes immediately, and makes them visible in the browser:

```bash
npm run dev
```

The application can also be built for production deployment. This will create a `dist` directory in the project root directory that contains the built files ready for deployment:

```bash
npm run build
```

After building the application, you can preview the built state in the browser:

```bash
npm run preview
```

### Linting and Formatting

For the project, ESLint and Prettier are configured as the linter and code formatter. To process files in the repository using these tools, you can use the following scripts:

```bash
npm run lint # ESLint
npm run format # Prettier
```

However, it is recommended to set up these tools in your own Integrated Development Environment (e.g., VSCode).
