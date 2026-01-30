# 🏨 Hotel Booking Management System (MERN Stack)

A full-stack **Hotel Booking Management System** built using the **MERN stack** that allows users to search hotels, make bookings, and enables hotel owners to manage listings and view business analytics.  
This project is designed with **scalability, security, and real-world production practices** in mind.

---

## 🚀 Features

### 👤 User Features
- User registration & authentication (JWT based)
- Search hotels with filters (city, price, rating, facilities)
- View hotel details with images
- Book hotels with date selection
- View personal booking history

### 🏨 Hotel Owner Features
- Add, edit, and delete hotel listings
- Upload hotel images (Cloudinary)
- Manage bookings for owned hotels
- View business analytics (revenue, bookings, performance)

### 🛠️ Admin / System Features
- Secure authentication & authorization
- Payment intent creation (Stripe)
- RESTful API with Swagger documentation
- Rate limiting, CORS, Helmet security
- MongoDB with Mongoose models
- End-to-end tests using Playwright

---

## 🧠 Tech Stack

### Frontend
- React + TypeScript
- Vite
- Tailwind CSS
- Context API
- Axios / Fetch API

### Backend
- Node.js
- Express.js
- TypeScript
- MongoDB & Mongoose
- JWT Authentication
- Stripe Payments
- Cloudinary Image Storage
- Swagger API Docs

### Testing
- Playwright (E2E testing)

---

## 📁 Project Structure

```bash
prasan23bad042-hotel-mern/
├── backend/        # Express + MongoDB backend
├── frontend/       # React + Vite frontend
├── shared/         # Shared TypeScript types
├── e2e-tests/      # Playwright end-to-end tests
└── README.md
