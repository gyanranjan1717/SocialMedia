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
