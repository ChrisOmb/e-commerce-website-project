# E-Commerce Website

A fully functional e-commerce platform built with Django and Python, allowing users to register as either **Vendors** or **Buyers**. 
Vendors can manage their products and track orders, while buyers can browse products, add them to the cart, and make purchases.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
   - [Vendor Features](#vendor-features)
   - [Buyer Features](#buyer-features)
   - [Admin Panel (Optional)](#admin-panel)
3. [Technologies Used](#technologies-used)
4. [Installation Guide](#installation-guide)
   - [Clone the Repository](#clone-the-repository)
   - [Set Up Virtual Environment](#set-up-virtual-environment)
   - [Install Dependencies](#install-dependencies)
   - [Configure Environment Variables](#configure-environment-variables)
   - [Run Database Migrations](#run-database-migrations)
   - [Create Superuser](#create-superuser)
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

### Admin Panel (Optional)
- **Manage Users**: Admins can manage vendor and buyer accounts.
- **Monitor Orders**: Admins can view all orders and approve/deny vendor products.

## Technologies Used
- **Backend**: Django, Python
- **Frontend**: HTML, CSS, JavaScript, and Bootstrap
- **Database**: MySQL
- **Authentication**: Django's built-in authentication system
- **Payment Gateway**: Stripe/PayPal integration / Daraja API

## Installation Guide

### Clone the Repository
First, clone the repository and navigate into the project directory.
```bash
git clone https://github.com/ChrisOmb/ecommerce-project.git
cd ecommerce-project
```

### Set Up Virtual Environment
Set up a virtual environment to manage project dependencies.
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Install Dependencies
Install all required packages from `requirements.txt`.
```bash
pip install -r requirements.txt
```

### Configure Environment Variables
Create an `.env` file in the project root to store sensitive configurations like database credentials and API keys. Here’s an example setup:

```plaintext
# .env file example
DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_NAME=ecommerce_db
DATABASE_USER=your_username
DATABASE_PASSWORD=your_password
DATABASE_HOST=localhost
DATABASE_PORT=3306

# Stripe or PayPal
STRIPE_SECRET_KEY=your_stripe_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_SECRET=your_paypal_secret
```

Make sure to replace the placeholders with actual values.

### Run Database Migrations
Set up the database by running Django migrations.
```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser
To access the admin panel, create a superuser account.
```bash
python manage.py createsuperuser
```

### Run the Development Server
Start the server to access the platform locally.
```bash
python manage.py runserver
```

Open a browser and go to `http://127.0.0.1:8000` to view the website.

## Usage
Once the server is running, you can navigate the website using the following:
- **Vendor Account**: Register as a vendor to add/manage products and view orders.
- **Buyer Account**: Register as a buyer to browse, add items to the cart, and make purchases.
- **Admin Panel**: Go to `http://127.0.0.1:8000/admin` to manage the website through the admin panel.

## Contributing
If you'd like to contribute, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions, please reach out to Chris at [christopherombwori06@gmail.com].
