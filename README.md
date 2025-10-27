# 🏠 Airbnb Clone - Backend API

A complete backend system for an Airbnb-like vacation rental platform built with Node.js, Express, PostgreSQL, and Redis. This RESTful API handles user authentication, property management, bookings, payments, and reviews.

## 🚀 Features

### 🔐 Authentication & Authorization
- JWT-based user registration and login
- Role-based access control (Guest, Host, Admin)
- OAuth 2.0 integration (Google, Facebook)
- Secure password hashing with bcrypt
- Email verification system

### 🏠 Property Management
- CRUD operations for property listings
- Image upload and management via AWS S3
- Advanced search and filtering
- Geographic location-based search
- Amenity-based filtering
- Availability calendar management

### 📅 Booking System
- Date availability validation
- Double-booking prevention
- Booking status tracking (pending, confirmed, completed, cancelled)
- Guest and host booking management
- Cancellation policy enforcement

### 💳 Payment Integration
- Stripe payment processing
- Multi-currency support
- Secure payment intents and webhooks
- Automatic host payouts
- Refund management
- Payment status tracking

### ⭐ Reviews & Ratings
- Booking-verified reviews only
- Multi-category ratings (cleanliness, accuracy, communication, etc.)
- Host response system
- Review moderation

### 🔔 Notifications
- Email notifications (SendGrid/Mailgun)
- In-app notification system
- Booking confirmations and reminders
- Payment receipts

### 👨‍💼 Admin Dashboard
- User management
- Property moderation
- Booking oversight
- Payment monitoring
- Analytics and reporting

## 🛠️ Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL
- **Cache**: Redis
- **File Storage**: AWS S3
- **Payments**: Stripe
- **Email**: SendGrid/Mailgun
- **Authentication**: JWT, OAuth 2.0
- **Deployment**: Docker, AWS EC2

## 📁 Project Structure
