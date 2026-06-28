# ECommerce Website using Django

A full-featured e-commerce web application built with Django and PostgreSQL. The project is designed using Django's app-based architecture and supports multiple user roles including Admin, Seller, and Buyer.

## Project Overview

ECommerce Lite provides a complete online shopping experience where sellers can manage products, buyers can browse and purchase items, and administrators can oversee the entire platform.

## Features

### Authentication
- User Registration & Login
- Custom User Model
- Role-Based Access (Admin, Seller, Buyer)
- Profile Management

### Product Management
- Product Categories
- Product Listings
- Product Details
- Multiple Product Images
- Inventory Management
- Search & Filtering

### Shopping
- Shopping Cart
- Wishlist
- Checkout Process
- Order Placement
- Order History

### Payments
- Payment Processing
- Payment History
- Order Status Tracking

### Reviews
- Product Ratings
- Customer Reviews

### Admin Dashboard
- User Management
- Product Management
- Order Management
- Sales Monitoring

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Django | Backend Framework |
| PostgreSQL | Database |
| HTML5 | Frontend Structure |
| CSS3 | Styling |
| JavaScript | Client-side Interactivity |

## Project Structure

```
ecommercelite/
│
├── config/                 # Django project configuration
├── accounts/               # Authentication & User Management
├── products/               # Product Management
├── cart/                   # Shopping Cart
├── orders/                 # Orders
├── payments/               # Payments
├── reviews/                # Product Reviews
├── wishlist/               # Wishlist
├── coupons/                # Coupons & Discounts
├── dashboard/              # Admin/Seller Dashboard
│
├── templates/
├── static/
├── media/
├── docs/
│
├── manage.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

## User Roles

### Admin
- Manage users
- Manage products
- Manage orders
- View platform statistics

### Seller
- Add products
- Update products
- Manage inventory
- Track customer orders

### Buyer
- Browse products
- Add items to cart
- Manage wishlist
- Place orders
- Write reviews

## Database

The project uses PostgreSQL with relationships between:

- Users
- Products
- Product Images
- Cart
- Cart Items
- Orders
- Order Items
- Payments
- Addresses
- Reviews

## Installation

### Clone Repository

```bash
git clone <repository-url>
cd ecommercelite
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment

Create a `.env` file and add your PostgreSQL credentials.

### Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Open your browser:

```
http://127.0.0.1:8000/
```

## Future Enhancements

- Email Notifications
- Product Recommendations
- Coupon System
- Sales Analytics
- REST API
- Responsive UI Improvements
- Performance Optimization
- Deployment

## Author

**Bala Adhish N D**
