# 🏆 **ICPC2T** — *Inspiring Innovation*

[![Event](https://img.shields.io/badge/Event-ICPC%202025-blue)](https://icpc.global/)
[![Organization](https://img.shields.io/badge/Host-NIT%20Raipur-red)](https://nitrr.ac.in/)
[![Theme](https://img.shields.io/badge/Theme-Coding%20%26%20Collaboration-green)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **ICPC2T** is the official **coding and training platform of NIT Raipur** for the **International Collegiate Programming Contest (ICPC)**.  
> It serves as a **central hub for registration, contests, announcements, leaderboards, and training resources** for all participants under the ICPC2T initiative.  
>
> Developed and maintained by the **ICPC2T Tech Team**, it powers a seamless experience for contestants, mentors, and administrators alike.

🌐 **Official Website:** [https://icpc2t.nitrr.ac.in/#/](https://icpc2t.nitrr.ac.in/#/)

## 📸 **Conference Preview**

![ICPC2T Conference Banner](./48149ab7-22d8-4547-9c97-e3959d229c26.png)

---

## ✨ **Key Highlights**

- 🧭 **Centralized Dashboard** – Unified access to announcements, schedules, and team details.  
- ⚔️ **Contest Management** – Create, host, and monitor live coding contests.  
- 📊 **Dynamic Leaderboards** – Real-time standings with advanced filtering.  
- 📚 **Resource Hub** – Curated problem sets, tutorials, and ICPC archives.  
- 🧑‍🤝‍🧑 **User Management** – Role-based access for participants, mentors, and admins.  
- 🔐 **Secure Authentication** – Firebase-based login and role verification.  
- 🖥 **Responsive UI/UX** – Optimized for all devices for smooth contest experiences.  

---

## 🚀 **Tech Stack**

| Frontend | Backend | Database | Hosting | Authentication |
|-----------|----------|-----------|-----------|----------------|
| React.js, Tailwind CSS | Node.js, Express | MongoDB | Firebase Hosting | Firebase Auth |

---

## ⚙️ **System Overview**

1. **Frontend (React)**  
   Interactive UI built using React and Tailwind CSS, ensuring responsive design for mobile and web users.  

2. **Backend (Express + MongoDB)**  
   Handles contest logic, user data, leaderboards, and communication with Firebase Auth.  

3. **Authentication**  
   Firebase handles secure login for contestants, admins, and mentors with role-based privileges.  

4. **Live Contests**  
   Seamless contest experience with auto-refresh leaderboards and real-time data sync.  

---

## 📸 **Interface Preview**

*(Add screenshots of dashboard, leaderboard, and contest pages here)*  

---

## 🧑‍💻 **Getting Started**

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Nishantjha0007/Official-ICPC2T.git
cd Official-ICPC2T
2️⃣ Install Dependencies
npm install

3️⃣ Run the Development Server
npm start

4️⃣ Setup Environment Variables

Create a .env file in the root directory with the following:

REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
MONGO_URI=your_mongodb_connection_string

5️⃣ Build for Production
npm run build
