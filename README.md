# tailwind-project

## How To Setup This Project:

    1.npm init -y
    2.npm i -D tailwindcss
    3.Tailwind CSS Intellisense vs Code Plugin for tailwindcss auto suggestion (Brand Cornes)
    4.npx tailwindcss init
    5.Now Create src Folder & output Folder

### src Folder

    6.create tailwind.css file in src folder
    7.tailwind.css file write inside three line code
        1. @tailwind base;
        2. @tailwind components;
        3. @tailwind utilities;

### For vs code custom setup only tailwindcss

    8. create Folder (.vscode) name root folder
    9. create settings.json file in .vscode folder

## create two line code in settings.json file

    {
        "css.validate": false,
        "tailwindCSS.emmetCompletions": true
    }

10. package.json file inside write some code

    "scripts": {
    "build": "tailwindcss -i ./src/tailwind.css -o ./output/tailwind.css -w"
    },

11. npm run build
