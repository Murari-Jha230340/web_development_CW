# Candy Shop - Web Development Project

## Overview

The Candy Shop is an e-commerce web application designed to allow users to browse, select, and purchase a variety of candies and chocolates. This project was developed as part of the ST4056CEM Introduction to Web Development and Database Systems coursework.

## Features

- **User Registration and Login**: Secure user authentication and account management.
- **Product Listing**: Display of various candy products with detailed descriptions and pricing.
- **Shopping Cart**: Users can add items to their cart, update quantities, and remove items.
- **Order Processing**: A streamlined checkout process where users can place orders.
- **Admin Panel**: Manage products, view orders, and monitor user activity.

## Technology Stack

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript (with jQuery)
  - Bootstrap 5

- **Backend**:
  - PHP 8.2
  - MySQL

- **Development Tools**:
  - XAMPP (for local development)
  - phpMyAdmin (for database management)

## Files Overview

### **Project Files:**
- **about.html**: Contains the static HTML content for the "About Us" page, providing information about the Candy Shop and its offerings.
- **admin.php**: The backend script for the admin panel, allowing administrators to manage products, view orders, and monitor user activities.
- **candy.php**: Displays the list of candy products available in the shop, fetching data from the database.
- **candybabies.png**: An image file used in the website for visual representation, possibly within product listings or promotional sections.
- **cart.php**: Manages the shopping cart functionality, including adding, updating, and removing items.
- **chocolate.php**: Similar to `candy.php`, but specifically for listing chocolate products.
- **connection.php**: Contains the PHP script to establish a connection with the MySQL database, using secure methods to handle database credentials.
- **contact.php**: Provides a contact form for users to reach out to the shop, including server-side validation and email handling.
- **delete.php**: Handles the deletion of records from the database, such as removing items from the shopping cart or admin panel.

### **Images Directory:**
- **images/**: This folder contains all the image assets used in the website, such as product images and branding visuals.

## Coursework Details

This project is part of the ST4056CEM Introduction to Web Development and Database Systems coursework. The aim of this coursework is to demonstrate the application of web development techniques and database management skills. Below are the key learning outcomes addressed by this project:

1. **Core Principles of Web Development**: Demonstrated by creating a user-friendly, responsive website using HTML, CSS, and JavaScript.
2. **Database Integration**: Implemented a MySQL database to handle user data, product listings, and transactions securely.
3. **Security Best Practices**: Applied security measures such as password hashing, prepared statements, and session management.
4. **Full-Stack Development**: Combined front-end and back-end development to create a fully functional e-commerce platform.

## Installation

### Prerequisites

- XAMPP or any other server environment with PHP and MySQL.
- A web browser (e.g., Chrome, Firefox, Edge).

### Steps

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/candy-shop.git
    ```
    Alternatively, download the project as a ZIP file and extract it.

2. **Move the Project to the Server Directory**:
    - If using XAMPP, move the project folder to `C:/xampp/htdocs/`.

3. **Start the Apache and MySQL Services**:
    - Open the XAMPP control panel and start both the Apache and MySQL services.

4. **Create the Database**:
    - Open `phpMyAdmin` in your browser (`http://localhost/phpmyadmin`).
    - Create a new database named `candy_shop`.
    - Import the SQL file located at `database/candy_shop.sql` to set up the necessary tables.

5. **Configure Database Connection**:
    - Open the `connection.php` file in the project’s root directory.
    - Update the database configuration details (host, username, password, and database name) as per your local setup.

    ```php
    $host = 'localhost';
    $db   = 'candy_shop';
    $user = 'root';
    $pass = ''; // Your MySQL root password
    ```

6. **Access the Website**:
    - Open your web browser and navigate to `http://localhost/candy-shop/`.

## Usage

- **User Registration**: New users can register by clicking the "Register" link on the homepage.
- **Product Browsing**: Browse through available products on the homepage and category pages.
- **Shopping Cart**: Add products to your cart, adjust quantities, and proceed to checkout.
- **Admin Panel**: Admins can log in to manage the product inventory and view orders.

## Security Features

- **Password Hashing**: User passwords are securely hashed before storage.
- **Input Validation**: Client-side and server-side validation to prevent SQL injection and XSS attacks.
- **Session Management**: Secure handling of user sessions to prevent unauthorized access.

## Future Enhancements

- Integration of payment gateways.
- Implementation of user profiles with order history and personalized recommendations.
- Addition of product reviews and ratings.

## Contributors

- [Murari Jha]([https://github.com/y](https://github.com/Murari-Jha230340))

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
