# 🏨 Project Management Hotel

> A full-stack hotel management system with separate **Frontend (React)** and **Backend (Laravel)** directories. Designed for modern hotel operations including room bookings, customer management, and billing.

---
### 📁 Folder Structure

Project_Management_Hotel/
|-- FE/ # Frontend (React)
L-- BE/ # Backend (Laravel)

---

## 🚀 Technologies Used

### Frontend (FE):
- ✅ ReactJS
- ✅ React Router DOM
- ✅ Axios
- ✅ Bootstrap / Tailwind (nếu có)
- ✅ State Management (useState, useEffect, Context API...)

### Backend (BE):
- ✅ Laravel (PHP)
- ✅ MySQL
- ✅ Laravel Sanctum (for API authentication)
- ✅ Eloquent ORM
- ✅ RESTful API design

---

## 🔧 Setup Instructions

### ⚙️ 1. Clone the repository

```bash
git clone https://github.com/imdtrung36/Project_Management_Hotel.git
cd Project_Management_Hotel

### Setup BE:
cd BE
composer install
cp .env.example .env
php artisan key:generate

# Cấu hình DB trong file .env
php artisan migrate
php artisan db:seed 
php artisan serve

### Setup FE:
cd ../FE
npm install
npm start

