# 🕒 Base & Bezel – Fashion Accessories Management System

A modern full-stack **Laravel** web application for managing fashion accessories (watches and rings) with complete Admin Panel, Guest Checkout, and Inventory Management.

![Project Banner](screenshots/banner.png) <!-- Add a good main screenshot here later -->

## 📌 Overview
**Base & Bezel** is a real-world inspired e-commerce management system built with Laravel. It allows customers to browse products and place orders as guests, while admins have full control over products, categories, and inventory.

This project demonstrates clean code structure, proper MVC architecture, and real e-commerce features commonly used in professional web applications.

## 🎯 Key Features
- ✅ Full **CRUD** Operations (Create, Read, Update, Delete) for Products
- 📂 Category-wise Product Organization
- 👤 User Authentication & Authorization
- 🛒 **Guest Checkout System** (Order placement without login)
- 🧑‍💼 Dedicated Admin Dashboard
- 🔍 Product Listing with Detail View
- 📱 Fully Responsive & Mobile-Friendly Design
- 🛍️ Clean and Modern User Interface
- 🔐 Secure Authentication System

## 🛠️ Tech Stack
- **Backend**: Laravel (PHP Framework)
- **Architecture**: MVC Pattern
- **Frontend**: Blade Templates, Bootstrap 5
- **Database**: MySQL
- **Tools**: Git, GitHub, VS Code, Postman

## 📸 Screenshots

*(Add 4-6 screenshots here)*

![Product Listing](screenshots/product-listing.png)  
![Product Detail](screenshots/product-detail.png)  
![Admin Dashboard](screenshots/admin-dashboard.png)  
![Guest Checkout](screenshots/guest-checkout.png)

## What I Learned
- Implementing real-world **Guest Checkout** functionality
- Managing Authentication and Authorization
- Building scalable CRUD operations
- Creating responsive designs with Bootstrap

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/mwaseem-dev/base-bezel.git

# Go into the project directory
cd base-bezel

# Install PHP dependencies
composer install

# Install frontend dependencies
npm install && npm run dev

# Copy environment configuration
cp .env.example .env

# Generate application key
php artisan key:generate

# Configure your database in .env file

# Run database migrations
php artisan migrate

# Start development server
php artisan serve
