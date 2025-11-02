# 🌿 EcoVision

**EcoVision** is a full-stack AI-powered waste classification platform that promotes environmental awareness through technology and gamification.  
Users can upload images of waste, get instant classification results via a deep learning model, earn eco-points, and climb the global leaderboard.

---

## 🚀 Project Overview

EcoVision integrates **Machine Learning**, **FastAPI**, **Express.js**, and **React** to deliver a seamless user experience.  
The system rewards users for correctly classifying waste, building an engaging, eco-friendly digital community.

---

## 🧠 Key Features

- ♻️ **AI Waste Classification** – Uses a custom **EfficientNet-B0** model (PyTorch) served via **FastAPI** to predict waste type from uploaded images.  
- 🔐 **User Authentication** – Secure login and signup using **JWT**.  
- 🌱 **Eco-Points System** – Users earn points for each successful waste classification.  
- 🏆 **Leaderboard** – Real-time leaderboard displaying top eco-contributors.  
- 🔗 **Seamless Integration** – Backend (Express) communicates directly with the ML FastAPI service.  
- ☁️ **Cloud Deployment** –  
  - **Frontend:** Vercel  
  - **Backend:** Render  
  - **ML Service:** FastAPI (deployed separately) on Render

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React, Tailwind CSS |
| **Backend** | Node.js, Express.js, MongoDB |
| **Authentication** | JWT, bcrypt |
| **Machine Learning API** | FastAPI, PyTorch, EfficientNet-B0 |
| **Deployment** | Vercel (frontend), Render (backend), FastAPI (ML) on Render |

---

## 🏗️ System Architecture

```text
[React Frontend]  →  [Express Backend]  →  [FastAPI Model Server]
                            ↘                            ↘
                          [MongoDB]                  [PyTorch EfficientNet Model]
```

---

## 🌍 Deployment

- **Frontend (React)** → Vercel  
- **Backend (Express)** → Render  
- **ML Model (FastAPI)** → Deployed separately (Render / HuggingFace / custom server)

---

## 🧾 API Endpoints Overview

### Express Backend
| Method | Endpoint | Description |
|--------|-----------|-------------|
| `POST` | `/auth/signup` | Register new user |
| `POST` | `/auth/login` | User login |
| `POST` | `/api/predict` | Upload image → Forward to FastAPI |
| `GET` | `/api/leaderboard` | Fetch top users by eco-points |

### FastAPI ML Server
| Method | Endpoint | Description |
|--------|-----------|-------------|
| `POST` | `/predict` | Accepts image file and returns waste classification label |

---

## 🖼️ UI Preview

| Upload Screen | Leaderboard |
|:--------------:|:------------:|
| <img width="1919" height="1009" alt="Screenshot 2025-11-02 171009" src="https://github.com/user-attachments/assets/e4a7c973-8384-4012-88f5-4a3b4977cbf5" /> | <img width="1663" height="869" alt="Screenshot 2025-11-02 171101" src="https://github.com/user-attachments/assets/a3ab9379-7d8a-4c01-8f80-c36bd6e96b9b" /> |

---

## 🧑‍💻 Developer

**👤 Amrut Prasad Patro aka(Halloloid)**  
💼 Full-Stack Developer | ML Enthusiast  
🌐 [GitHub](https://github.com/Halloloid) 
---

## 🏁 Future Enhancements

- 🧩 Add community challenges  
- 📱 Launch mobile app version  
- 🌤️ Integrate with recycling location APIs  
- 💬 Add AI-based eco-tips and insights

---


---

> **EcoVision – Empowering a Greener Tomorrow through AI 🌎**
