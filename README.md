# 🛒 Full-Stack E-Commerce Website

A complete, responsive E-Commerce platform built with **PHP**, **MySQL**, and **Vanilla JavaScript**. This project features a robust administrative panel for inventory management and a clean, user-friendly storefront for customers.

---

## ✨ Key Features

### 👤 Customer Side
- **User Authentication:** Secure registration and login system.
- **Product Discovery:** Browse by categories, search functionality, and "Quick View" modals.
- **Shopping Cart & Wishlist:** Fully functional cart system with real-time updates.
- **Checkout System:** Integrated order processing and address management.
- **Order Tracking:** Users can view their order history and status.
- **Responsive Design:** Optimized for desktops, tablets, and mobile devices.

### 🛡️ Admin Side (Dashboard)
- **Product Management:** Add, edit, and delete products with image uploads.
- **Order Management:** View and update the status of customer orders.
- **User Management:** Monitor registered accounts.
- **Message System:** View inquiries sent via the contact form.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6)
- **Backend:** PHP (OOP concepts used)
- **Database:** MySQL
- **Icons:** FontAwesome

---

## 🚀 Getting Started

Follow these steps to set up the project on your local machine (using XAMPP/WAMP):

### 1. Clone the Repository
```bash
git clone [https://github.com/MihirTamboli/E-Commerce-Website.git](https://github.com/MihirTamboli/E-Commerce-Website.git)

```

### 2. Database Configuration

1. Open **phpMyAdmin**.
2. Create a new database named `shop_db`.
3. Click on the **Import** tab and select the `shop_db.sql` file from the project root.
4. Click **Go** to execute the SQL and create the tables.

### 3. Connect to the Database

Ensure your database connection settings are correct in the `components/connect.php` file:

```php
$db_name = 'mysql:host=localhost;dbname=shop_db';
$user_name = 'root';
$user_password = '';

```

### 4. Run the Project

* Move the project folder to your local server directory (e.g., `C:/xampp/htdocs/`).
* Open your browser and go to: `http://localhost/E-Commerce-Website/home.php`

---

## 📁 Project Structure

* `/admin`: All files related to the administrative dashboard.
* `/components`: Reusable code snippets (header, footer, DB connection).
* `/css`: Stylesheets for both user and admin panels.
* `/images`: Static site assets and icons.
* `/js`: Frontend logic and interactivity.
* `/uploaded_img`: Destination folder for product images uploaded via Admin.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


**Developed by [Mihir Tamboli**](https://www.google.com/search?q=https://github.com/MihirTamboli)

```
