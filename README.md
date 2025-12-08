# 🛒 Gro-Mart – Full Stack E-Commerce Application


Gro-Mart is a fully functional, production-grade **E-Commerce platform** built with the MERN stack.  
It includes secure authentication, product management, cart system, Stripe payments, and an end-to-end order workflow.

---

## 🚀 Features

### 🔐 Authentication & Security
- JWT-based authentication (Access + Refresh tokens)
- Encrypted passwords with bcrypt
- Protected routes on frontend & backend
- Role-based access (`admin`, `customer`)
- Secure cookies & HTTP-only token handling

### 🛍️ E-Commerce Core
- Product listing with images
- Categories, filters & search
- Cart add/remove/update functionality
- Order creation & tracking
- Wishlist (optional)

### 💳 Payments – Stripe Integration
- Create payment intents
- Secure card checkout
- Transaction verification
- Payment success/failure webhooks
- Store order & invoice details in DB

### 🧰 Admin Panel
- Add / Edit / Delete products
- Manage users
- Manage orders
- Sales analytics (optional)

### 📦 Robust Backend (Node + Express)
- Modular clean architecture  
- Controllers, Services, Routes separated
- Global error handler
- Request validation (Joi/Zod)
- Logging (morgan / winston)

### 🗄️ Database – MongoDB + Mongoose
- Product schema & indexing for fast search
- User schema with role-based permissions
- Orders schema with Stripe payment IDs
- Cart schema (persistent cart)

---

