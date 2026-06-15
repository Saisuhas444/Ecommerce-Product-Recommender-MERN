# 🛒 E-Commerce Product Recommender System (MERN Stack)

A full-stack intelligent e-commerce platform built using the MERN Stack that provides personalized product recommendations based on user behavior, product ratings, category preferences, and trending products.

This project demonstrates modern web development practices, RESTful API architecture, authentication & authorization, recommendation algorithms, and scalable database design.

---

## 📌 Project Overview

The E-Commerce Product Recommender System helps users discover relevant products through an intelligent recommendation engine while providing a seamless online shopping experience.

The platform includes user authentication, product management, shopping cart functionality, wishlist management, order processing, and an admin dashboard for managing the entire ecosystem.

---

## 🚀 Key Features

### User Features
- Secure User Registration & Login
- JWT Authentication & Authorization
- Browse Product Catalog
- Advanced Search & Filtering
- Product Details Page
- Add to Cart
- Wishlist Management
- Order Placement & Tracking
- Personalized Product Recommendations
- Responsive Design for Mobile & Desktop

### Admin Features
- Admin Dashboard
- Product Management (CRUD)
- Category Management
- User Management
- Order Management
- Sales Monitoring
- Inventory Tracking

---

## 🧠 Recommendation Engine

The recommendation system suggests products using multiple ranking factors:

### Recommendation Score Formula

Recommendation Score =
(Category Match × 40%)
+ (User Activity × 25%)
+ (Product Ratings × 20%)
+ (Trending Score × 15%)

### Recommendation Factors

#### Category Match
Recommends products from categories frequently viewed or purchased by the user.

#### User Activity
Analyzes:
- Product Views
- Wishlist Activity
- Cart Activity
- Purchase History

#### Product Ratings
Products with higher customer ratings receive higher recommendation priority.

#### Trending Score
Products with increasing popularity and sales volume are promoted.

---

## 🏗️ System Architecture

```text
Frontend (React.js)
       │
       ▼
REST API (Express.js)
       │
       ▼
Business Logic Layer
       │
       ▼
MongoDB Database
```

---

## 💻 Technology Stack

### Frontend
- React.js
- Redux Toolkit
- React Router DOM
- Tailwind CSS
- Context API

### Backend
- Node.js
- Express.js
- JWT Authentication
- Mongoose

### Database
- MongoDB Atlas

### Development Tools
- VS Code
- Git & GitHub
- Postman
- MongoDB Compass

---

## 📂 Project Structure

```text
ecommerce-recommender/
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── services/
│   │   └── assets/
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   └── utils/
│
├── README.md
└── package.json
```

---

## 🔐 Authentication Flow

1. User Registers
2. Password encrypted using bcryptjs
3. JWT Token generated after login
4. Protected routes verified using middleware
5. Role-based access for Admin and Users

---

## 🗄️ Database Collections

### Users
- User Information
- Authentication Data
- Wishlist
- Purchase History

### Products
- Product Details
- Category
- Price
- Ratings
- Stock

### Orders
- Order Information
- Payment Status
- Delivery Status

### Reviews
- Product Ratings
- User Feedback

---

## 📈 Future Enhancements

- AI-Based Recommendation Model
- Collaborative Filtering
- Content-Based Filtering
- Product Review Sentiment Analysis
- Payment Gateway Integration
- Real-Time Notifications
- Chatbot Support
- Sales Analytics Dashboard

---

## 🎯 Learning Outcomes

Through this project, the following concepts were implemented:

- Full-Stack MERN Development
- RESTful API Design
- JWT Authentication
- MongoDB Database Modeling
- State Management using Redux Toolkit
- Recommendation System Fundamentals
- Responsive UI Development
- Deployment & Version Control

---

## 👨‍💻 Author

**Vallabhapuram SaiSuhas**

B.Tech Computer Science Engineering (2027)

GitHub: https://github.com/Saisuhas444

LinkedIn: https://linkedin.com/in/saisuhas-vallabhapuram-989102294

---

## ⭐ Project Status

Completed as a Full-Stack MERN Project for Academic Learning, Placement Preparation, and Portfolio Development.
