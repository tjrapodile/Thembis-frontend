# React + Vite Ecommerce Cart
This ReactJS e-commerce application allows users to browse products, view detailed information, and manage their shopping carts. It features dynamic routing for seamless navigation between products, a shopping cart to store selected items, and real-time updates to the cart's subtotal. The app utilizes React Router DOM for routing and react-hot-toast for user notifications when products are added to the cart.

Features:
Product Browsing: Users can browse a selection of atchar and chilli products.
Product Detail View: Each product has a detailed view displaying its name, price, description, and other relevant information.
Shopping Cart: Users can add products to their cart, view cart contents, and adjust item quantities.
Responsive Design: The application is fully responsive, providing an optimal experience across devices.

Tech Stack:
ReactJS: Frontend framework used to build the user interface.
React Router DOM: For client-side routing, enabling smooth navigation between different views.
react-hot-toast: Provides notifications and alerts for actions like adding items to the cart.

Project Structure:
Components: Reusable UI components such as Navbar, Products, MyCart, and ProductDetail.
Pages: Key pages rendered by the app, corresponding to the main routes.
State Management: Uses React's useState and useEffect hooks for managing application state.
API Integration: The frontend communicates with the backend via RESTful API calls to fetch product data and manage the cart.

"/": Page displaying the list of products.
"/home": Page displaying the home page of the website
"/about": About page for users to understand more about the business
"/cart": The cart page shows the items added by the user.
"/product/": Dynamic route for viewing detailed information about a specific product.

Clone the repository:
git clone https://github.com/tjrapodile/Thembis-frontend.git

Navigate to the project directory:
cd Thembis-frontend

Install dependencies:
npm install

run the application:
npm run dev

Open your browser and visit the site.
