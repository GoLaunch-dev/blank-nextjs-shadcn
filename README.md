# Next.js and Shadcn UI Template

This is a basic template for creating web applications using Next.js and Shadcn UI components. It provides a lightweight starting point for your projects with modern web technologies.

## Features

- Next.js 14.2.7
- React 18
- Shadcn UI components
- TypeScript support
- ESLint and Prettier for code quality
- Tailwind CSS for styling

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```
   npm install
   ```
3. Run the development server:
   ```
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Changing the Theme

Shadcn UI provides a simple way to customize your theme:

1. Visit the [Shadcn UI Theme Generator](https://ui.shadcn.com/themes).
2. Choose your desired colors for background, foreground, primary, secondary, etc.
3. Click on "Copy CSS Variables" to copy the generated theme.
4. Open `app/globals.css` in your project.
5. Replace the existing `:root` and `[data-theme="dark"]` CSS variables with the copied theme.
