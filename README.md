<div align="center">

# 🎓 SmartLearn

### A Modern Smart Learning System Built with React, Vite & Tailwind CSS

<p align="center">
  SmartLearn is a sleek and interactive learning platform designed for modern students.
  It combines course management, quizzes, analytics, discussion forums,
  certificates, and AI-ready architecture into one responsive educational experience.
</p>

<br>

![React](https://img.shields.io/badge/React-18-000000?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-5-000000?style=for-the-badge&logo=vite)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-000000?style=for-the-badge&logo=tailwindcss)
![React Router](https://img.shields.io/badge/React_Router-v6-000000?style=for-the-badge&logo=reactrouter)
![Recharts](https://img.shields.io/badge/Recharts-2-000000?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-000000?style=for-the-badge)

<br>

[Live Demo](#) • [Features](#-features) • [Installation](#-installation) • [Tech Stack](#-tech-stack)

</div>

---

# 📚 About The Project

SmartLearn is a full-featured **Learning Management System (LMS)** developed as a mini project by **Group 5** at **School of Future Tech, ITM Skills University**.

The platform simulates a complete online education ecosystem, including:

- Student Dashboard
- Course Management
- Interactive Quizzes
- Progress Tracking
- Discussion Forums
- Learning Resources
- Completion Certificates
- Instructor Profiles

The entire project is built using **React component architecture**, **client-side routing**, and a centralized mock-data structure without requiring a backend.

---

# ✨ Features

## 🏠 Landing Page
- Modern hero section
- Features showcase
- Testimonials
- Pricing section
- Fully responsive UI

## 📖 Course Catalog
- Browse available courses
- Search functionality
- Category filtering
- Difficulty level filtering
- Progress indicators

## 🎥 Video Learning System
- Simulated video player
- Lesson navigation
- Progress tracking
- Interactive learning flow

## 🧠 Quiz Engine
- Multiple-choice quizzes
- Instant feedback
- Score calculation
- Quiz completion tracking

## 📊 Analytics Dashboard
- Learning statistics
- Bar charts
- Line charts
- Student progress overview

## 💬 Discussion Forum
- Threaded discussions
- Instructor badges
- Replies and interactions
- Community-based learning

## 📂 Learning Resources
- Downloadable materials
- File filtering
- Resource categorization

## 🏆 Certificates
- Printable completion certificates
- Unique certificate IDs
- Course-based generation

## 👨‍🏫 Instructor Profiles
- Instructor cards
- Detailed modal popups
- Experience and expertise showcase

---

# 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **React 18** | Frontend UI Library |
| **Vite 5** | Development & Build Tool |
| **Tailwind CSS 3** | Styling Framework |
| **React Router v6** | Routing |
| **Recharts** | Analytics & Charts |
| **Lucide React** | Icons |
| **clsx + tailwind-merge** | Dynamic class management |

---

# 📁 Project Structure

```bash
Smart-Learning-System/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── data/
│   ├── lib/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── index.html
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── package.json
```

---

# 🚀 Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/smart-learning.git
```

## 2️⃣ Navigate into the Project

```bash
cd Smart-Learning-System
```

## 3️⃣ Install Dependencies

```bash
npm install
```

## 4️⃣ Start Development Server

```bash
npm run dev
```

---

# 🌐 Open in Browser

```bash
http://localhost:5173
```

> If port `5173` is occupied, Vite will automatically assign another port.

---

# 🧭 Available Routes

| Route | Description |
|---|---|
| `/` | Landing Page |
| `/app` | Dashboard |
| `/app/courses` | Course Catalog |
| `/app/courses/:id` | Course Details |
| `/app/courses/:id/video/:lessonId` | Video Player |
| `/app/quiz/:id` | Quiz Page |
| `/app/progress` | Progress Dashboard |
| `/app/forum` | Discussion Forum |
| `/app/resources` | Resources |
| `/app/certificate/:courseId` | Certificate Generator |
| `/app/instructors` | Instructor Profiles |

---

# ⚡ Build for Production

```bash
npm run build
```

Preview production build:

```bash
npm run preview
```

The production-ready files will be generated inside the `dist/` folder.

---

# 🚀 Deployment

## Deploy on Vercel

```bash
npm install -g vercel
vercel
```

## Deploy on Netlify

Drag and drop the `dist/` folder into:

```txt
https://netlify.com/drop
```

## Deploy on GitHub Pages

Install gh-pages:

```bash
npm install -D gh-pages
```

Add this to `package.json`:

```json
"homepage": "https://your-username.github.io/smart-learning",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d dist"
}
```

Then run:

```bash
npm run deploy
```

---

# 📦 Dependencies

```json
{
  "dependencies": {
    "react": "^18.3.1",
    "react-dom": "^18.3.1",
    "react-router-dom": "^6.23.0",
    "recharts": "^2.12.7",
    "lucide-react": "^0.395.0",
    "clsx": "^2.1.1",
    "tailwind-merge": "^2.3.0"
  }
}
```

---

# 👥 Team

## Group 5 — Problem Statement 05

**School of Future Tech, ITM Skills University**  
**Cohort:** Larry Page  
**Academic Year:** 2025 – 2029

| Team Members |
|---|
| Subrata Panda |
| Japji Kaur |
| Sanika Kangane |
| Parth Sarova |

---

# 📄 License

This project is created for academic and educational purposes as part of the ITM Skills University mini project curriculum.

---

<div align="center">

## SmartLearn • Group 5 • ITM Skills University

</div>
