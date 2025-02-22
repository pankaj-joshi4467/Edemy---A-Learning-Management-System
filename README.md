# Full Stack Learning Management System (LMS) - MERN Stack

## 📌 Project Overview

The **Full Stack Learning Management System (LMS)** is a comprehensive web application designed to facilitate online learning by connecting **educators** and **students** in a seamless digital environment. Built using the **MERN (MongoDB, Express.js, React.js, Node.js) stack**, this platform empowers educators to **publish courses**, and students to **enroll, purchase, and watch courses** through an intuitive and responsive interface.

This LMS is designed to handle the **entire course lifecycle**, from content creation to student engagement, payments, and progress tracking. It integrates **modern authentication** and **secure payment solutions** to ensure a seamless and trustworthy learning experience.

### 🎯 Key Highlights:

- **Educator Dashboard** for managing courses, revenue, and student progress.
- **Student Portal** for browsing, enrolling, and tracking course completion.
- **Secure Authentication** with **Clerk**, ensuring data privacy and role-based access control.
- **Integrated Payment System** with **Stripe** to facilitate course purchases.
- **Responsive UI** ensuring compatibility across desktops, tablets, and mobile devices.
- **Efficient Course Management** with video content uploads and structured lesson plans.
- **Scalable Backend Architecture** to support a growing user base.

With a focus on **performance, security, and user experience**, this project aims to bridge the gap between learners and educators through a **feature-rich and accessible LMS**.

---

## 🚀 Features

### 👨‍🏫 For Educators

- Create and manage courses with structured lessons
- Upload and host video content
- Earn revenue through paid courses
- Secure authentication and access control with Clerk
- **Dashboard** for tracking earnings, students, and course analytics

### 🎓 For Students

- Browse a library of courses
- Enroll in and watch courses on-demand
- Secure payment processing via Stripe
- Progress tracking for completed lessons and courses
- User profile management with authentication

### 🔐 Authentication & Authorization

- **Clerk Integration** for user authentication and management
- Pre-built **Sign-In, Sign-Up, and Profile** UI components
- Role-based authentication (**Student & Educator**)
- Secure session handling and data privacy measures

### 💳 Payment Integration

- **Stripe payment gateway** for seamless transactions
- Encrypted and secure payment processing
- Purchase history tracking for students

### 📡 Tech Stack

- **Frontend:** React.js, Clerk Authentication
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Payment Gateway:** Stripe
- **State Management:** Context API / Redux (optional)

---

## 📂 Project Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/lms-mern.git
cd lms-mern
```

### 2️⃣ Install Dependencies

#### Backend:

```bash
cd server
npm install
```

#### Frontend:

```bash
cd client
npm install
```

### 3️⃣ Environment Variables

Create a **.env** file in the server directory and add the following:

```env
PORT=5000
MONGO_URI=your-mongodb-connection-string
STRIPE_SECRET_KEY=your-stripe-secret-key
CLERK_SECRET_KEY=your-clerk-secret-key
```

### 4️⃣ Start the Development Server

#### Backend:

```bash
cd server
npm start
```

#### Frontend:

```bash
cd client
npm start
```

---

## 📌 Folder Structure

```
LMS-MERN/
│── client/          # Frontend (React.js)
│── server/          # Backend (Node.js, Express.js)
│── models/          # Database Models (MongoDB)
│── routes/          # API Routes
│── controllers/     # Controller Logic
│── middleware/      # Middleware (Auth, Error Handling)
│── .env             # Environment Variables
│── README.md        # Project Documentation
```

---

## 📸 Screenshots

Home Page
![Screenshot 2025-02-21 231037](https://github.com/user-attachments/assets/0954c6ae-f0f8-4a1a-8b3c-a0a987aef2a3)

Login / Sign Up
![11](https://github.com/user-attachments/assets/7a11ada5-cefe-4e04-8b99-2bc43e6b5ab4)

Courses
![Screenshot 2025-02-21 231126](https://github.com/user-attachments/assets/87338c0b-f56b-4c08-8eff-bb39abc0ad28)

![5](https://github.com/user-attachments/assets/0be416c7-1a05-443d-b9e5-8e4be2486e02)

Seaarch Functionaility
![6](https://github.com/user-attachments/assets/39580f74-1acb-478b-90ee-ccf6050c3238)

Course Details
![7](https://github.com/user-attachments/assets/e709f2e9-3c58-4ffe-9f00-59a3fbae97a9)


Testimonials
![3](https://github.com/user-attachments/assets/905d3a1c-36ce-43a7-8378-65efe8f63118)

Footer
![4](https://github.com/user-attachments/assets/0787f280-b917-4ba0-b7e3-0b719f0522db)

Educator DashBoarrd
![9](https://github.com/user-attachments/assets/249ea3c5-0676-45cd-8f30-f214b26134de)

Enrollments
![8](https://github.com/user-attachments/assets/0043efe3-8d2e-43a3-a4e0-20469b7c6396)

My Courses
![10](https://github.com/user-attachments/assets/1dff17e2-bd62-4219-a412-830fda6c6596)












&#x20;&#x20;

---

## 🎯 Future Enhancements

- Implement **Live Classes** feature
- Integrate **Chat System** for discussions
- AI-powered **Personalized Course Recommendations**
- Gamification elements like **Badges & Certificates**

---



## 📜 License

This project is licensed under the **MIT License**.

