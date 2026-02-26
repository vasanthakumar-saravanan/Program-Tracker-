````md
# 🚀 Programmer Progress Tracker

A **full-stack web application** that helps programmers track their coding practice **topic-wise**, analyze strengths and weaknesses, and visualize progress using interactive dashboards.

This project is built as an **academic mini-project / portfolio project** inspired by modern coding analytics platforms.

---

## 📌 Project Overview

The **Programmer Progress Tracker** allows users to:
- Log solved programming problems
- Categorize problems by topics such as Arrays, DP, Database, etc.
- Track difficulty levels
- View visual analytics to understand learning progress

---

## ✨ Features

- 🔐 User Authentication (Login / Signup)
- ➕ Add solved programming problems
- 🧠 Topic-wise tracking (Array, DP, Graph, DB, etc.)
- 📊 Analytics Dashboard  
  - Bar chart: Problems per topic  
  - Pie chart: Topic distribution
- 🎯 Difficulty-wise analysis (Easy / Medium / Hard)
- 📅 Track problem-solving history

---

## 🛠️ Tech Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Mongoose)

### Charts
- Chart.js

---

## 📂 Project Structure

```text
├── client/          # Frontend (React)
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.tsx
│
├── server/          # Backend (Node + Express)
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
│
├── README.md
└── package.json
````

---

## ⚙️ How to Run Locally

### Prerequisites

* Node.js (v16+ recommended)
* npm
* MongoDB (local or Atlas)

### Steps

```sh
# 1. Clone the repository
git clone <YOUR_GIT_URL>

# 2. Navigate into the project
cd <YOUR_PROJECT_NAME>

# 3. Install dependencies
npm install

# 4. Start the development server
npm run dev
```

The application will run at:

```
http://localhost:5173
```

---

## 📊 Analytics Logic

* Problems are grouped by **topic**
* Aggregation is used to calculate:

  * Total problems per topic
  * Percentage contribution
* Data is visualized using charts for better clarity

---

## 🎓 Use Case

* Students preparing for placements
* Competitive programmers
* Self-assessment of DSA preparation
* Resume & portfolio project

---

## 🚀 Future Enhancements

* 🔥 Daily streak tracking
* 📈 Platform-wise analytics (LeetCode / CodeChef / HackerRank)
* 📤 Export progress as PDF
* 🧑‍🤝‍🧑 Leaderboard
* 🌐 Production deployment with CI/CD

---

## 🧾 License

This project is created for **educational purposes**.
You are free to fork, modify, and improve it.

```
```
