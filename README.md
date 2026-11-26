<div align="center">

# 🛠️ ToolShare

**Professional equipment booking platform: Client, Manager & Admin spaces**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=000) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=fff) ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=fff) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=fff) ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=fff) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=fff) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=000) ![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=fff) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=fff) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=fff)

[👩‍💻 Author](https://github.com/razaane)

</div>

---

## 📌 About

ToolShare lets users **book professional equipment across several stores**. Each store is supervised by a manager assigned by the administrator, and the platform tracks availability, reservations, loans and returns. This repository contains the Node.js / Express / MongoDB REST API that powers the React client.

> 🎓 Built during my training at **YouCode (UM6P) · Full Stack Web Development**.

## ✨ Features

- 🔐 JWT authentication with **Client / Manager / Admin** roles
- 🏬 Store management, with managers assigned to stores by the admin
- 🧰 Equipment catalogue per store with live availability
- 📅 Reservations: booking, loan, return and status tracking
- 🛡️ Middlewares to protect routes and ensure a manager only manages **their own store**
- 🧭 Layered architecture (controllers / services / repositories / validators)
- 📚 Swagger documentation at `/api-docs`
- 🧪 Jest + Supertest tests, ESLint, Docker & Docker Compose

## 🛠️ Tech Stack

`React` · `Node.js` · `Express` · `MongoDB` · `Mongoose` · `JWT` · `Swagger` · `Jest` · `Docker` · `GitHub Actions`

## 🚀 Getting Started

```bash
git clone https://github.com/razaane/ToolShare-App.git
cd ToolShare-App/backend
cp .env.example .env        # set JWT_SECRET
docker compose up --build   # API on http://localhost:3000
```
or without Docker:
```bash
npm install
npm run dev
```
Swagger UI: **http://localhost:3000/api-docs**

## 🧩 Main API resources
| Resource | Endpoint |
|---|---|
| Auth | `/api/auth` |
| Stores | `/api/stores`, `/api/admin/stores` |
| Equipment | `/api/equipments` |
| Reservations | `/api/reservations` |
| Manager space | `/api/manager` |
| Admin space | `/api/admin` |

Related repository: [ToolShare REST API (v1)](https://github.com/razaane/ToolShare-).


## 📁 Project Structure

```text
ToolShare-App/
└── backend/
    ├── docs/
    │   └── diagramme_classe.drawio
    ├── src/
    │   ├── config/
    │   ├── controllers/
    │   ├── middlewares/
    │   ├── models/
    │   ├── repositories/
    │   ├── routes/
    │   ├── services/
    │   ├── utils/
    │   ├── validators/
    │   ├── app.js
    │   ├── server.js
    │   └── swagger.js
    ├── tests/
    │   └── services/
    ├── .dockerignore
    ├── .env.example
    ├── .gitignore
    ├── docker-compose.yml
    ├── Dockerfile
    ├── eslint.config.js
    ├── package.json
    └── README.md
```

## 👩‍💻 Author

**Razane Wakhidi** · MERN Stack & Full Stack Developer · Safi, Morocco 🇲🇦

[![GitHub](https://img.shields.io/badge/GitHub-razaane-181717?style=flat-square&logo=github)](https://github.com/razaane)
[![Email](https://img.shields.io/badge/Email-wakhidirazane%40gmail.com-7C3AED?style=flat-square&logo=gmail&logoColor=white)](mailto:wakhidirazane@gmail.com)

> 💼 Open to work: MERN / Full Stack roles, internships & freelance.
