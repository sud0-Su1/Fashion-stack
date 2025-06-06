# Full-stack-fashion
# Full-Stack Clothing Website

A modern full-stack clothing e-commerce web application with user authentication, product browsing, and seamless checkout options.

## Features

- **User Authentication**  
  Secure login and registration system for customers.

- **Product Catalog**  
  Browse and select from a wide range of clothing products.

- **Shopping Cart & Checkout**  
  Add items to cart and checkout with multiple payment options: Stripe (credit/debit card payments), Razorpay (India-specific payment gateway), and Cash on Delivery (COD).

- **Admin Panel**  
  Dedicated admin interface for managing products, orders, and users.

## Screenshots

![Homepage](path/to/homepage_screenshot.png)  
*Homepage displaying product catalog*

![Login Page](path/to/login_screenshot.png)  
*User login page*

![Checkout Page](path/to/checkout_screenshot.png)  
*Checkout page with multiple payment options*

![Admin Dashboard](path/to/admin_dashboard_screenshot.png)  
*Admin dashboard for managing store*

## Technologies Used

- Frontend: React.js / Next.js (confirm based on your project)  
- Backend: Node.js, Express.js  
- Database: MongoDB / MySQL (confirm your DB)  
- Payment Integrations: Stripe, Razorpay  
- Authentication: JWT / Session-based (confirm)

## Installation

1. Clone the repository  
```bash
git clone https://github.com/sud0-Su1/Full-stack-clothing.git

2. Navigate to the project directory
```cd Full-stack-clothing

3.Install dependencies
```npm install

4.Configure environment variables
```Create a .env file and add your Stripe keys, Razorpay keys, database credentials, and JWT secrets. Example:
   STRIPE_SECRET_KEY=your_stripe_secret  
   RAZORPAY_KEY_ID=your_razorpay_key  
   RAZORPAY_KEY_SECRET=your_razorpay_secret  
   DB_URI=your_database_connection_string
   JWT_SECRET=your_jwt_secret

5.Start the development server
```npm run dev


## Usage
Visit the homepage to browse products.

Register or log in to add products to your cart.

Proceed to checkout and select a payment method.

Admins can log in to the admin page to manage the store.



