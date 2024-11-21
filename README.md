# E-Commerce Website 

A fully functional e-commerce platform built with Django and Python, allowing users to register as either **Vendors** or **Buyers**.
Vendors can manage their products and track orders, while buyers can browse products, add them to the cart, and make purchases.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
   - [Vendor Features](#vendor-features)
   - [Buyer Features](#buyer-features)
   - [Admin Panel (Optional)](#admin-panel-optional)
3. [Technologies Used](#technologies-used)
4. [Installation Guide](#installation-guide)
   - [Clone the Repository](#clone-the-repository)
   - [Set Up Virtual Environment](#set-up-virtual-environment)
   - [Install Dependencies](#install-dependencies)
   - [Run the Development Server](#run-the-development-server)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction

This e-commerce website is designed to be scalable and customizable. It allows vendors to list and manage products, while buyers can shop for products, place orders, and leave reviews.

## Features

### Vendor Features
- **Register and Login** as a vendor.
- **Add/Update/Delete Products**: Vendors can manage product listings.
- **Manage Orders**: Track and update the status of orders.
- **View Sales History**: Track earnings and order statistics.

### Buyer Features
- **Register and Login** as a buyer.
- **Browse Products**: Search and filter products by categories and prices.
- **Add to Cart**: Buyers can add products to the shopping cart and checkout.
- **Order History**: View past orders and their status.

### Admin Panel 
- **Manage Users**: Admins can manage vendor and buyer accounts.
- **Monitor Orders**: Admins can view all orders and approve/deny vendor products.

## Technologies Used
- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript and (Bootstrap)
- **Database**: MySQL
- **Authentication**: Django's built-in authentication system
- **Payment Gateway**: Stripe/PayPal integration / daraja Api

## Installation Guide

### Clone the Repository
```bash
git clone https://github.com/ChrisOmb/ecommerce-project.git
cd ecommerce-project
