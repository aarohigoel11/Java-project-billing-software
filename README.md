# 🧾 Billing Software System

A complete full-stack billing software web application built using **Spring Boot, React, and MySQL**, featuring secure authentication, cloud storage, and online payments.

---

## ✨ Features

- 🔐 JWT-based Authentication (Login/Register)
- 🧑‍💼 Role-based Access Control (Admin, User)
- 📦 Category & Item Management
- 🛒 Order Creation & Management
- 💳 Online Payments using Stripe
- 📁 File Upload to AWS S3
- 📊 Dashboard with analytics
- 🌐 REST API integration with React frontend
- 🌍 Deployed on Render / Vercel

---

## ⚙️ Backend Stack

- Spring Boot (Hosted on Render)
- MySQL (Hosted on FreeSQLDatabase)
- Spring Security + JWT
- Hibernate / JPA (ORM)
- AWS S3 (Image uploads)
- Stripe API (Payments)

---

## 🧑‍💻 Frontend Stack

- ReactJS
- Axios (API calls)
- React Router
- Tailwind CSS / Bootstrap

---


---

## 📁 Project Structure
src/main/in/aarohigoel/billingsoftware/
│
├── controller # REST Controllers
├── service # Business Logic
├── entity # Database Models
├── repository # JPA Repositories
├── security # JWT & Security Config
├── config # App Configuration


---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- Java 17+
- Maven (`mvn -v`)
- Node.js & npm (`node -v`, `npm -v`)
- MySQL Database (e.g., freesqldatabase.com)
- AWS S3 Bucket (for file uploads)
- Stripe Account (for payments)

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/billingsoftware.git
cd billingsoftware
2️⃣ Configure Backend

Go to:

src/main/resources/application.properties

Update the following:

MySQL Database credentials
AWS S3 keys
JWT secret key
Stripe secret key
3️⃣ Run Backend (Spring Boot)
./mvnw clean install
./mvnw spring-boot:run
4️⃣ Run Frontend (React)
cd client
npm install
npm run dev
⚠️ Important Notes
Ensure API URLs in React (Axios) match your backend endpoints.
Backend must be running before frontend.
Configure CORS if needed.
Use environment variables for sensitive data in production.
📌 Future Improvements
Email notifications for orders
Invoice PDF generation
Advanced analytics dashboard
Multi-user collaboration
🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

📄 License

This project is licensed under the MIT License.

👩‍💻 Author

Aarohi Goel


---
