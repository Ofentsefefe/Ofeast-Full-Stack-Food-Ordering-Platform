# Ofeast-Full-Stack-Food-Ordering-Platform
Ofeast is a modern food ordering and delivery platform designed to connect customers with local food vendors. The platform allows users to browse menus, place orders, choose pickup or delivery, manage their profiles, and track their orders. Built with a focus on creating a convenient digital ordering experience for the surrounding community
# 🍽️ Ofeast

<p align="center">
  <img src="assets/logo/ofeast-logo.png" alt="Ofeast Logo" width="180">
</p>

<h3 align="center">
  Your Cravings Deserve the Best.
</h3>

<p align="center">
  A modern food ordering and delivery platform connecting customers
  with local food businesses.
</p>

<p align="center">
  <a href="https://ofeast.vercel.app/">🌐 Live Demo</a>
  •
  <a href="#features">Features</a>
  •
  <a href="#technology-stack">Technology</a>
  •
  <a href="#system-architecture">Architecture</a>
  •
  <a href="#roadmap">Roadmap</a>
</p>

---

## 📖 Overview

**Ofeast** is a full-stack food ordering and delivery platform designed to make ordering from local food businesses faster, easier and more convenient.

The platform allows customers to discover food businesses, browse menus, add items to a cart, place orders, make online payments and monitor the progress of their orders.

Ofeast is being designed with a multi-role architecture that supports:

- 👤 Customers
- 🏪 Food businesses
- 👨‍💼 Administrators
- 🚚 Delivery drivers

The platform initially focuses on serving students and customers around educational institutions and local communities, with a long-term vision of expanding into broader communities and township markets across South Africa.

---

# 🎯 Problem Statement

Many students and local customers still rely on traditional ordering methods when purchasing food.

Customers may have to:

- Wait in long queues
- Visit food businesses physically
- Communicate through multiple messaging platforms
- Wait without knowing the status of an order
- Use cash or different payment methods
- Search for nearby food businesses manually

At the same time, smaller food businesses may rely on:

- Manual order management
- WhatsApp messages
- Paper-based processes
- Verbal communication
- Limited order tracking
- Manual payment verification

These processes can become difficult to manage as the number of customers and orders increases.

---

# 💡 The Ofeast Solution

Ofeast provides a centralized digital platform where customers and food businesses can interact through one system.

### Customers

Customers can:

1. Discover food businesses
2. Browse menus
3. Select food items
4. Add items to their cart
5. Place orders
6. Make online payments
7. Track order progress
8. Choose between pickup and delivery
9. View previous orders
10. Manage their profile and preferences

### Food Businesses

Food businesses can receive and manage customer orders through dedicated business functionality.

Businesses can:

- View incoming orders
- Manage order statuses
- Manage menu items
- Monitor orders belonging to their business
- Move orders through the preparation workflow

### Delivery

Ofeast is being developed to support a delivery workflow where drivers can receive delivery assignments and help customers receive their orders.

---

# ✨ Features

## 👤 Customer Features

### Authentication

- User registration
- User login
- Authentication system
- Protected application routes
- Password handling
- Authentication middleware
- User session management

### Food Discovery

- Browse available food businesses
- View individual shop information
- Browse food menus
- Search for food
- View available menu items
- Save favourite items/businesses

### Shopping Cart

- Add food items to cart
- Remove food items
- Update quantities
- View cart summary
- Manage cart state

### Ordering

- Place food orders
- View order details
- View order history
- Monitor order status
- Order preparation workflow
- Pickup and delivery support

### Payments

Ofeast integrates online payment functionality through **PayFast**.

The backend includes payment processing and webhook functionality for handling payment-related events.

### Location

The platform includes location-related functionality designed to support:

- Customer location
- Location-aware experiences
- Delivery functionality
- Map-based features
- Future live delivery tracking

### Favourites

Customers can save food businesses or menu items for easier access in the future.

### Profile

Customers can manage their account and access their personal application features through their profile.

---

# 🏪 Food Business Features

Ofeast is designed to support multiple independent food businesses on the same platform.

Each business can have its own:

- Business profile
- Menu
- Menu items
- Orders
- Order management workflow

### Business Order Management

Food businesses can manage their incoming orders and update order progress.

Example workflow:

```text
New Order
    ↓
Preparing
    ↓
Ready
    ↓
Completed / Collected / Delivered

### System Architecture
Example workflow:

```text


                         ┌──────────────────────┐
                         │      CUSTOMER        │
                         │    React / Vite      │
                         └──────────┬───────────┘
                                    │
                                    │ HTTP / API
                                    ▼
                         ┌──────────────────────┐
                         │     OFEAST API       │
                         │   Node.js / Express  │
                         └──────────┬───────────┘
                                    │
              ┌─────────────────────┼─────────────────────┐
              │                     │                     │
              ▼                     ▼                     ▼
      ┌──────────────┐      ┌──────────────┐      ┌──────────────┐
      │  PostgreSQL  │      │   PayFast    │      │  Socket.io   │
      │    Prisma    │      │   Payments   │      │  Real-Time   │
      └──────────────┘      └──────────────┘      └──────────────┘
                                    │
                                    ▼
                           ┌─────────────────┐
                           │     WEBHOOKS    │
                           │ Payment Events  │
                           └─────────────────┘

              ┌─────────────────────┼─────────────────────┐
              │                     │                     │
              ▼                     ▼                     ▼
       ┌─────────────┐       ┌─────────────┐       ┌─────────────┐
       │    SHOP     │       │    ADMIN    │       │   DRIVER    │
       │   SYSTEM    │       │   SYSTEM    │       │   SYSTEM    │
       └─────────────┘       └─────────────┘       └─────────────┘

