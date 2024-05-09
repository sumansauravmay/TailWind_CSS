#command

// add this in the hed tag and start using Tailwind css

<script src="https://cdn.tailwindcss.com"></script>

--------------------------------------------------------------------------------------------------------------------------

1. npm init --y
2. npm install -D tailwindcss postcss autoprefixer
3. npm i vite
4. npx tailwindcss init
5. add this in the package.json folder(scripts)
"start": "vite"
6. npm run start(to run the server)
7. install Tailwind CSS IntelliSense(this is vs code exptension)
-----------------------------------------------------------------------------------------------------------------------------
//For the production in the indusries.

1. npm init -y
2. npm install -D tailwindcss postcss autoprefixer
3. npx tailwindcss init -p
4. create a css file "input.css". add it to your html and edit it with this content:

@tailwind base;
@tailwind components;
@tailwind utilities;


5. In your tailwind.config.js file replace content:[], with content:["*"],
6. Add "start":"vite" to your scripts in package.json
7. create a index.html file
8.  add this in the html file in the header section

<script src="https://cdn.tailwindcss.com"></script>

now we can use tailwind css.
9. Run npm run start command to start a dev server

---------------------------------------------------------------------------------------------------------------------------
// command using react in CRA(create react app)

1. npx create-react-app my-project
2. cd my-project
3. npm install -D tailwindcss
4. npx tailwindcss init
5. now paste this in the tailwind.config.js file

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

6. add this in the index.css

@tailwind base;
@tailwind components;
@tailwind utilities;

7. npm run start(to run command)

8. write the code in the app.js or in the other component

----------------------------------------------------------------------------------------------------------------------------

// command using vite
1. npm create vite@latest my-project -- --template react
2. cd my-project
3. npm install -D tailwindcss postcss autoprefixer
4. npx tailwindcss init -p
5. now paste this in the tailwind.config.js file


/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

6. add this in the index.css

@tailwind base;
@tailwind components;
@tailwind utilities;

7. npm run dev
8. write the code in the app.js or in the other component

