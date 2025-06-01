# React + Vite + TypeScript Boilerplate

This project is a boilerplate for building React applications using Vite and TypeScript. It includes configurations for ESLint, Prettier, StyleLint, and Husky for pre-commit hooks.

## Features

- React 18
- Vite as the build tool
- TypeScript for type safety
- ESLint for linting
- Prettier for code formatting
- StyleLint for CSS linting
- Tailwind CSS for styling
- Husky for pre-commit hooks

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/react-vite-ts-boilerplate.git
   ```

2. Navigate to the project directory:

   ```bash
   cd react-vite-ts-boilerplate
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

### Running the Application

To start the development server, run:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:3000` to see your application in action.

### Linting and Formatting

This project uses ESLint and Prettier for linting and formatting. You can run the following commands to lint and format your code:

- Lint: `npm run lint`
- Format: `npm run format`

### Pre-commit Hooks

Husky is configured to run ESLint and Prettier before each commit. This ensures that your code is always linted and formatted correctly.

### Building for Production

To build the application for production, run:

```bash
npm run build
```

This will create an optimized build in the `dist` directory.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
