# 📚 Fullstack LMS Platform

A complete Learning Management System (LMS) built from scratch using React.js, Node.js, Express, MongoDB, and Redux Toolkit (RTK Query).
This project supports role-based access (Admin, Instructor, Student), payment integration via Stripe, file uploads, and dynamic course progress tracking.

---

## 🌟 Features

- 👤 User Authentication (JWT-based)
- 👨‍🏫 Role-based Access (Admin, Instructor, Student)
- 🎥 Add, Edit, Publish Courses & Lectures
- 📁 File Uploads via Multer & Cloudinary
- 💳 Secure Stripe Payment Integration
- 📊 Course Progress Tracking
- 🔐 Protected Routes
- 🌙 Light/Dark Mode
- 🧭 Search & Filter Courses
- 📈 Responsive Design with ShadCN UI

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Redux Toolkit (RTK Query)
- React Router DOM
- ShadCN UI
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose
- Multer (file uploads)
- Cloudinary (file storage)
- Stripe API (payments)

---

## 🚀 Getting Started

### Prerequisites
- Node.js and npm installed
- MongoDB setup (local or Atlas)
- Stripe account for payments
- Cloudinary account for image/video hosting

### Setup Instructions

#### 1. Clone the Repository

```bash
git clone https://github.com/Vaibhavthore12/E-Learning-platform.git
cd E-Learning-platform
cd backend
npm install
Create a `.env` file with the following:
  - MONGO_URI=your_mongodb_uri
  - JWT_SECRET=your_jwt_secret
  - CLOUDINARY_CLOUD_NAME=your_cloud_name
  - CLOUDINARY_API_KEY=your_key
  - CLOUDINARY_API_SECRET=your_secret
  - STRIPE_SECRET_KEY=your_stripe_key

npm run dev
cd ../frontend
npm install
npm start

