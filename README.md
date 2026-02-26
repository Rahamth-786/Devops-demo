# Fullstack DevOps Demo 🚀

This is a simple Fullstack Application with:

- Backend: Node.js + Express
- Frontend: React
- API Communication between frontend and backend

---

## 📁 Project Structure

```
fullstack-devops-demo
 ├── backend
 │    ├── server.js
 │    └── package.json
 └── frontend
      └── App.js
```

---

## 🔹 Backend Setup

### 1️⃣ Go to backend folder

```bash
cd backend
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Start server

```bash
npm start
```

Backend runs on:

```
http://localhost:5000
```

Test API:

```
http://localhost:5000/api/message
```

---

## 🔹 Frontend Setup

### 1️⃣ Go to frontend folder

```bash
cd frontend
```

### 2️⃣ Install dependencies (if React app)

```bash
npm install
```

### 3️⃣ Start frontend

```bash
npm start
```

Frontend runs on:

```
http://localhost:3000
```

---

## 🔹 How It Works

- Frontend calls backend API:
  ```
  GET /api/message
  ```
- Backend responds with:
  ```
  Hello from Backend 🚀
  ```
- Message is displayed in frontend UI.

---

## 🛠 Technologies Used

- Node.js
- Express.js
- React.js
- Git & GitHub

---

## 🎯 Future Improvements

- Add Docker support
- Add docker-compose
- Add CI/CD pipeline
- Deploy to Kubernetes

---

## 👨‍💻 Author

Your Name
