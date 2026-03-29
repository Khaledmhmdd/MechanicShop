# 🚀 MechanicShop - Workshop Management System

A modern **Workshop Management System** built using **ASP.NET Core (.NET 8)** and a rich client interface, designed to manage automotive service operations efficiently.

The system handles customers, work orders, repair tasks, billing, and scheduling, with a strong focus on scalability, maintainability, and real-world deployment practices.

---

## 🧩 Architecture

The project follows **Clean Architecture** and is divided into multiple layers:

- **MechanicShop.Api** → REST APIs, Controllers, Middleware, Endpoints  
- **MechanicShop.Application** → Business logic, features, and use cases  
- **MechanicShop.Domain** → Core entities and domain rules  
- **MechanicShop.Infrastructure** → Data access, services, background jobs  
- **MechanicShop.Client** → Frontend (Blazor-based UI)  
- **MechanicShop.Contracts** → Shared DTOs and contracts  

---

## ✨ Features

### 👤 Identity & Authentication
- Secure user authentication and authorization  
- Current user context handling  

### 🧑‍🔧 Workshop Management
- Customer management  
- Work orders and repair task tracking  
- Labor and service management  
- Scheduling system  

### 💳 Billing & Invoices
- Invoice generation and billing workflows  
- Payment tracking  

### 📊 Dashboard & Insights
- Dashboard endpoints for monitoring operations  
- Business insights and reporting  

### ⚙️ System Features
- Global exception handling middleware  
- Request logging middleware  
- Background jobs processing  
- Real-time capabilities (SignalR ready)  

---

## 🛠️ Tech Stack

### 🔹 Backend
- ASP.NET Core (.NET 8)  
- Entity Framework Core  
- Clean Architecture  
- MediatR (CQRS pattern)  

### 🔹 Frontend
- Blazor (Interactive UI)  

### 🔹 DevOps & Tools
- Docker & Docker Compose  
- GitHub Actions (CI/CD)  
- Structured logging & request tracking  

---

## 📂 Project Structure
