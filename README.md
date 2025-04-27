# Filyo

**Filyo** is a modern and dynamic product store platform, built using **Laravel**, **FilamentPHP**, and **MySQL**.  
It delivers a seamless shopping experience with real-time stock updates, smart product recommendations, and exciting daily flash deals.

---

## 🚀 Technologies Used
- **Laravel** — PHP Framework for robust web applications
- **FilamentPHP** — Admin panel and UI management made easy
- **MySQL** — Reliable relational database backend

---

## 👥 Team Members
- **Omar Abduh** — *Team Leader*  
- Mohammed Hany  
- Mohamed Hesham  
- **Kamel Ahmed**

---

## 📚 Features
- Real-time stock availability
- Daily flash deals ("Filyo Pulse Deals")
- Wishlist and save-for-later options
- Smart product recommendation engine
- Full admin dashboard for store management
- Order tracking and history
- Customer reviews and rating system

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/filyo.git
   cd filyo
   ```

2. **Install PHP and JavaScript dependencies**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Create environment file**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Configure Database** in `.env`
   ```plaintext
   DB_DATABASE=your_database_name
   DB_USERNAME=your_username
   DB_PASSWORD=your_password
   ```

5. **Run Migrations and Seeders**
   ```bash
   php artisan migrate --seed
   ```

6. **Serve the Application**
   ```bash
   php artisan serve
   ```

---

## 🎯 Project Goals
- Deliver a smooth, fast, and intelligent e-commerce experience.
- Empower store owners with easy admin control.
- Use dynamic deals to boost customer engagement and sales.

---

## 📄 License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## 🛠️ Status
![Laravel](https://img.shields.io/badge/Laravel-11.x-red)
![FilamentPHP](https://img.shields.io/badge/FilamentPHP-3.x-green)
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)
