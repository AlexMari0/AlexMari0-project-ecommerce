# 🛒 Fullstack E-Commerce Platform

A modern full-stack **E-Commerce Application** built with Next.js App Router, supporting product browsing, cart management, order processing, and seller dashboard.

This project demonstrates a **production-ready architecture** with authentication, payments, background jobs, and scalable API design.

---

## 🛠️ Tech Stack

### 🔹 Frontend & Backend (Monorepo)

* Next.js (App Router)
* React 19
* Tailwind CSS

### 🔹 Backend & Database

* MongoDB (Mongoose)
* Next.js API Routes

### 🔹 Integrations

* Clerk → Authentication & user management
* Stripe → Payment processing
* Inngest → Background jobs & workflows
* Cloudinary → Media storage

---

## ✨ Features

### 👤 User

* Browse products
* View product details
* Add to cart
* Place orders
* Manage addresses
* View order history
* Secure authentication (Clerk)

### 🛍️ Seller

* Add products
* Manage product listings
* View orders
* Seller dashboard

### ⚙️ System Features

* Fullstack API (Next.js Route Handlers)
* Stripe payment integration
* Background jobs (Inngest)
* Scalable folder structure (App Router)
* Role-based access (User & Seller)

---

## 📁 Project Structure

```bash id="h3k8x2"
project-root/
├── app/                   # Next.js App Router (pages & API)
├── components/            # Reusable UI components
├── models/                # MongoDB schemas
├── config/                # DB & Inngest config
├── context/               # Global state
├── lib/                   # Utility functions
└── assets/                # Static assets
```

---

## 📌 App Router & API

```bash id="p9x2k7"
app/
├── api/                   # Backend API (Route Handlers)
│   ├── product/
│   ├── cart/
│   ├── order/
│   └── user/
├── product/[id]/          # Dynamic product page
├── cart/                  # Cart page
├── my-orders/             # Orders page
└── seller/                # Seller dashboard
```

---

## 📦 Installation

### 1. Clone Repository

```bash id="z1k8x3"
git clone https://github.com/AlexMari0/E-Commerce.git
cd ecommerce-inngest
```

---

## ▶️ Run Project

```bash id="m4p9x2"
npm install
npm run dev
```

App will run on:

```
http://localhost:3000
```

---

## 🌐 Environment Variables

Create `.env.local` in root:

```env id="q2k7x9"
# MongoDB
MONGODB_URI=your_mongodb_uri

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_secret

# Stripe
STRIPE_SECRET_KEY=your_secret
STRIPE_WEBHOOK_SECRET=your_webhook

# Cloudinary
CLOUDINARY_CLOUD_NAME=your_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
```

---

## 🌍 Live Demo

* 🔗 App: https://e-commerce-alpha-flame-85.vercel.app/

---

## 📸 Screenshots

Add screenshots such as:

* Homepage
<img width="1424" height="786" alt="image" src="https://github.com/user-attachments/assets/aa203702-132d-4542-bfb4-b9e143634873" />

* Product page
<img width="1426" height="787" alt="image" src="https://github.com/user-attachments/assets/e6ef8baf-80bc-421f-b3d3-8cff2aae15bf" />

* Cart & checkout
<img width="1427" height="783" alt="image" src="https://github.com/user-attachments/assets/15f5664a-d8b7-48ba-b733-48c70cb30f73" />

* Seller dashboard
<img width="1425" height="781" alt="image" src="https://github.com/user-attachments/assets/d476228a-3e90-442a-aa0c-ad061aff6c4b" />

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

* Alex Mario
* GitHub: https://github.com/Alex-Mari0
