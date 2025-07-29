# 🏡 Airbnb Clone – Full-Stack Booking Web App

Welcome to the **Airbnb Clone Project**, a production-ready, full-stack web application that mimics the core functionality of Airbnb. Built using modern technologies like **React**, **Next.js**, **Node.js**, **Express**, and **MongoDB**, this clone allows users to list, browse, and book properties around the world with real-time features and a beautifully responsive interface.

---

## 🌐 Live URL

[🔗 View Project](https://airbnb-pi-virid.vercel.app)  
*Deployed using Vercel / Railway / MongoDB Atlas.*

---

## 🧩 Table of Contents

- [Features](#-features)
- [Screenshots](#-screenshots)
- [Tech Stack](#-tech-stack)
- [Project Architecture](#-project-architecture)
- [Folder Structure](#-folder-structure)
- [Environment Variables](#-environment-variables)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Known Issues](#-known-issues)
- [Roadmap](#-roadmap)
- [Topics Covered](#-topics-covered)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)

---

## ✨ Features

### 🔑 Authentication & Authorization
- Login and Signup with JWT
- Google OAuth integration
- Session-based route protection
- Secure password hashing with bcrypt

### 🏘️ Listings
- View public listings
- Filter by location, category, price, availability
- Responsive listing cards with interactive hover effects
- Create, edit, or delete personal listings

### 📅 Booking System
- Select check-in and check-out using react-date-range
- Dynamic price calculation
- Backend validation of availability
- Cancel or manage your bookings

### 📍 Map Integration
- Interactive maps using **Mapbox** or **Google Maps API**
- Location autocomplete
- Marker pins for listings

### 📸 Image Uploads
- Upload and preview images using **Firebase** or **Cloudinary**
- Image validation
- Compressed and optimized storage

### 📬 Messaging *(Optional)*
- Real-time messaging between guest and host using **Socket.io**
- Inbox system and conversation management
- Notifications for unread messages

### 📲 Fully Responsive
- Designed for mobile-first experience
- Tailwind CSS for utility-first custom design
- Dark mode ready *(optional)*

---

## 🖼 Screenshots

> Add 3–5 screenshots here to showcase UI:
- Landing Page
- Property Details Page
- Booking Calendar
- Dashboard
- Mobile View

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Next.js (Server Side Rendering, API Routes, Routing)
- Tailwind CSS
- react-date-range
- Axios
- Mapbox / Google Maps API

### Backend
- Node.js + Express.js
- MongoDB + Mongoose / PostgreSQL + Prisma ORM
- JWT for token-based authentication
- Bcrypt.js for password hashing
- Socket.io for real-time communication

### Cloud & DevOps
- Firebase / Cloudinary – image storage
- Vercel / Netlify – frontend deployment
- Railway / Render / EC2 – backend deployment
- MongoDB Atlas / PlanetScale – hosted databases
- GitHub + Git – version control
- GitHub Actions – CI/CD pipelines

---

## 🧱 Project Architecture

├── client/ # Frontend code (React + Next.js)
│ ├── components/ # Reusable UI components
│ ├── pages/ # Routing structure
│ ├── styles/ # Tailwind or global CSS
│ └── utils/ # Helper functions
│
├── server/ # Backend (Node.js + Express)
│ ├── controllers/ # Business logic
│ ├── routes/ # API routes
│ ├── models/ # Database schemas
│ ├── middlewares/ # Auth & error handling
│ └── config/ # Database and cloud config
│
├── public/ # Static assets
├── .env # Environment variables
└── README.md

# Build frontend
cd client
npm run build

#Start 
npm i
npm run dev
