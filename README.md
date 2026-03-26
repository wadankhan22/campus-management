# Campus Management System 🎓

A professional, full-stack campus management solution built with modern technologies. This system provides a seamless experience for teachers and students to manage coursework, announcements, attendance, and grades.

## 🚀 Features
- **🔐 Secure Authentication**: JWT-protected login and registration with distinct Teacher and Student roles.
- **📢 Smart Announcements**: Real-time campus feed with automatic 1-week data cleanup (Cron jobs).
- **📋 Attendance Tracking**: Teachers can mark presence in bulk; students can track their history.
- **📚 Gradebook & Assignments**: Digital tracking of coursework and academic performance.
- **🎨 Premium UI/UX**: Modern Glassmorphism design with a persistent Dark Mode system.

## 🛠️ Technology Stack
### Backend
- **Framework**: NestJS (Node.js)
- **Database**: PostgreSQL
- **ORM**: TypeORM
- **Scheduling**: @nestjs/schedule (Cron)

### Mobile App
- **Framework**: React Native (Expo)
- **Navigation**: Expo Router
- **State Management**: Zustand
- **Persistence**: AsyncStorage

## 📸 Preview
*Check the `assets/` folder for high-quality screenshots and mockups.*

## ⚙️ Installation & Setup

### 1. Backend
```bash
cd backend
npm install
# Configure your .env with PostgreSQL credentials
npm run start:dev
```

### 2. Mobile App
```bash
cd mobile-app
npm install
npx expo start
```
*Scan the QR code with the Expo Go app.*

---
*Created with ❤️ for modern education.*
