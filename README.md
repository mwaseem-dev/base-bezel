# 🕒 Base & Bezel – Watch & Jewelry Management System

🚀 A full-stack Laravel-based web application for managing watches and rings with authentication, category-based product management, and admin control system.

---

## 📌 Overview

**Base & Bezel** is a real-world inspired e-commerce style system designed to simulate a product and inventory management platform.

It allows authenticated users to manage products like watches and rings, organize them into categories, and perform full CRUD operations securely.

This project demonstrates how backend systems in real applications handle authentication, authorization, and inventory workflows.

---

## 🎯 Key Features

- 🛍️ Product Management (Watches & Rings)
- 📂 Category-based product organization
- ➕ Add / Edit / Delete products (CRUD operations)
- 🔍 Product listing and detail view
- 🧑‍💼 Admin-side management system
- 📱 Responsive UI design
- 🛒 Guest Order System (No login required to place orders)
- 🚪 Optional Admin Authentication for management access

## 🛒 Order System

- Users can place orders without logging in (Guest Checkout)
- No authentication required for customers
- Simplified ordering flow for better user experience
- Admin manages products and order-related operations

---

## 🛠️ Tech Stack

**Backend:**
- Laravel (PHP Framework)
- MVC Architecture
- Laravel Authentication System

**Frontend:**
- Blade Templates
- Bootstrap

**Database:**
- MySQL

**Tools:**
- Git & GitHub
- VS Code
- Postman (for testing APIs if used)

---

## 🏗️ System Architecture

This project follows the **MVC (Model-View-Controller)** architecture:

- **Models** → Handle database logic and relationships  
- **Controllers** → Manage application business logic  
- **Views** → Handle UI rendering using Blade templates  
- **Guest Flow** → Users can browse and place orders without authentication  
- **Admin Panel** → Restricted access for product management

---
What I Learned
- Implementing guest checkout (real-world e-commerce flow)


---
## ⚙️ Installation & Setup
# Clone the repository
git clone https://github.com/mwaseem-dev/base-bezel.git

# Move into project directory
cd base-bezel

# Install dependencies
composer install
npm install

# Copy environment file
cp .env.example .env

# Generate app key
php artisan key:generate

# Configure database in .env

# Run migrations
php artisan migrate

# Start server
php artisan serve
