Shopify E-Commerce UI
This project is a responsive e-commerce user interface built using HTML, CSS, and JavaScript. The UI features a clean, modern design with an emphasis on usability and aesthetics. Key features include a shopping cart, product listing, and carousel banners.

Features
Responsive Navbar: A fixed navigation bar with links to various sections, including a shopping cart badge.

Hero Section: A dynamic carousel displaying promotional banners with call-to-action buttons.

Product Sections: Product grids that are categorized into Trending, Clothing, and Electronics.

Shopping Cart: A fully functional shopping cart allowing users to add, remove, and update product quantities.

Footer: A detailed footer containing links to company information, brand partners, and contact details.

Project Structure
bash
Copy
Edit
Ecomm-UI/
├── cart.html          # Shopping cart page
├── index.html         # Homepage with product listings
├── css/
│   └── styles.css     # Stylesheet for the project
├── img/               # Images used in the project
│   ├── img1.png
│   ├── img2.png
│   ├── img3.png
│   ├── img4.png
│   ├── img5.jpg
│   └── img6.jpg
├── js/
│   ├── api.js         # Fetches and displays products
│   └── cart.js        # Manages shopping cart functionality
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Shashankshekhar05/Ecom-UI.git
Open the project folder in your code editor and open the index.html file in your browser to get started.

Usage
Homepage (index.html):

View the hero carousel showcasing promotional banners.

Browse products categorized into Trending, Clothing, and Electronics.

Add items to the cart using the "Add to Cart" button.

Cart Page (cart.html):

View and manage the items added to your cart.

Update product quantities or remove items as necessary.

See the total amount and proceed to checkout.

Scripts
js/api.js:

Fetches product data from a backend API (http://localhost:8080/products).

Dynamically populates product grids based on categories (e.g., Trending, Clothing, Electronics).

js/cart.js:

Manages cart operations such as adding, removing, and updating product quantities.

Stores cart data persistently using localStorage.

Styling
This project utilizes custom CSS along with Bootstrap for styling. Key design features include:

Global Theme Colors: Easy customization of the theme via :root variables.

Responsive Design: Fully responsive layout to ensure compatibility across different devices.

Hover Effects: Interactive hover effects applied to buttons and product cards for a better user experience.

Dependencies
Bootstrap 5.3.0

Font Awesome 6.4.2

Future Enhancements
Backend Integration: Implement a backend API for user authentication and order management.

Product Filters & Search: Add filters and search functionality to help users find products more easily.

Payment Gateway: Integrate a payment gateway for the checkout process.

License
This project is licensed under the MIT License. For more details, see the LICENSE file.

Designed by Shashank Shekhar



