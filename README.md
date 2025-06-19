# 📣 Notification Engine

A real-time web-based notification delivery platform that supports **Email**, **SMS**, and **Push Notifications**. Built with **React**, **Firebase**, **Twilio**, **FastAPI**, and containerized with **Docker** for smooth deployment.

---

## 🚀 Features

- 📧 Send Email notifications
- 📱 Send SMS notifications (via Twilio)
- 🔔 Send Push notifications (via Firebase Cloud Messaging)
- 🕒 Real-time notification history dashboard
- 🐳 Dockerized backend for easy setup & portability
- 🌈 Clean, modern UI with TailwindCSS

---

## 🧱 Tech Stack

| Layer     | Tech Stack                                   |
|-----------|----------------------------------------------|
| Frontend  | React, TailwindCSS, Vite                     |
| Backend   | FastAPI, Python                              |
| Messaging | Firebase (FCM), Twilio                       |
| Storage   | SQLite (for message history)                 |
| Container | Docker (with `Dockerfile` for backend)       |

---

## 📦 Project Structure

notification-engine/
│
├── backend/ # FastAPI server
│ ├── main.py # Entry point
│ ├── notify.py # Notification logic
│ ├── Dockerfile # Docker setup for backend
│ └── ...
│
├── frontend/ # React client
│ ├── src/
│ │ ├── App.jsx
│ │ ├── NotificationSetup.jsx
│ │ └── firebase.js
│ ├── .env # 🔒 Firebase keys (not committed)
│ └── ...
│
├── database/ # SQLite or DB storage
│
└── README.md
