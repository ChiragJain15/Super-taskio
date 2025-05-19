# 🍄 SuperTaskio — Gamified Task Manager with a Mario Twist

SuperTaskio is a fun, retro-inspired, interactive task manager designed to boost productivity using a Super Mario–style gamification system. Users can complete tasks, earn XP, level up, and unlock achievements — all in a visually nostalgic terminal-like aesthetic with 3D interactive elements.

---

## 📦 Tech Stack

### 🖥 Frontend
- **Next.js (App Router)**
- **Tailwind CSS**
- **ShadCN/UI**
- **Framer Motion**
- **Lucide Icons**
- **React Three Fiber (for 3D elements)**

### 🌐 Backend
- **Node.js + Express**
- **MongoDB + Mongoose**
- **JWT Authentication**
- **Dotenv + CORS**
- **Bcrypt for hashing**

---

## 🔑 Core Features

- ✅ User Registration & JWT Authentication
- 🎮 Gamified Task Completion (XP + Level System)
- 📋 Task Categories (e.g., Power-ups, Boss Fights)
- 🏆 Achievement System (Badges & Unlockables)
- 🗺️ Mario-style Level Map Progression
- 🔧 Admin Panel for User/Task Management
- 🎨 Retro 8-bit Pixel UI with Sound FX & Animations
- 📂 Clean Architecture (Separate client/server)

---

## 🧱 Folder Structure

super-taskio/
├── client/ → Frontend (Next.js)
├── server/ → Backend (Express API)
└── README.md → You're here!


---

## 🧪 Development Principles

| Rule | Description |
|------|-------------|
| ✅ **JWT Auth Only** | No sessions, all protected routes must validate JWT |
| 🧼 **DRY Principle** | Don’t Repeat Yourself – modularize repeated logic |
| 📦 **Atomic Design** | Reusable UI components using ShadCN/UI |
| ✨ **Clean Code** | Use Prettier + ESLint |
| 🔄 **Async/Await Only** | Consistent API logic |
| 🚫 **No Hardcoded Secrets** | Use `.env` for all keys and configs |
| 📡 **RESTful APIs** | All endpoints follow REST naming |
| 🧪 **Test as You Go** | Write unit tests and mock APIs |
| 🌍 **Responsive UI** | Mobile-first design using Tailwind utilities |

---

## ✨ Design System

- 🎨 **Theme**: Retro terminal with pixel fonts
- 🕹 Font: [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P)
- 🟡 Primary Color: `#facc15` (Coin Yellow)
- 🔴 Accent: `#ef4444` (Mario Red)
- ⚫ Background: `#0f172a` (Zinc Dark)
- 🧩 Components:
  - `LevelBar`
  - `TaskCard`
  - `AchievementModal`
  - `BrickButton`
  - `ProfilePanel`
  - `CoinCounter`
  - `WorldMapTracker`

---

## Contributions
Feel free to fork and contribute ideas, bug fixes, or new worlds to SuperTaskio!
