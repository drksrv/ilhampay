# 🚀 Ilhampay - Smart Payment & Crowdfunding App

Ilhampay is a **mobile payment gateway** that enables **DuitNow payments, QR code scanning, and instant transactions**. It also supports **crowdfunding for charities & small businesses**, allowing individuals and organizations to **receive payments instantly**.

---

## 🌍 Key Features
✅ **DuitNow QR Payments** – Seamless bank transfers via QR codes  
✅ **Crowdfunding** – Raise funds for personal, business, or charity causes  
✅ **Crypto Payments** – Binance API & Metamask support for USDT/ETH  
✅ **Secure Login** – Google, Apple, Facebook authentication via Firebase  
✅ **Small Business Support** – Instant payments for food stalls, services, rentals  
✅ **Admin Dashboard** – Web-based control panel for managing transactions  

---

## 🛠️ Tech Stack

### **📱 Mobile App**
- **Flutter (Dart)** – Cross-platform development for Android & iOS
- **Firebase Authentication** – Google, Apple, Facebook login
- **Firestore (NoSQL) & PostgreSQL (SQL Backup)** – Hybrid database structure

### **🌐 Web Dashboard**
- **React.js (JavaScript/TypeScript)** – User-friendly admin interface
- **Tailwind CSS** – Modern, responsive UI design

### **🖥️ Backend API**
- **FastAPI (Python) / Node.js (Express.js)** – Handles transactions, user data, and business logic
- **PostgreSQL & Firestore** – Hybrid SQL + NoSQL database
- **Redis (Caching)** – Improves app performance

### **💰 Payment Integration**
- **DuitNow API** – Instant QR-based transactions
- **Stripe API** – Secure card payments
- **Curlec API** – FPX payment support for businesses
- **Binance API & Metamask API** – Crypto transactions

### **🔒 Security & Infrastructure**
- **2FA (Two-Factor Authentication)**
- **Cloud Firestore Rules** – Secure database access
- **Firebase Functions** – Serverless backend logic
- **RackNerd VPS (Windows/Linux)** – Backend API hosting
- **GitHub Actions (CI/CD)** – Automated deployment & testing

---

## 🚀 Deployment Strategy

### **📱 Mobile App Deployment**
- **Google Play Store** (Android)
- **Apple App Store** (iOS)

### **🌐 Web Dashboard Hosting**
- **Firebase Hosting** (Admin panel)
- **Vercel or Netlify** (Alternative for fast deployment)

### **🖥️ Backend Hosting**
- **RackNerd VPS (Windows/Linux)** – Runs API services
- **DigitalOcean / AWS EC2** – Backup server hosting
- **Docker Containers** – Isolated backend services

### **💾 Database & Storage**
- **Firestore (NoSQL) + PostgreSQL (SQL backup)**
- **Cloud Storage (Google Cloud, AWS S3)** for user files & transaction logs

### **🔄 CI/CD (Continuous Integration & Deployment)**
- **GitHub Actions** – Auto-deploy on push to `main`
- **Firebase Hosting Deploy** – `firebase deploy` for frontend updates
- **Dockerized Backend Deployment** – `docker-compose up`

---

## 💻 Getting Started (Setup Guide)

### **🔹 Prerequisites**
Before running the project, ensure you have:
- **Flutter SDK** installed → [Flutter Install Guide](https://flutter.dev/docs/get-started/install)
- **Node.js & npm** installed → [Node.js Download](https://nodejs.org/)
- **Python 3 & FastAPI** installed → `pip install fastapi`
- **Firebase CLI** installed → `npm install -g firebase-tools`
- **Docker (Optional for Backend API)** → [Docker Install Guide](https://www.docker.com/)

---

### **🔹 Installation Steps**
1️⃣ **Clone the repository**
```bash
git clone https://github.com/drksrv/ilhampay.git
cd ilhampay
