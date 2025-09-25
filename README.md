# 🎬 Cinema and Event Ticketing System (CETS)

The **Cinema and Event Ticketing System (CETS)** is a full-stack web application that allows users to browse movies and events, book tickets, and manage their accounts. It also includes an **admin dashboard** for managing bookings and event data.

---

## 🚀 Features

- 🔑 **User Authentication**
  - Register / Login with username or email
  - Passwords stored securely with hashing
  - Role-based access (User / Admin)

- 🎥 **Movies**
  - Browse available movies
  - View showtime and ticket availability
  - Book cinema tickets online

- 🎤 **Events**
  - Browse upcoming events
  - View event details (location, date, time)
  - Book event tickets

- 👤 **User Profile**
  - Manage bookings
  - View ticket history

- 🔒 **Admin Dashboard**
  - Manage movies and events (CRUD operations)
  - View all user bookings
  - Role-based access only for admins

---

## 🛠️ Tools Used

- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend:** PHP 
- **Database:** MySQL  
- **Version Control:** Git + GitHub  
- **Local Development:** XAMPP  

---
```
## 📂 Project Structure

CETS-Project/
├── css/ # Stylesheets
│ ├── account.css
│ ├── profile.css
│ └── style.css
│
├── img/ # Images (logos, assets)
│
├── php/ # PHP backend files
│ ├── db.php # Database connection
│ ├── auth.php # Authentication logic
│ ├── logout.php # Logout handling
│ ├── cancel_booking.php # Cancel booking
│
├── index.php # Homepage
├── login.php # Login page
├── register.php # Register page
├── movies.php # Movies list
├── events.php # Events list
├── admin.php # Admin dashboard
├── profile.php # User profile
├── about.php # About page
├── contact.php # Contact page
└── nav.php # Navigation bar
```

---

## ⚙️ Setup Instructions

1. Clone the repository:
```
git clone https://github.com/MaxYPro/CETS-Project.git
```

2. Move the website folder `cets` from CETS-Project.zip into your **XAMPP `htdocs`** folder :
```
C:\xampp\htdocs\cets
```

3. Import the database:
- Open **phpMyAdmin**
- Create a database called `cets_db`
- Import the provided SQL file (`cets_db.sql`)

4. Configure database connection in:
```
C:\xampp\htdocs\CETS-Project
```

5. Run the project:
- Start **Apache** & **MySQL** in XAMPP
- Open browser and go to:
```
http://localhost/CETS-Project
```

  Accounts for Testing:
```
  Username   Email             Password   Role

  Maxim      maxim@gmail.com   maxim      (user)
  Test       test@gmail.com    test       (user)
  Admin      admin@gmail.com   admin      (admin)
```
---

## 👨‍💻 Team Members

- **Maxim Pereu** – Full Stack Developer  
- **Vasile Padureanu** – Project Manager  
- **Marius Olaru** – Finance Manager & Tester  

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).  
You are free to use, modify, and distribute this project for personal or commercial purposes.
