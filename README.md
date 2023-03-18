# tic-tac-toe

create vue project
select javascript
npm create vite@latest

get tailwinds css

npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

modify tailwind.config file

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./index.html","./src/**/*.{vue,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

create a main.css file in the src and past these in

@tailwind base;
@tailwind components;
@tailwind utilities;

then import the main.css into main.js

after that import google fonts into the index.html file

<link href="https://fonts.googleapis.com/css2?family=Material+Icons+Outlined"
      rel="stylesheet">
