Got it — now I see the **correct project details.**
Here is a **professional README.md** based on the exact features and stack you listed.
Just copy-paste into your repository.

---

```md
# ✨ Full-Stack AI Interview Platform 🚀

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tech](https://img.shields.io/badge/Stack-MERN%20%7C%20Video%20SDK%20%7C%20Clerk%20Auth-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Pull Requests](https://img.shields.io/badge/PRs-Welcome-brightgreen)
![Deployment](https://img.shields.io/badge/Deployment-Sevalla-black)

---

## 🧠 Overview

The **Full-Stack Interview Platform** is an advanced interactive interview experience where users can:

- Join **1-on-1 video interview rooms**
- Write and execute code using a **real-time VSCode-powered editor**
- Receive **automated feedback** based on test cases  
- Practice coding challenges in **solo mode**
- Authenticate securely using **Clerk**
- Chat, share screen, toggle mic/camera and more — just like a real interview.

This platform simulates modern technical interviews with collaboration, real-time coding, audio/video calls, and automated judge support.

---

## ✨ Key Highlights

| Feature | Status |
|--------|--------|
| 🔐 Authentication (Clerk) | ✔ |
| 🎥 1-on-1 Video Interview Rooms | ✔ |
| 🧑‍💻 Real-time Code Editor | ✔ |
| ⚙️ Secure Code Execution | ✔ |
| 💬 Live Chat Messaging | ✔ |
| 📊 Dashboard with Live Metrics | ✔ |
| 📁 Practice Problems | ✔ |
| 🔊 Mic/Camera Controls + Screen Sharing | ✔ |
| 🔒 Room Lock / 2-participant limit | ✔ |
| 🔁 Background Jobs (Inngest) | ✔ |
| 🎉 Confetti + Fail Notifications | ✔ |

---

## 🛠 Tech Stack

### 🧩 Frontend

- React + Vite
- TanStack Query
- Clerk Authentication
- Video SDK (screen share, camera, mic)
- Monaco / VSCode Editor
- Tailwind CSS

### ⚙ Backend

- Node.js + Express
- MongoDB + Mongoose
- Secure Code Execution Sandbox
- Inngest (async tasks)
- REST API

### 🔧 DevOps / Integrations

- GitHub Workflow (PRs, branches, merges)
- CodeRabbit (PR review automation)
- Deployment: **Sevalla**

---

## 📂 Folder Structure

```

📦 Full-Stack-Interview-Platform
│
├── 📁 backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── server.js
│
└── 📁 frontend
├── src/
├── public/
└── vite.config.js

```

---

## 🔐 Environment Variables

### Backend (`/backend/.env`)
```

PORT=3000
NODE_ENV=development

DB_URL=your_mongodb_connection_url

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CLIENT_URL=[http://localhost:5173](http://localhost:5173)

```

### Frontend (`/frontend/.env`)
```

VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

VITE_API_URL=[http://localhost:3000/api](http://localhost:3000/api)

VITE_STREAM_API_KEY=your_stream_api_key

````

---

## 🚀 Installation & Usage

### ▶ Start Backend

```sh
cd backend
npm install
npm run dev
````

### ▶ Start Frontend

```sh
cd frontend
npm install
npm run dev
```

---

## 📸 Screenshots (Coming Soon)

| Feature           | Screenshot |
| ----------------- | ---------- |
| 🔐 Authentication | ⏳          |
| 🎥 Video Room     | ⏳          |
| 💻 Code Editor    | ⏳          |
| 📊 Dashboard      | ⏳          |

---

## 📌 Future Enhancements

* 🔍 AI voice feedback & scoring
* 🏆 Leaderboard for practice mode
* 📱 Mobile app version
* 🧠 AI interviewer persona system
* 🗂 Resume-based personalized challenges

---

## 👤 Author

**Marati Jashwanth Kumar**
💻 Aspiring Full-Stack Developer & Machine Learning Enthusiast

🔗 LinkedIn: *https://www.linkedin.com/in/jashwanthmarati*
🔗 GitHub: *https://github.com/jashwanth318/talent-IQ*

---

## 🪪 License

MIT License — free to learn, clone, and upgrade.

---

### ⭐ If you like this project, please give it a **star** on GitHub!

---

