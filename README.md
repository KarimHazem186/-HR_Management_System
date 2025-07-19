# 🌐 HR Management System

A comprehensive and scalable **Human Resources Management System** built for modern organizations to efficiently manage employees, departments, payroll, leave, attendance, and financial entitlements — all while adapting to **country-specific tax and labor laws**.

🚀 **Live Demo**: [View Deployment](https://employee-frontend-gilt.vercel.app/login)  
🔐 **Admin Login**:  
- **Email**: `admin@gmail.com`  
- **Password**: `admin`
---
👤 **Employee**:
- **Email**: `employee@gmail.com`  
- **Password**: `employee`

---

## ✨ Features

### 👥 Employee Management
- Add, edit, and delete employee records
- Profile image uploads and file support
- Department assignment and branch affiliation

### 🏢 Department & Branch Management
- Manage multiple departments
- Support for multiple branches
- Department-based salary and entitlement policies

### 📅 Leave & Attendance
- Apply and approve/reject leave requests
- Track attendance with real-time status
- Automated leave calculations and history

### 💵 Salary & Financial Entitlements
- Monthly salary computation
- Real-time tax, gratuity, and deduction calculations
- Insurance handling based on country policy
- Salary reports for individuals and departments

### 🌍 Country-Specific Rules Engine
- Dynamic rules for:
  - **Tax systems**
  - **Gratuity calculations**
  - **Insurance policies**
  - **Legal deductions**
- Easily extendable to support more countries

### 📊 Reporting System
- Employee reports with filters (by department, date, etc.)
- Leave and attendance reports
- Salary and financial history tracking

---

## 🛠️ Built With

| Tech Stack     | Description                          |
|----------------|--------------------------------------|
| **Frontend**   | React.js, Axios, Bootstrap CSS        |
| **Backend**    | Node.js, Express.js, Mongoose (MongoDB) |
| **Database**   | MongoDB Atlas                        |
| **Deployment** | Vercel (Frontend), Render/Other (API) |
| **Auth**       | JWT-based authentication             |

---

## 🔐 Access Roles

- 👑 **Admin**: Full access to all modules
- 👤 **Employee**: View profile, apply for leave, track salary and attendance

---

## 🧪 How to Use Locally

1. Clone the project

   ```bash
   git clone https://github.com/yourusername/hr-management-system.git
Install dependencies

bash
Copy
Edit
cd backend
npm install

cd ../frontend
npm install
