# 🔗 URL Shortener Service — Flask Microservice

A lightweight and efficient **URL shortening microservice** built with **Flask**, using a **custom base62 encoding system** to generate unique short URLs. It supports redirection, usage tracking, and can be extended with user authentication and analytics.

---

## 📝 Description

This service allows users to shorten long URLs and redirect users when those short links are accessed. Built using **Flask** and **SQLite** (or **PostgreSQL** for production), the service includes custom short-code generation using **base62 encoding**, ensuring compact and unique identifiers.

---

## ✨ Features

- 🔗 Generate short URLs from long ones
- 🚀 Fast redirection from short URLs
- 🔢 Custom **base62 encoding** logic (0-9, a-z, A-Z)
- 📊 Track usage count (optional)
- 🧪 Simple REST API endpoints
- 🗄️ SQLite for development / PostgreSQL for production
- 🔐 Easily extendable for user login, analytics, or QR code generation

---

## 💻 Technologies Used

- **Python 3.x**
- **Flask** – micro web framework
- **SQLite** (default) / **PostgreSQL** (optional for production)
- **SQLAlchemy** – ORM
- **Base62 encoding** – for generating compact, unique URLs

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/url-shortener-service.git
cd url-shortener-service
