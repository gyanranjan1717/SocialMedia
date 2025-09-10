# 🚀 PingUp – Modern Social Media Platform  

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Vercel](https://img.shields.io/badge/deploy%20on-Vercel-black?logo=vercel)](https://vercel.com/)
[![Node.js](https://img.shields.io/badge/node-%3E=_18-brightgreen)](https://nodejs.org/)

> ⚠️ **Note**: This project is still under development. Features like **comments on posts, post sharing, read receipts in messages, and more** are coming soon!  

A **full-stack social media application** built with **React, Node.js, and MongoDB**, providing a seamless networking experience with **real-time features, stories, messaging, and more.**  

---

## ✨ Features  

### 🔹 Core Features  
- 🔐 **User Authentication** – Secure auth with Clerk  
- 👤 **User Profiles** – Cover photo + avatar customization  
- 📝 **Posts & Feed** – Create, like, comment, share posts  
- 📸 **Stories** – 24-hour disappearing stories with viewer tracking  
- 💬 **Real-time Messaging** – Direct chats with live updates  
- 🤝 **Connections** – Send/accept requests & manage contacts  
- 🔍 **Discover** – Find and connect with new people  
- 🔔 **Notifications** – Real-time interaction alerts  

### 🔹 Advanced Features  
- 🖼️ **Image Uploads** (ImageKit integration)  
- 📧 **Email Notifications** with Nodemailer  
- ⚡ **Background Jobs** handled by Inngest  
- 📱 **Responsive Design** (Tailwind CSS)  
- 🔄 **Live Updates** via Redux Toolkit  

---

## 🛠️ Tech Stack  

**Frontend**  
- ⚛️ React 19  
- 🎛️ Redux Toolkit + RTK Query  
- 🛣️ React Router v7  
- 🎨 Tailwind CSS 4  
- ⚡ Vite  
- 🔑 Clerk React  

**Backend**  
- 🟢 Node.js + Express.js  
- 🍃 MongoDB + Mongoose  
- 🔑 Clerk Express  
- ⚡ Inngest  
- 🖼️ ImageKit  
- 📧 Nodemailer  

**Deployment**  
- ▲ Vercel (Frontend)  
- ☁️ Cloud Platform + MongoDB Atlas (Backend)  

---

## 🚀 Getting Started  

### ✅ Prerequisites  
- Node.js v18+  
- MongoDB Atlas account  
- Clerk account  
- ImageKit account  
- SMTP service (for emails)  

### 📦 Installation  

```bash
# Clone repo
git clone https://github.com/santoshsingh19114/Pingup.git
cd Pingup

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install


## ⚙️ Environment Variables  

To run this project, you will need to create **`.env` files** in both the **server** and **client** directories.  

### 🔹 Server `.env`  

```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string

# Clerk Authentication
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# ImageKit Configuration
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint

# Email (SMTP) Configuration
EMAIL_USER=your_email@domain.com
EMAIL_PASS=your_email_password

# Inngest Background Jobs
INNGEST_EVENT_KEY=your_inngest_event_key


# Clerk (Frontend)
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

# API URL (Backend server endpoint)
VITE_API_URL=http://localhost:4000/api


## ▶️ Run the App  

```bash
# Terminal 1 - Start backend
cd server
npm start

# Terminal 2 - Start frontend
cd client
npm run dev


