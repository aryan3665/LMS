# 🎓 Learning Management System (LMS)

A full-stack MERN-based Learning Management System (LMS) designed to provide a complete online learning experience for students and instructors. The platform allows users to explore courses, purchase premium content, watch lectures, and track learning progress through a modern and responsive interface.

The project focuses on building a scalable e-learning platform with secure authentication, payment integration, course management, and smooth user experience.

---

# 🚀 Features

## 👨‍🎓 Student Features
- User Authentication (Login/Register)
- Browse and Search Courses
- Purchase Premium Courses
- Secure Online Payment Integration
- Access Video Lectures
- Track Course Progress
- Responsive Student Dashboard
- Profile Management

## 👨‍🏫 Admin/Instructor Features
- Create and Manage Courses
- Upload Course Videos & Materials
- Edit/Delete Courses
- Manage Students & Enrollments
- Monitor Payments
- Admin Dashboard

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Redux Toolkit / Context API
- React Router DOM
- Axios

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

## Authentication & Security
- JWT Authentication
- bcrypt.js Password Hashing
- Protected Routes

## Payment Integration
- Razorpay / Stripe

## Cloud & Storage
- Cloudinary
- Multer

---

# ✨ Key Highlights

- Full-stack MERN application
- Secure JWT-based authentication system
- Real-time course access after payment verification
- Modern and fully responsive UI
- Role-based access control for students and admins
- RESTful API architecture
- Cloud-based media storage support
- Optimized backend routing and API handling

---

# 💳 Payment Integration

The platform includes secure online payment functionality for purchasing premium courses.

### Payment Flow
1. User selects a premium course
2. Payment order is created
3. User completes secure transaction
4. Payment is verified
5. Course access is granted instantly

---

# 🔐 Authentication System

- Secure user registration and login
- Encrypted password storage using bcrypt.js
- JWT token-based authentication
- Protected routes for authorized users only

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/lms-project.git
```

## Install Dependencies

### Frontend
```bash
cd client
npm install
```

### Backend
```bash
cd server
npm install
```

---

# ▶️ Run Project

## Start Backend
```bash
npm run server
```

## Start Frontend
```bash
npm start
```

---

# 🌐 Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=5000
MONGODB_URI=your_mongodb_url
JWT_SECRET=your_secret_key
CLOUDINARY_API_KEY=your_key
CLOUDINARY_SECRET=your_secret
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret
```

---

# 🔒 Security Features

- Password Hashing
- JWT Authentication
- Protected APIs
- Secure Payment Verification
- Environment Variable Protection

---

# 📈 Future Improvements

- Live Classes
- Quiz & Assessment System
- AI-based Course Recommendation
- Certificate Generation
- Multi-language Support

---

# 👨‍💻 Author

Developed by **ARYAN**
