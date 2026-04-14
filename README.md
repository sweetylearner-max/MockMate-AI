# MockMate AI 🎯

> AI-powered mock interview platform that simulates real interview scenarios, evaluates your answers, and gives structured feedback to help you land your dream job.

---

## ✨ Features

- 🎭 **Role-based Interviews** — Frontend, Backend, Full Stack, Python
- 🤖 **AI Question Generation** — Dynamic questions powered by Groq API
- 📊 **Answer Evaluation** — Score + detailed feedback on every answer
- 💡 **Performance Insights** — Strengths & areas to improve
- 🔐 **Authentication** — Login / Signup system
- 📱 **Responsive UI** — Works on all devices

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React (Vite) + Tailwind CSS |
| State Management | Context API |
| HTTP Client | Axios |
| AI / LLM | Groq API |

---

## 📁 Project Structure

```
MockMate-AI/
├── api/
│   └── groq.js               # Groq API server-side handler
├── public/
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── components/
│   │   ├── FeedbackCard.jsx  # Interview feedback UI
│   │   ├── Loader.jsx        # Loading spinner
│   │   ├── Navbar.jsx        # Navigation bar
│   │   ├── ProtectedRoute.jsx# Auth route guard
│   │   └── QuestionCard.jsx  # Interview question card
│   ├── context/
│   │   ├── AuthContext.jsx   # Authentication state
│   │   └── InterviewContext.jsx # Interview session state
│   ├── pages/
│   │   ├── Home.jsx          # Landing page
│   │   ├── Interview.jsx     # Interview session page
│   │   ├── Login.jsx         # Login page
│   │   ├── Results.jsx       # Results & feedback page
│   │   └── Signup.jsx        # Signup page
│   ├── services/
│   │   └── groq.js           # Groq API client
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env.example
├── index.html
├── package.json
└── vite.config.js
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sweetylearner-max/MockMate-AI.git
cd MockMate-AI
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create `.env` file

```env
VITE_GROQ_BASE_URL=https://api.groq.com/openai/v1
VITE_GROQ_API_KEY=your_api_key_here
VITE_GROQ_MODEL=your_model_here
```

### 4. Run the app

```bash
npm run dev
```

---

## 👩‍💻 Developed By

**Akanksha Bursu** — B.Tech CSE | QIS Ongole

[![GitHub](https://img.shields.io/badge/GitHub-sweetylearner--max-181717?style=flat&logo=github)](https://github.com/sweetylearner-max)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akanksha%20Bursu-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/akanksha-bursu-4b1544352/)