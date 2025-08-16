
PS G:\agency-ai> npm create vite@latest 

> npx
> create-vite

│
◇  Project name:             // Project name add -> . mean - that will create using project name 
│  .
│
◇  Current directory is not empty. Please choose how to proceed:
│  Remove existing files and continue
│
◇  Select a framework:
│  React
│
◇  Select a variant:
│  JavaScript
│
◇  Scaffolding project in G:\agency-ai...
│
└  Done. Now run:

  npm install
  npm run dev


  ## clear the project
  remove the app.css file 

  delete all the code in app.jsx and rafce

  delete all the code in index.css

  change the title in index.html file

  add the favicon icon also - that should replace in public folder

  ## add tailwind css to project
 open browser and type - vite tailwind css 

 npm install tailwindcss @tailwindcss/vite
 
 ## add google fonts
open browser and type - google fonts
 type manrope and get the emberded code import statement and 

add 

```bash

@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&family=Outfit:wght@100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

@import "tailwindcss";

*{
  font-family: "Manrope", sans-serif;
  font-weight: 500;
}

```

add

```bash 

@import "tailwindcss";

@theme{
  --color-primary: #5044E5;
}

@custom-variant dark (&:where(.dark, .dark *));

```

-----------------------------------------------------------

## navigation bar

