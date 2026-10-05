# Janus Server

**The Node.js backend powering Janus, a property management mobile app.**

A REST API built with Express and MongoDB that stores properties, their buildings, and the visits registered by the Janus mobile app.

[![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)](https://nodejs.org/) [![Express](https://img.shields.io/badge/Express.js-000000?logo=express)](https://expressjs.com/) [![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/)

---

## 📖 Overview

Janus Server is the backend for the Janus mobile app, which manages properties and the buildings inside them. Buildings see regular activity such as maintenance, cleaning, and visits, and the server stores each visit along with its purpose.

The mobile client lives in [janus-app](https://github.com/jonathanadel-dev/janus-app).

---

## ✨ Core Features

- 🏢 **Properties & Buildings**: Store and retrieve properties and the buildings inside them
- 📝 **Visit Records**: Register visits and their purpose (maintenance, cleaning, visiting)
- 🗄️ **MongoDB**: Persistent data storage with Mongoose
- 🔌 **REST API**: JSON endpoints consumed by the mobile app

---

## 🏗️ Architecture

A simple Express-based REST API.

```
janus-server/
├─ models/       → MongoDB / Mongoose models
├─ routes/       → API route handlers
├─ utils/        → Shared utilities
├─ index.js      → Application entry point
├─ Procfile      → Process configuration for deployment
└─ package.json  → Project configuration
```

---

## 🛠️ Tech Stack

| Layer     | Technology |
| --------- | ---------- |
| Runtime   | Node.js    |
| Framework | Express.js |
| Database  | MongoDB    |
| API Format | REST      |

---

## 📌 Project Status

Janus Server is the backend component of the Janus property management app and was built alongside the mobile client.

---

Built by **Jonathan Adel**