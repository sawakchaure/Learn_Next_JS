# Learn_Next_JS

Installation 
Option 1. npx create-next-app@latest

It asks below questions,

- What is your project named? my-app
- Would you like to use TypeScript? No / Yes
- Would you like to use ESLint? No / Yes
- Would you like to use Tailwind CSS? No / Yes
- Would you like your code inside a `src/` directory? No / Yes
- Would you like to use App Router? (recommended) No / Yes
- Would you like to use Turbopack for `next dev`?  No / Yes
- Would you like to customize the import alias (`@/*` by default)? No / Yes
- What import alias would you like configured? @/*


Option 2. npm install next@latest react@latest react-dom@latest
- create a package.json file and paste the following script:
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  }
}
