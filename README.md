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
