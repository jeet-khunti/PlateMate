# Food Ordering Website

## Project Overview

This is a complete food ordering website that allows users to browse menus, search for food items, add them to a cart, and place orders. Registered users can manage their profiles, view past orders, and update their delivery address. The system also includes pages for login, registration, and contact.

The project is built using **HTML**, **CSS**, **JavaScript**, **PHP**, and **MySQL**, offering a full-stack solution for online food ordering.


## Features and User Functionality

- User registration and login (`register.php`, `login.php`)
- View homepage and about section (`home.php`, `about.php`)
- Browse and search food items (`menu.php`, `search.php`)
- View food categories (`category.php`)
- Add items to cart and manage cart (`cart.php`)
- Checkout and order management (`checkout.php`, `orders.php`)
- View and update user profile (`profile.php`, `update_profile.php`, `update_address.php`)
- Quick view of food items (`quick_view.php`)
- Contact the site team (`contact.php`)

## Project Structure

> **Note**: Image assets and static files (e.g., `images/`, `.jpg`, `.png`) are not listed here for brevity.

```plaintext
food_website/
├── about.php
├── cart.php
├── category.php
├── checkout.php
├── contact.php
├── food_db.sql
├── home.php
├── login.php
├── menu.php
├── orders.php
├── profile.php
├── quick_view.php
├── register.php
├── search.php
├── update_address.php
├── update_profile.php
└── .git/
```

## Database

The project uses a MySQL database. Import the provided SQL file `food_db.sql` into your MySQL server to set up the necessary tables and data.

Update your database connection settings in the relevant PHP configuration file(s), typically using `mysqli`.

## Setup Instructions

1. Extract the project folder (`food_website`) into your server directory (e.g., `htdocs` if using XAMPP).
2. Create a database in MySQL and import the `food_db.sql` file.
3. Configure database credentials in the PHP connection file.
4. Start Apache and MySQL services.
5. Visit the application in your browser at:
   ```
   http://localhost/food_website
   ```

## Technologies Used

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL
