# Vite-React-Docu

Download nodejs
To check if you have nodejs installed in your computer, type: node -v in your command prompt.
To create Vite + React folder
1. Open new terminal and type: npx create vite@latest myproject.
2. To add tailwindcss open new terminal inside your created Vite + React folder type: npm install -D tailwindcss
3. To create tailwind.config.js file type: npx tailwindcss init
4. In your tailwind.config.js file replace the code with this:
```js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./src/*.{js,ts,jsx,tsx}",
    "./src/components/*.{js,ts,jsx,tsx}",
    "./src/pages/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```
Start your project, Enjoy!
