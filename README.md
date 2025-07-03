# 🎯 Quiz Builder (Full Project)

**Quiz Builder** is a full-stack web application for building, managing, and taking quizzes. It consists of three separate applications:

---

## 🔗 Repositories

| Module                | Description                              | GitHub Repo                                                                 |
|-----------------------|------------------------------------------|------------------------------------------------------------------------------|
| Admin Dashboard  (almost completed)     | Admins can create, edit, publish quizzes | [quiz-admin-dashboard](https://github.com/YasmeenOthman/quiz-admin-dashboard) |
| Learner Dashboard  (under constructions)   | Learners can take quizzes                | [quiz-learner-dashboard](https://github.com/YasmeenOthman/quiz-learner-dashboard) |
| Backend Server        | Node.js API server for both dashboards   | [quiz-builder-backend](https://github.com/YasmeenOthman/quiz-builder-backend) |

---

## 🗂️ Architecture

```plaintext
                        ┌───────────────────────┐
                        │     Frontend Apps     │
                        └──────────┬────────────┘
                                   │
        ┌──────────────────────────┴──────────────────────────┐
        │                                                     │
┌───────────────┐                                   ┌────────────────────┐
│ Admin Dashboard│                                   │ Learner Dashboard │
└───────────────┘                                   └────────────────────┘
        │                                                     │
        └──────────────────────┬──────────────────────────────┘
                               │
                       ┌──────────────┐
                       │ Backend API  │
                       └─────┬────────┘
                             │
                       ┌──────────────┐
                       │   Database   │
                       └──────────────┘
```



## 📦 Tech Stack

- Frontend: React + MUI + React Router
- Backend: Node.js + Express + MongoDB
- Auth: JWT
- Hosting: Netlify (Frontend), Render/Heroku/Other (Backend)

---

## 📌 Status

🚧 This project is currently under development. Contributions and feedback are welcome!
