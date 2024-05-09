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








