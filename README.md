# 🍽️ Ofeast — Full-Stack Food Ordering & Delivery Platform

<p align="center">
  <img src="assets/logo/ofeast-logo.png" alt="Ofeast Logo" width="180">
</p>

<h3 align="center">
  Your Cravings Deserve the Best.
</h3>

<p align="center">
  A full-stack food ordering and delivery platform connecting customers
  with local food businesses through a modern digital ordering experience.
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
  <a href="#project-structure">Project Structure</a>
  •
  <a href="#roadmap">Roadmap</a>
</p>

---

> **⚠️ Repository Status**
>
> This repository is currently a **showcase and documentation hub** for the
> Ofeast platform. The production source code is kept **private** while the
> project is under active development. Screenshots and documentation will be
> updated as the platform evolves.

---

# 📑 Table of Contents

- [📸 Application Preview](#-application-preview)
  - [🏠 Customer Experience](#-customer-experience)
    - [Home & Food Discovery](#home--food-discovery)
    - [🍔 Food Menu](#-food-menu)
    - [🛒 Shopping Cart](#-shopping-cart)
    - [💳 Checkout & Payment](#-checkout--payment)
    - [📦 Order Tracking](#-order-tracking)
  - [🏪 Food Business Experience](#-food-business-experience)
    - [Shop Dashboard](#shop-dashboard)
  - [👨‍💼 Administration](#-administration)
    - [Admin Dashboard](#admin-dashboard)
  - [📱 Mobile Experience](#-mobile-experience)
- [📖 Overview](#-overview)
- [🎯 Problem Statement](#-problem-statement)
- [💡 The Ofeast Solution](#-the-ofeast-solution)
  - [Customer Ordering Journey](#customer-ordering-journey)
- [✨ Features](#-features)
- [🛠️ Technology Stack](#️-technology-stack)
  - [Frontend](#frontend)
  - [Backend](#backend)
  - [Database & Storage](#database--storage)
  - [DevOps & Tooling](#devops--tooling)
- [🏗️ System Architecture](#️-system-architecture)
  - [Data Flow](#data-flow)
- [📁 Project Structure](#-project-structure)
  - [Why Two Separate Projects?](#why-two-separate-projects)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Variables](#environment-variables)
  - [Running the Application](#running-the-application)
- [🗺️ Roadmap](#️-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📬 Contact](#-contact)

---

# 📸 Application Preview

Ofeast provides a modern digital ordering experience that connects
customers with local food businesses.

The platform covers the complete ordering journey — from discovering
food and managing a cart to payment, order preparation, and delivery.

> **📌 Note:** Screenshots below are placeholders. Actual application
> screenshots will be added as the platform is finalized.

---

## 🏠 Customer Experience

### Home & Food Discovery

<p align="center">
  <img
    src="assets/screenshots/home.png"
    alt="Ofeast Customer Home"
    width="850"
  >
</p>

The Ofeast home experience allows customers to discover available
food businesses and access the main ordering features of the platform.

---

### 🍔 Food Menu

<p align="center">
  <img
    src="assets/screenshots/menu.png"
    alt="Ofeast Food Menu"
    width="850"
  >
</p>

Customers can browse available food items, explore menus, and select
products they want to order.

---

### 🛒 Shopping Cart

<p align="center">
  <img
    src="assets/screenshots/cart.png"
    alt="Ofeast Shopping Cart"
    width="850"
  >
</p>

The shopping cart allows customers to review selected items, update
quantities, remove products, and prepare their order for checkout.

---

### 💳 Checkout & Payment

<p align="center">
  <img
    src="assets/screenshots/checkout.png"
    alt="Ofeast Checkout and Payment"
    width="850"
  >
</p>

Ofeast integrates online payment functionality through PayFast,
allowing customers to complete their orders digitally.

---

### 📦 Order Tracking

<p align="center">
  <img
    src="assets/screenshots/order-tracking.png"
    alt="Ofeast Order Tracking"
    width="850"
  >
</p>

Customers can monitor the progress of their orders throughout the
preparation and fulfillment process.

---

## 🏪 Food Business Experience

### Shop Dashboard

<p align="center">
  <img
    src="assets/screenshots/shop-dashboard.png"
    alt="Ofeast Food Business Dashboard"
    width="850"
  >
</p>

Food businesses have dedicated functionality for managing their
incoming orders and updating order progress.

---

## 👨‍💼 Administration

### Admin Dashboard

<p align="center">
  <img
    src="assets/screenshots/admin-dashboard.png"
    alt="Ofeast Admin Dashboard"
    width="850"
  >
</p>

The administrative system is designed to provide platform-level
management of users, businesses, drivers, orders, and applications.

---

## 📱 Mobile Experience

<p align="center">
  <img
    src="assets/screenshots/mobile.png"
    alt="Ofeast Mobile Experience"
    width="400"
  >
</p>

Ofeast is designed with responsive experiences in mind, allowing the
platform to adapt to different screen sizes and devices.

---

# 📖 Overview

**Ofeast** is a full-stack food ordering and delivery platform designed
to make ordering from local food businesses faster, easier, and more
convenient.

The platform provides a centralized digital experience where customers
can discover food businesses, browse menus, manage their carts, place
orders, make online payments, and monitor order progress.

Ofeast follows a multi-role architecture supporting:

- 👤 Customers
- 🏪 Food Businesses
- 👨‍💼 Administrators
- 🚚 Delivery Drivers

The platform initially focuses on students and customers around
educational institutions and surrounding communities, with a long-term
vision of expanding into broader communities and township markets
across South Africa.

---

# 🎯 Problem Statement

Many customers still rely on traditional methods when ordering food
from local businesses.

Customers may have to:

- Wait in physical queues
- Visit food businesses to place orders
- Communicate through multiple messaging platforms
- Wait without knowing the status of an order
- Use different payment methods
- Search manually for nearby food businesses

At the same time, smaller food businesses may rely on:

- WhatsApp messages
- Paper-based processes
- Verbal communication
- Manual payment verification
- Limited order tracking
- Manual coordination between customers and staff

These processes can become increasingly difficult to manage as
customer demand and order volumes grow.

---

# 💡 The Ofeast Solution

Ofeast brings customers and food businesses together through a
centralized digital platform.

Instead of relying on separate communication and ordering channels,
customers can manage the ordering process through one application.

### Customer Ordering Journey

```text
Discover
   ↓
Browse Food Business
   ↓
Browse Menu
   ↓
Add to Cart
   ↓
Checkout
   ↓
Payment
   ↓
Order Preparation
   ↓
Pickup / Delivery
   ↓
Order Completed
```

---

# ✨ Features

| Feature | Description |
|---|---|
| 🔐 Authentication | Secure sign-up, login, and role-based access control |
| 🏪 Multi-Vendor Support | Multiple food businesses on a single platform |
| 🍔 Menu Management | Businesses can create, update, and manage menus |
| 🛒 Shopping Cart | Persistent cart with quantity and item management |
| 💳 Online Payments | Integrated PayFast payment gateway |
| 📦 Order Tracking | Real-time order status updates |
| 🚚 Delivery Coordination | Driver assignment and delivery workflow |
| 👨‍💼 Admin Dashboard | Platform-wide management and oversight |
| 📱 Responsive Design | Optimized for desktop, tablet, and mobile |
| 📧 Email Notifications | Order confirmations and updates via SMTP |
| 🔔 Notifications | Order and status notifications for all roles |

---

# 🛠️ Technology Stack

### Frontend

| Technology | Purpose |
|---|---|
| React | Component-based UI library |
| Vite | Fast build tool and dev server |
| Tailwind CSS | Utility-first styling |
| React Router | Client-side routing |
| Axios | HTTP client for API communication |

### Backend

| Technology | Purpose |
|---|---|
| Node.js | Server runtime |
| Express.js | REST API framework |
| Prisma | Type-safe ORM for database access |
| PostgreSQL | Relational database |
| Neon | Serverless PostgreSQL hosting |
| JWT | Authentication and authorization |
| PayFast | Payment gateway integration |
| Multer | File and image uploads |
| Nodemailer (SMTP) | Transactional email delivery |

### Database & Storage

| Technology | Purpose |
|---|---|
| PostgreSQL | Relational database |
| Prisma | ORM, schema, and migrations |
| Neon | Cloud-hosted PostgreSQL database |
| Cloudinary | Image storage and optimization |

### DevOps & Tooling

| Technology | Purpose |
|---|---|
| Git & GitHub | Version control |
| Vercel | Frontend deployment |
| Render / Railway | Backend deployment |
| Postman | API testing |
| Prisma Studio | Database GUI and inspection |

---

# 🏗️ System Architecture

Ofeast follows a **client-server architecture** with a clear separation
between the frontend, backend, and database layers.

```text
┌─────────────────────────────────────────────────────────────┐
│                        CLIENT LAYER                         │
│                                                             │
│   ┌──────────────┐   ┌──────────────┐   ┌──────────────┐   │
│   │  Customer    │   │   Business   │   │    Admin     │   │
│   │     App      │   │   Dashboard  │   │   Dashboard  │   │
│   └──────┬───────┘   └──────┬───────┘   └──────┬───────┘   │
│          │                  │                  │            │
│          └──────────────────┼──────────────────┘            │
│                             │                               │
└─────────────────────────────┼───────────────────────────────┘
                              │ HTTPS / REST API
                              ▼
┌─────────────────────────────────────────────────────────────┐
│                        SERVER LAYER                         │
│                                                             │
│   ┌─────────────────────────────────────────────────────┐   │
│   │              Express.js REST API                     │   │
│   ├──────────────┬──────────────┬───────────────────────┤   │
│   │  Auth Routes │ Order Routes │  Menu Routes          │   │
│   │  User Routes │ Payment      │  Business Routes      │   │
│   │  Admin Routes│ Routes       │  Driver Routes        │   │
│   └──────────────┴──────────────┴───────────────────────┘   │
│                                                             │
│   ┌──────────────┐   ┌──────────────┐   ┌──────────────┐   │
│   │  JWT Auth    │   │  PayFast     │   │  Cloudinary  │   │
│   │  Middleware  │   │  Integration │   │  Uploads     │   │
│   └──────────────┘   └──────────────┘   └──────────────┘   │
│                                                             │
│   ┌──────────────┐   ┌──────────────────────────────────┐   │
│   │  Prisma ORM  │   │  Nodemailer (SMTP Email Service) │   │
│   └──────┬───────┘   └──────────────────────────────────┘   │
│          │                                                  │
└──────────┼──────────────────────────────────────────────────┘
           │
           ▼
┌─────────────────────────────────────────────────────────────┐
│                        DATA LAYER                           │
│                                                             │
│   ┌─────────────────────────────────────────────────────┐   │
│   │           Neon (Serverless PostgreSQL)              │   │
│   ├──────────┬──────────┬──────────┬───────────────────┤   │
│   │  Users   │  Orders  │  Menus   │  Businesses       │   │
│   │  Drivers │  Carts   │  Items   │  Payments         │   │
│   └──────────┴──────────┴──────────┴───────────────────┘   │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### Data Flow

```text
Customer / Business / Admin / Driver
                │
                ▼
        React Frontend (Vite)
                │
                │ REST API (HTTPS)
                ▼
        Express.js Backend
                │
        ┌───────┼───────────┬────────────┐
        ▼       ▼           ▼            ▼
    Prisma   PayFast   Cloudinary   SMTP Email
      │
      ▼
    Neon (PostgreSQL)
```

---

# 📁 Project Structure

Ofeast is organized as **two independent projects** — a React + Vite
frontend and a Node.js + Express backend — each with its own
`package.json`, dependencies, and configuration. They are kept in
separate directories so the frontend and backend can be developed,
built, and deployed independently.

```text
ofeast/                                 # Project root
│
├── 📁 frontend/                        # React + Vite application
│   │
│   ├── public/                         # Static assets served as-is
│   │   ├── favicon.ico
│   │   └── robots.txt
│   │
│   ├── src/
│   │   ├── assets/                     # Images, fonts, icons
│   │   │   ├── images/
│   │   │   └── icons/
│   │   │
│   │   ├── components/                 # Reusable UI components
│   │   │   ├── common/                 # Buttons, inputs, modals, loaders
│   │   │   ├── layout/                 # Navbar, sidebar, footer
│   │   │   ├── cart/                   # Cart-related components
│   │   │   ├── menu/                   # Menu & food item components
│   │   │   ├── order/                  # Order & tracking components
│   │   │   └── dashboard/              # Shared dashboard components
│   │   │
│   │   ├── pages/                      # Route-level page components
│   │   │   ├── customer/               # Customer-facing pages
│   │   │   │   ├── Home.jsx
│   │   │   │   ├── Menu.jsx
│   │   │   │   ├── Cart.jsx
│   │   │   │   ├── Checkout.jsx
│   │   │   │   └── OrderTracking.jsx
│   │   │   │
│   │   │   ├── business/               # Business dashboard pages
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── MenuManagement.jsx
│   │   │   │   └── Orders.jsx
│   │   │   │
│   │   │   ├── admin/                  # Admin dashboard pages
│   │   │   │   ├── Dashboard.jsx
│   │   │   │   ├── Users.jsx
│   │   │   │   ├── Businesses.jsx
│   │   │   │   └── Drivers.jsx
│   │   │   │
│   │   │   ├── driver/                 # Driver-facing pages
│   │   │   │   └── Deliveries.jsx
│   │   │   │
│   │   │   └── auth/                   # Authentication pages
│   │   │       ├── Login.jsx
│   │   │       └── Register.jsx
│   │   │
│   │   ├── context/                    # React context providers
│   │   │   ├── AuthContext.jsx
│   │   │   ├── CartContext.jsx
│   │   │   └── OrderContext.jsx
│   │   │
│   │   ├── hooks/                      # Custom React hooks
│   │   │   ├── useAuth.js
│   │   │   ├── useCart.js
│   │   │   └── useFetch.js
│   │   │
│   │   ├── services/                   # API service layer
│   │   │   ├── api.js                  # Axios instance & interceptors
│   │   │   ├── authService.js
│   │   │   ├── orderService.js
│   │   │   ├── menuService.js
│   │   │   └── paymentService.js
│   │   │
│   │   ├── utils/                      # Helper functions
│   │   │   ├── formatters.js
│   │   │   ├── validators.js
│   │   │   └── constants.js
│   │   │
│   │   ├── styles/                     # Global styles
│   │   │   └── index.css
│   │   │
│   │   ├── App.jsx                     # Root component & routes
│   │   └── main.jsx                    # React entry point
│   │
│   ├── .env.example                    # Frontend env template
│   ├── .gitignore
│   ├── index.html                      # Vite HTML entry
│   ├── package.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   └── vite.config.js
│
├── 📁 backend/                         # Node.js + Express application
│   │
│   ├── prisma/                         # Prisma ORM
│   │   ├── schema.prisma               # Database schema & models
│   │   ├── migrations/                 # Database migration history
│   │   └── seed.js                     # Optional seed data
│   │
│   ├── config/                         # Configuration & connections
│   │   ├── prisma.js                   # Prisma Client instance
│   │   ├── cloudinary.js               # Cloudinary setup
│   │   ├── payfast.js                  # PayFast setup
│   │   └── mailer.js                   # Nodemailer SMTP transport
│   │
│   ├── controllers/                    # Route controllers (logic)
│   │   ├── authController.js
│   │   ├── userController.js
│   │   ├── businessController.js
│   │   ├── menuController.js
│   │   ├── orderController.js
│   │   ├── paymentController.js
│   │   ├── driverController.js
│   │   └── adminController.js
│   │
│   ├── middleware/                     # Express middleware
│   │   ├── authMiddleware.js           # JWT verification
│   │   ├── roleMiddleware.js           # Role-based access control
│   │   ├── errorMiddleware.js          # Centralized error handling
│   │   └── uploadMiddleware.js         # Multer file uploads
│   │
│   ├── routes/                         # API route definitions
│   │   ├── authRoutes.js
│   │   ├── userRoutes.js
│   │   ├── businessRoutes.js
│   │   ├── menuRoutes.js
│   │   ├── orderRoutes.js
│   │   ├── paymentRoutes.js
│   │   ├── driverRoutes.js
│   │   └── adminRoutes.js
│   │
│   ├── services/                       # Business logic layer
│   │   ├── authService.js
│   │   ├── orderService.js
│   │   ├── paymentService.js
│   │   └── emailService.js             # SMTP email sending logic
│   │
│   ├── utils/                          # Helper functions
│   │   ├── generateToken.js
│   │   ├── sendEmail.js
│   │   └── logger.js
│   │
│   ├── uploads/                        # Temporary upload storage
│   │
│   ├── .env.example                    # Backend env template
│   ├── .gitignore
│   ├── package.json
│   └── server.js                       # Express entry point
│
├── 📁 docs/                            # Project documentation
│   ├── API.md                          # API endpoint documentation
│   ├── DATABASE.md                     # Database schema docs
│   ├── CONTRIBUTING.md                 # Contribution guidelines
│   └── DEPLOYMENT.md                   # Deployment guide
│
├── 📁 assets/                          # README assets (screenshots, logo)
│   ├── logo/
│   │   └── ofeast-logo.png
│   └── screenshots/
│       ├── home.png
│       ├── menu.png
│       ├── cart.png
│       ├── checkout.png
│       ├── order-tracking.png
│       ├── shop-dashboard.png
│       ├── admin-dashboard.png
│       └── mobile.png
│
├── .gitignore                          # Root gitignore
├── .editorconfig                       # Editor configuration
├── LICENSE
└── README.md
```

### Why Two Separate Projects?

| Aspect | Frontend (`frontend/`) | Backend (`backend/`) |
|---|---|---|
| **Framework** | React + Vite | Node.js + Express |
| **Language** | JavaScript (JSX) | JavaScript (Node) |
| **ORM** | — | Prisma |
| **Database** | — | PostgreSQL (Neon) |
| **Package Manager** | npm / yarn | npm / yarn |
| **Dev Server** | Vite (port 5173) | Nodemon (port 5000) |
| **Deployment** | Vercel | Render / Railway |
| **Env File** | `.env` (VITE_*) | `.env` |

This separation keeps concerns clean, allows independent deployment,
and mirrors how the platform runs in production.

---

# 🚀 Getting Started

> **⚠️ Note:** The source code for this project is currently **private**.
> The instructions below describe the intended local setup for when the
> codebase is made available.

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- PostgreSQL database (local or Neon)
- PayFast merchant account
- Cloudinary account
- SMTP email account (e.g. Gmail, Mailtrap, SendGrid)

### Installation

```bash
# Clone the repository (when available)
git clone https://github.com/your-username/ofeast.git
cd ofeast
```

#### 1. Set up the Frontend

```bash
cd frontend
npm install
```

#### 2. Set up the Backend

```bash
cd ../backend
npm install
```

#### 3. Set up the Database (Prisma)

```bash
cd backend

# Generate the Prisma Client
npx prisma generate

# Run database migrations
npx prisma migrate dev

# (Optional) Open Prisma Studio to inspect the database
npx prisma studio
```

### Environment Variables

Create a `.env` file in both `frontend/` and `backend/` directories.

**Backend (`backend/.env`)**

```env
PORT=5000
NODE_ENV=development

# Database (Neon PostgreSQL)
DATABASE_URL=postgresql://user:password@host/dbname?sslmode=require

# Authentication
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d

# PayFast
PAYFAST_MERCHANT_ID=your_merchant_id
PAYFAST_MERCHANT_KEY=your_merchant_key
PAYFAST_PASSPHRASE=your_passphrase
PAYFAST_RETURN_URL=http://localhost:5173/order-success
PAYFAST_CANCEL_URL=http://localhost:5173/cart

# Cloudinary
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

# SMTP Email
SMTP_HOST=smtp.example.com
SMTP_PORT=587
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password
SMTP_FROM="Ofeast <no-reply@ofeast.co.za>"
```

**Frontend (`frontend/.env`)**

```env
VITE_API_URL=http://localhost:5000/api
VITE_PAYFAST_URL=https://sandbox.payfast.co.za/eng/process
```

### Running the Application

Open **two terminals** — one for each project.

```bash
# Terminal 1 — Backend
cd backend
npm run dev
```

```bash
# Terminal 2 — Frontend
cd frontend
npm run dev
```

The frontend will be available at `http://localhost:5173` and the
backend API at `http://localhost:5000`.

---

# 🗺️ Roadmap

### ✅ Phase 1 — Foundation
- [x] Project planning and architecture design
- [x] Multi-role system design (Customer, Business, Admin, Driver)
- [x] Authentication and authorization strategy
- [x] Database schema design (Prisma + PostgreSQL)
- [x] UI/UX wireframing

### 🚧 Phase 2 — Core Development
- [ ] User registration and login
- [ ] Business onboarding and management
- [ ] Menu creation and management
- [ ] Shopping cart functionality
- [ ] Order placement and tracking
- [ ] PayFast payment integration

### 🔜 Phase 3 — Advanced Features
- [ ] Real-time order notifications
- [ ] Driver assignment and delivery tracking
- [ ] Admin analytics dashboard
- [ ] Ratings and reviews
- [ ] Promotional codes and discounts
- [ ] Push notifications
- [ ] Transactional email flows (order confirmation, status updates)

### 🌍 Phase 4 — Expansion
- [ ] Multi-language support
- [ ] Township and community market expansion
- [ ] Mobile application (React Native)
- [ ] Advanced analytics and reporting
- [ ] Loyalty and rewards program

---

# 🤝 Contributing

Contributions, feedback, and suggestions are welcome. Since the source
code is currently private, please reach out via the contact details
below if you'd like to collaborate or learn more about the project.

---

# 📄 License

This project is licensed under the **MIT License**. See the
[LICENSE](LICENSE) file for details.

---

# 📬 Contact

**Project Maintainer**

- 🌐 Live Demo: [ofeast.vercel.app](https://ofeast.vercel.app/)
- 📧 Email: your-email@example.com
- 💼 LinkedIn: [Your Name](https://linkedin.com/in/your-profile)
- 🐙 GitHub: [@your-username](https://github.com/your-username)

---

<p align="center">
  <strong>Ofeast</strong> — Your Cravings Deserve the Best.
</p>

<p align="center">
  Made with ❤️ in South Africa
</p>
