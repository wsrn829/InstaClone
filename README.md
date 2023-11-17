# React + TypeScript + Vite

1. Run "npm create vite@latest ./" command in the terminal to setup the development environment, and choose React as the framework and TypeScript as the variant.
2. Run "npm install" to install dependencies, and run "npm run dev" to spin up the apllication in the browser on port:  http://localhost:5173/
3. In the src folder, create main.js to create ReactDOM and hook it with the actual DOM ('root').
4. Create App.js to set up the entire structure of the application as well as the routes.
5. Create a globals.css file (written in Tailwind CSS) and setup Tailwind CSS with vite in the terminal by running "npm install -D tailwindcss postcss autoprefixer" command to install necessaru packages. Then run "npx tailwindcss init -p" to initialize Tailwind CSS, which creates tailwind.config.js and postcss.config.js files, etc. Add "content" to tailwind.config.css file and add the "@tailwind" directives (@tailwind base; @tailwind components; @tailwind utilities;) to globals.css file.
