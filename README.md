# 💓 Pulse - Real-time Website Monitor

**Pulse** is a full-stack monitoring solution designed to track website uptime and performance. It uses a microservices architecture with a **React** dashboard, a **Node.js** API, and a background **Worker** that pings sites every minute. Data is stored efficiently using **MongoDB Time Series** collections, and the entire stack is containerized with **Docker**.

## 🛠️ Tech Stack
* **Frontend:** React, TypeScript, Vite, Framer Motion, Recharts.
* **Backend:** Node.js, Express, TypeScript, node-cron.
* **Database:** MongoDB (Time Series).
* **DevOps:** Docker, Docker Compose.

## 🏃 Quick Start
1.  `git clone https://github.com/Sha-lvi23/Pulse-monitoring.git`
2.  `docker-compose up --build`
3.  Open `http://localhost:5173`

---

## 🚧 Project Status: Ongoing
This project is under active development.

## 🔮 Future Roadmap
* **☁️ Cloud Deployment:** Deploy to AWS ECS or Kubernetes.
* **🔐 Auth:** Add JWT authentication for multi-user support.
* **🔔 Alerts:** Integrate Email/SMS notifications for downtime.
