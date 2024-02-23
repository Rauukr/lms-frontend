# lsm frontend

### setup instruction
1. Clone the project 
 ---
    git clone--https://github.com/Rauukr/lms-frontend.git
---
2. Move into the directory
---
    cd lsm frontend
---     
3. Install dependencies
---
    npm i
---
4. Run the server
---
    npm run dev
---



### setup instruction for tailswind 

[tailwind official instruction doc](https://tailwindcss.com/docs/guides/create-react-app)

1. Install tailwindcss

---
    npm install -D tailwindcss
---
2. Create tailwind config file 

---
    npx tailwindcss init
---
3. Add file extension to tailwind config file in the content properties

---
    "./src/**/*.{html,js,jsx,ts,tsx}", "./index.html",
---
4. Add the tailwind directive at the top of `indec.css` file 
 
---
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
---    
5. Add the following details in the plugin property of tailwind config

---
     [require("daisyui"), require("@tailwindcss/line-clamp")]
---



### Adding plugins and dependencies
---
    npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyuios react-hot-toats @tailwindcss/line-camp   
---
