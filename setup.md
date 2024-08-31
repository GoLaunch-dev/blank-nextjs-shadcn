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
