# Prerequisites for Installing React with Vite, Bun, or Node.js

This guide outlines the requirements and steps to set up a React project using Vite with different package managers: Node.js (npm/yarn/pnpm) and Bun.

---

## System Requirements

Ensure your system meets the following prerequisites before proceeding:

- **Node.js**: Version 16.0.0 or higher.
  - [Download Node.js](https://nodejs.org/)
- **npm**: Comes pre-installed with Node.js, or install [yarn](https://yarnpkg.com/) / [pnpm](https://pnpm.io/).
- **Bun**: Version 0.5.0 or higher.
  - [Install Bun](https://bun.sh/)

---

## Installation Guide

### 1. Setting Up React with Vite (Node.js)

Follow these steps to create a React app using Vite with npm/yarn/pnpm:

```bash
# Using npm
npm create vite@latest my-react-app -- --template react

# Using yarn
yarn create vite my-react-app --template react

# Using pnpm
pnpm create vite@latest my-react-app --template react

```



```bash

cd my-react-app
npm install         # or yarn install / pnpm install
npm run dev         # or yarn dev / pnpm dev


```

Setting Up React with Vite (Bun)
To use Bun as the package manager:

```bash
Copy code
# Create the project
bun create vite my-react-app --template react

# Navigate to the project directory
cd my-react-app

# Start the development server
bun dev

```
## Additional Tips
Check for Version Compatibility  <br>
Use `node -v`, `npm -v`,` bun -v`, or `yarn -v` to verify installed versions. <br>
Install Required Dependencies <br>
Ensure vite and React packages are installed correctly during setup. <br>
Browser Compatibility <br>
Modern browsers (Chrome, Firefox, Edge) are recommended for local testing.
<br>