# 🚗 RentSetGo Car Rental System

> A full-stack car rental management platform that enables customers to browse, rent, and manage vehicles while providing employees with dedicated tools for booking and fleet management.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-14+-339933?style=flat-square\&logo=node.js\&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-4+-000000?style=flat-square\&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-4+-47A248?style=flat-square\&logo=mongodb\&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

# 🚀 Overview

**RentSetGo Car Rental System** is a full-stack web application designed to simplify vehicle rental operations for both customers and rental service providers.

The platform offers secure authentication, customer and employee dashboards, vehicle booking management, and rental tracking features through an intuitive web interface.

Built using **Node.js**, **Express.js**, **MongoDB**, **HTML**, **CSS**, and **JavaScript**, the system provides a scalable solution for managing car rental workflows and customer interactions.

---

# ✨ Features

* 🚗 Vehicle Rental Management
* 🔐 Secure User Registration & Login
* 👤 Customer Dashboard
* 👨‍💼 Employee Dashboard
* 📋 Booking Management System
* 🗄️ MongoDB Database Integration
* 📱 Responsive Web Interface
* ❓ FAQ & Support Section
* ⚡ Express.js RESTful Backend

---

# 🏗️ Architecture

```text
┌─────────────────────────┐
│      Frontend UI        │
│                         │
│ HTML • CSS • JavaScript │
└───────────┬─────────────┘
            │ HTTP Requests
┌───────────▼─────────────┐
│      Express Server     │
│                         │
│ Booking & Auth APIs     │
└───────────┬─────────────┘
            │
┌───────────▼─────────────┐
│       MongoDB DB        │
│                         │
│ Users • Cars • Rentals  │
│ Bookings • Employees    │
└─────────────────────────┘
```

---

# 🛠️ Tech Stack

| Layer          | Technology                   |
| -------------- | ---------------------------- |
| Frontend       | HTML5, CSS3, JavaScript      |
| Backend        | Node.js, Express.js          |
| Database       | MongoDB, Mongoose            |
| Authentication | Session-Based Authentication |
| Development    | Nodemon                      |

---

# 🚗 Core Functionalities

## Customer Module

* Register and Login
* Browse Available Vehicles
* Book Rental Cars
* View Rental Information
* Manage User Profile

## Employee Module

* Manage Customer Bookings
* Monitor Vehicle Availability
* Handle Rental Requests
* Manage Fleet Information
* Track Rental Records

---

# 📂 Project Structure

```text
RentSetGo/
│
├── public/
│   ├── css/
│   ├── images/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── customerDashboard.html
│   ├── employeeDashboard.html
│   ├── about.html
│   └── faq.html
│
├── node_modules/
├── package.json
├── package-lock.json
└── server.js
```

---

# 🚀 Getting Started

## Prerequisites

* Node.js
* MongoDB
* npm

## Clone Repository

```bash
git clone https://github.com/your-username/RentSetGo.git
cd RentSetGo
```

## Install Dependencies

```bash
npm install
```

## Start MongoDB

```bash
mongod
```

## Run Application

```bash
npm start
```

or

```bash
nodemon server.js
```

## Access Application

```text
http://localhost:3000
```

---

# 📸 Screenshots

> Add screenshots of:
>
> * Home Page
> * Login Page
> * Registration Page
> * Customer Dashboard
> * Employee Dashboard
> * Car Listings
> * Booking Management

---

# 🔮 Future Enhancements

* [ ] Online Payment Gateway Integration
* [ ] Real-Time Vehicle Availability Tracking
* [ ] Admin Dashboard
* [ ] Email & SMS Notifications
* [ ] GPS Vehicle Tracking
* [ ] Rental Analytics Dashboard
* [ ] JWT Authentication
* [ ] Cloud Deployment

---

# 📄 License

Distributed under the MIT License.

---

# 👤 Author

**Pranaav S and Dhanushvardan A V J**

Full Stack Developer | MERN Stack | AI Enthusiast
