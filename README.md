# FreshMart - Online Grocery Ordering Application

A full-stack supermarket digitization platform built with **React**, **Express**, and **MongoDB**.

## 🚀 Getting Started

### 1. Prerequisites
- **Node.js** installed
- **MongoDB** running locally (or update `.env`)

### 2. Backend Setup
1. Open a terminal in the `server` directory.
2. Run `npm install` (already done by the assistant).
3. (Optional) Run `node seed.js` to initialize the database with an admin user and sample products.
4. Start the server: `node index.js` or `npm run dev` (if you add nodemon).

**Admin Credentials (from seed):**
- **Email:** `admin@freshmart.com`
- **Password:** `adminpassword123`

### 3. Frontend Setup
1. Open another terminal in the `frontend` directory.
2. Run `npm install` (already done by the assistant).
3. Start the app: `npm run dev`.
4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## 🛠️ Features
- **Customers**: Browse by category, search products, manage cart, place orders, and track history.
- **Admins**: Dashboard with sales stats, manage stock (CRUD with photo uploads), and update order delivery status.

## 🎨 Tech Stack
- **Frontend**: React, Tailwind CSS, Framer Motion, Lucide Icons, Axios.
- **Backend**: Node.js, Express, Mongoose, Multer (file uploads), JWT (auth).
- **Database**: MongoDB.
