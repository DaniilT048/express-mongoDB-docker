# Backend Demo with MongoDB and Mongo Express

This project demonstrates a simple Node.js backend connected to a MongoDB database with a web interface for data management via Mongo Express. Everything is set up using Docker Compose.

## 📦 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongo Express
- Docker & Docker Compose

---

## 📁 Project Structure

```
.
├── docker-compose.yml
├── Dockerfile
├── src
│   ├── db.js
│   └── server.js
├── .env
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git https://github.com/DaniilT048/express-mongoDB-docker
cd express-mongoDB-docker
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create `.env` file

```env
MONGO_CONNECTION=mongodb+srv://Т=InPM:PasswordInPM.@cluster0.p2hfeap.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
```

### 4. Run Docker Compose

```bash
docker-compose up --build
```

---

## 🔗 Access

| Service        | URL                   | Access          |
|----------------|------------------------|------------------|
| Backend (API)  | http://localhost:5000  | public           |
| Mongo Express  | http://localhost:8081  | admin:password   |

---

## 🧪 Sample Requests

### GET /

```
http://localhost:5000/docker
```

Response:

```json
{
  "message": "Hello from backend"
}
```

---

## 🖥 Screenshots

### 📸 1. Mongo Express Interface
![](./screenshots/mongo-express-interface.png)

### 📸 2. API Response
![](./screenshots/API-Response.png)

### 📸 3. Terminal Logs After Startup
![](./screenshots/Terminal-Logs-After-Startup.png)