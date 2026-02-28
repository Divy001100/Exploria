# Exploria Application

🌍 Exploria – Full-Stack Travel Booking Platform

Natours is a production-grade travel booking application built with Node.js, Express, MongoDB and Pug.
It demonstrates secure backend architecture, authentication systems, payment processing, API design, and dynamic server-side rendering.

This project focuses heavily on backend engineering principles, security, and scalable REST API design.

🚀 Live Features
🔐 Authentication & Authorization

JWT-based authentication

Secure HTTP-only cookies

Password hashing with bcrypt

Role-based access control (Admin / Lead Guide / User)

Password reset via email

Protected routes & middleware security

🗺 Tour Management System

CRUD operations for tours

Advanced filtering, sorting, field limiting & pagination

MongoDB aggregation pipelines

Geospatial queries (distance-based search)

Virtual properties

Middleware hooks (document & query middleware)

💳 Secure Payment Integration

Stripe checkout integration

Booking model tied to payment session

Protected booking endpoints

📧 Email Services

Welcome emails

Password reset emails

Production-ready email service layer

📊 API Architecture

RESTful API structure

MVC architecture

Centralized error handling

Custom AppError class

Async error wrapper

Environment configuration (development vs production)

🖥 Server-Side Rendering

Pug templating engine

Dynamic tour pages

Conditional UI rendering based on authentication

Secure data rendering from backend

🏗 Tech Stack
Backend

Node.js

Express.js

MongoDB

Mongoose

Stripe

JWT

Bcrypt

Nodemailer

Frontend

Pug (server-rendered templates)

Custom CSS architecture

Dynamic tour cards

Role-based UI behavior

🔒 Security Implementations

Helmet (secure HTTP headers)

Data sanitization (NoSQL injection prevention)

XSS protection

Rate limiting

Secure cookie handling

Production error masking

📁 Project Architecture
controllers/
models/
routes/
utils/
views/
public/

Follows clean MVC separation with reusable middleware and modular routing.

🎯 Key Engineering Highlights

Clean layered architecture

Reusable middleware pattern

Database performance optimization with indexes

Secure authentication flow

Payment processing workflow

Production-grade error handling strategy

🧠 What This Project Demonstrates

Designing scalable REST APIs

Implementing secure authentication systems

Working with real-world payment gateways

Writing clean, modular backend code

Structuring full-stack applications professionally

🛠 Setup
npm install
npm start

Configure environment variables in .env:

DATABASE

JWT_SECRET

STRIPE_SECRET_KEY

EMAIL credentials

📌 Why This Project Matters

Exploria is not just a demo — it is a full backend-focused application that demonstrates:

Real-world API design

Authentication flows

Payment integration

Security best practices

Clean production architecture