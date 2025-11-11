# 🧠 USTHB Forms — Intelligent Automatic Form Generation Platform

## 📖 Overview

**USTHB Forms** is an intelligent web platform designed to **automate the generation of administrative and academic forms** at the **University of Science and Technology Houari Boumediene (USTHB)**.

This project streamlines the process of creating, managing, and publishing forms using **Artificial Intelligence**, reducing manual effort, eliminating repetitive tasks, and ensuring **consistency**, **efficiency**, and **data security** across departments.

---

## 🎯 Objectives

- Automate the form creation process to save time and minimize human error.  
- Enable dynamic form generation through **AI-powered suggestions**.  
- Standardize form design and structure within the institution.  
- Provide a unified, user-friendly interface for administrators, creators, and respondents.  

---

## 🚀 Core Features

### 🧩 Form Management
- Create forms **manually**, **via AI assistance**, or **from predefined templates**.  
- Edit, duplicate, or schedule form publications.  
- Maintain separate **draft** and **published** states for better organization.  

### 💬 AI Integration
- AI chat interface that interprets natural language to generate or modify forms.  
- Context-aware responses powered by **Google Generative AI (Gemini 2.0 Flash)**.  
- Intelligent suggestions for question types, categories, and validation rules.  

### 👥 User Roles
- **Administrators** – oversee all forms, responses, and user statistics.  
- **Form Owners** – create and manage their own forms, view analytics.  
- **Respondents** – fill out and submit forms through an intuitive interface.  

### 📈 Analytics & Visualization
- Real-time statistics on response rates and user engagement.  
- Exportable datasets in multiple formats (e.g., CSV, Excel).  

### 🔐 Security & Access Control
- Secure authentication and authorization system.  
- Role-based access control and session management.  
- Data integrity and backup through database replication and ACID compliance.  

---

## 🏗️ System Architecture

### 🖥️ Frontend

| Component | Technology |
|------------|-------------|
| **Framework** | Next.js — server-side rendering for high performance |
| **Language** | TypeScript — type safety and maintainable code |
| **Styling** | Tailwind CSS — fast, responsive UI design |
| **Animations** | @lottiefiles/dotlottie-react — interactive visual components |

---

### ⚙️ Backend

| Component | Technology |
|------------|-------------|
| **Runtime** | Node.js — asynchronous event-driven environment |
| **Framework** | Express.js — lightweight REST API framework |
| **ORM** | Sequelize — relational database mapping for MySQL |
| **Documentation** | Swagger UI — interactive API explorer |
| **File Management** | Multer + Cloudflare R2 — secure file upload and storage |
| **Validation** | Joi — schema validation for API requests |
| **Logging** | Winston + Logrotate — centralized logging and monitoring |

---

### 🤖 Artificial Intelligence

| Function | Technology |
|-----------|-------------|
| **AI Server** | Flask (Python) — RESTful microservice for AI communication |
| **Model** | Google Generative AI (Gemini 2.0 Flash) — context-aware text generation |
| **Data Parsing** | RegEx — for extracting structured JSON responses |
| **Session Context** | Custom state management for conversational continuity |

---

## 🧩 Database Schema (MySQL)

The database ensures **referential integrity** and **optimized query performance**.

**Main Tables:**
- `users` — user authentication and role management  
- `forms` — form definitions and publication metadata  
- `categories` — logical grouping of form sections  
- `questions` — question details and configurations  
- `choices` — predefined options for multiple-choice questions  
- `responses` — stored answers linked by form and question IDs  

---

## ⚙️ Installation & Setup Guide

### 1️⃣ Clone the Repository

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

2️⃣ Install Dependencies
npm install axios express cors
npm install @lottiefiles/dotlottie-react

3️⃣ Start the Proxy Server
node proxy.js

4️⃣ Run the Application
npm run dev


💡 You can also run both servers simultaneously:

npm run dev ; node proxy.js

🧠 Development Highlights

Modular backend architecture: Routes → Controllers → Services → Models

Seamless communication between Next.js frontend, Node.js backend, and Flask AI microservice

Enhanced user experience with real-time previews, AI chat, and responsive layouts

Strong focus on security, data consistency, and performance optimization

👨‍💻 Project Team
Name	
Akkouchi Nesrine	

Mouaci Rabie	

Khennouf Hamza	

Belakab Billal	

Dahmouche Melissa Ahlem	

Tayebi Souad	

Supervisor: Mme. Guendouz

Academic Year: 2024–2025

🏁 Conclusion

USTHB Forms is a complete, scalable, and AI-driven web platform built to modernize university document workflows.
By combining Next.js, Node.js, MySQL, and Generative AI, it delivers a reliable system that promotes digital transformation, consistency, and automation in academic administration.
