# 1. Install Tailwind Css

Go to <tailwind.css>

Docs -> Framework Guides -> Laravel -> Install TailwindCss

> npm install -D tailwindcss postcss autoprefixer

> npx tailwindcss init -p

# 2. Configure your template paths

go to->  tailwind.config.js  file

paste this in content and remove old content 

    content: [
        "./resources/**/*.blade.php",
        "./resources/**/*.js",
        "./resources/**/*.vue",
    ],

# 3. Add the Tailwind directives to your CSS

go to-> app.css  

remove old and add this 

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

# 4. 

@vite(['resources/css/app.css', 'resources/js/app.js']) 

add this in end of the header tag.. 

# 5.

> npm run build

> npm run dev
