#command

// npm init --y
// npm i tailwindcss
// make a public and source folder
1. create a public folder
2. create a src folder and create a file styles.css
// now add tailwind to the css i.e. styles.css
@tailwind base;
@tailwind components;
@tailwind utilities;

// now add this to the package.json in the scripts section

("build-css":"tailwindcss build src/styles.css -o public/styles.css")

// npm run build-css
now it is created a styles.css in the public folder.

//now create a index.html file in the public folder.
// install live server(npm i live-server -g)

// to run the live-server(live-server public)
index.html file is in the public folder

--------------------------------------------------------------------------------------------------------------------------------------------

// add this in the hed tag and start using Tailwind css

<script src="https://cdn.tailwindcss.com"></script>

--------------------------------------------------------------------------------------------------------------------------

1. npm init --y
2. npm install -D tailwindcss postcss autoprefixer
3. npm i vite
4. npx tailwindcss init
5. add this in the package.json folder(scripts)
"start": "vite"
6. npm start(to run the server)
7. install Tailwind CSS IntelliSense
-----------------------------------------------------------------------------------------------------------------------------


1. npm init -y
2. npm install -D tailwindcss postcss autoprefixer
3. npx tailwindcss init -p
4. create a css file "input.css". add it to your html and edit it with this content:

@tailwind base;
@tailwind components;
@tailwind utilities;


5. In your tailwind.config.js file replace content:[], with content:["*"],
6. Add "start":"vite" to your scripts in package.json
7. Run npm run start command to start a dev server




















