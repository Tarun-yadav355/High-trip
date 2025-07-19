# High-trip - Travel Agency Solution 🌍

**High-trip** is a full-stack PHP + MySQL travel agency platform where users can explore, book, and review tour packages, and admins can manage bookings, users, and generate PDF reports — all in real-time.

> ✨ This project is a customized and enhanced version of the open-source `triptrip` project. I improved the code, UI, and modular structure while preparing it for production use.

---

## 🧠 Features

### 👤 Users
- Secure user registration with **email validation** (PHPMailer integration)
- Restricts duplicate or invalid package purchases:
  - Can’t repurchase same package
  - Can't buy after start date or when capacity is full
- Users can:
  - Browse/search packages
  - Leave reviews
  - Download PDF of purchase report

### 🛠️ Admin
- Add/update/remove tour packages
- Manage users (Active/Inactive)
- View and export **sales data** as PDF

---

## 📦 Tech Stack
- **Backend**: Raw PHP (OOP + modular)
- **Database**: MySQL
- **Frontend**: HTML, CSS, Bootstrap
- **PDF Generator**: FPDF
- **Mailing**: PHPMailer
- **Payment Gateway**: SSLCommerz (Sandbox ready)

---

## 🚀 Setup Instructions

### 📁 Prerequisites
- XAMPP / Laragon (Apache + MySQL)
- VS Code or PhpStorm

### 🧪 Local Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/high-trip.git
