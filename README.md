# Next.js Snippets

[![Visual Studio Marketplace](https://img.shields.io/badge/Marketplace-Install-blue)](https://marketplace.visualstudio.com/items?itemName=MinaSamehAnis.nextjs-snippets)

### Description
Boost your Next.js development productivity with this VS Code extension. This extension provides a set of handy snippets for Next.js projects, allowing you to quickly scaffold common code patterns.

---

## Features
- **Quick Scaffolding**: Create Next.js pages, API routes, components, and more in seconds.
- **TypeScript Support**: Includes TypeScript-specific snippets for type-safe development.
- **Reusable Code Blocks**: Simplify your codebase with reusable snippets for common tasks like `getServerSideProps`, `getStaticProps`, and more.

---

## Installation
1. Search for **Next.js Snippets** in the **Visual Studio Marketplace**.
2. Click **Install** to add it to your VS Code.
3. Reload VS Code if prompted.

---

## Usage
### Snippets Overview
Type the following prefixes in your `.js`, `.jsx`, `.ts`, or `.tsx` files to trigger the snippets:

| Prefix               | Description                        |
|----------------------|------------------------------------|
| `npage`             | Create a Next.js page             |
| `napiroute`         | Create an API route               |
| `ncomponent`        | Create a functional component     |
| `ngssp`             | `getServerSideProps` function     |
| `ngsp`              | `getStaticProps` function         |
| `ngspaths`          | `getStaticPaths` function         |

---

### Example Snippets

#### `npage` - Next.js Page
Generates a basic Next.js page:

```javascript
import React from 'react';

const Page = () => {
  return (
    <div>
      <h1>Hello, Next.js!</h1>
    </div>
  );
};

export default Page;
