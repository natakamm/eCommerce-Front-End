### Deployed Links:

Front-end: https://e-commerce-185fdc.netlify.app/
Back-end: https://ecommerce-api-k4pz.onrender.com

The frontend of the e-commerce shop is a React application that enables users to manage products and categories through interaction with a custom-built backend API.

Product Management: Users can create new products, assign them to multiple categories, and edit existing products. The application allows users to modify product details like price, description, and category assignment. However, product deletion is not yet implemented in the frontend.

Category Management: Full CRUD functionality for categories is available. Users can create, edit, and delete categories as needed, providing flexibility in organizing products.

API Interaction: The frontend uses `POST`, `PUT`, and `GET` methods to interact with the backend API for product and category management.

- Creating new products and categories.
- Editing existing products and categories.
- Viewing product and category details.
While the frontend offers core features for product and category management, the backend API supports additional functionalities that were not fully implemented due to time constraints. This provides a solid foundation for expanding the app in the future.


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### Install Vite

`npm create vite@latest new-react-app -- --template react`

### Navigate into your project directory:

`cd new-react-app`

### Install Dependencies

`npm install`

### Install and Configure Tailwind CSS

Next, we will install Tailwind CSS

### Install Tailwind CSS

`npm install -D tailwindcss postcss autoprefixer`

### Initialize Tailwind CSS

`npx tailwindcss init -p`

### Configure Tailwind

### In the tailwind.config.js file, replace the content with the following:

```/** @type {import('tailwindcss').Config} */
export default {
content: ['./index.html', './src/**/\*.{js,ts,jsx,tsx}'],
theme: {
extend: {}
},
plugins: []
};
```

### Add Tailwind Directives

Open the index.css file located in the src folder, and replace its content with the Tailwind CSS directives:

@tailwind base;
@tailwind components;
@tailwind utilities;

### Install Daisy UI

`npm i -D daisyui`

### Configure Daisy UI

In your tailwind.config.js file, add daisyui to the plugins array:

```/** @type {import('tailwindcss').Config} */
import daisyui from "daisyui"
export default {
content: ['./index.html', './src/**/\*.{js,ts,jsx,tsx}'],
theme: {
extend: {}
},
plugins: [daisyui]
};
```

Check out the various UI components from [Daisy](https://daisyui.com/components/) here.


