# task-manager-api
A scalable backend REST API for managing personal tasks and productivity, built using Node.js, Express.js, MongoDB, and JWT authentication.
# 🗂️ Task Manager API

A scalable and secure backend API to manage tasks and boost personal productivity. Built with Node.js, Express, MongoDB, and JWT for user authentication.

---

## 📌 Features

- 🔐 User Registration and Login (JWT Auth)
- ✅ Create, Read, Update, Delete (CRUD) Tasks
- 🏷️ Task Categorization (e.g. Work, Personal)
- ⏰ Due-date tracking for tasks
- 🧠 Smart structure for productivity workflows
- 🧪 Postman-ready routes
- 📑 Markdown-based documentation

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB + Mongoose
- JSON Web Token (JWT)
- bcryptjs (password hashing)
- dotenv (environment variables)
- Postman (for testing)

---

## 📦 Installation & Setup

```bash
git clone https://github.com/your-username/task-manager-api.git
cd task-manager-api
npm install
```

Create a .env file in the root folder and add:

```
PORT=5000
MONGO_URI=mongodb://localhost:27017/task_manager
JWT_SECRET=your_super_secret_key
```

Then start the server:
```
npm run dev
```
🔐 API Authentication
All /api/tasks routes are protected

Use Authorization: Bearer <token> in headers after login/register

📬 API Endpoints
👤 Auth Routes
Method	Endpoint	             Description
POST	  /api/auth/register	   Register a new user
POST	  /api/auth/login	       Login and get token

🗂️ Task Routes
Method	Endpoint	      Description
GET	    /api/tasks	    Get all tasks (auth req.)
POST	  /api/tasks	    Create new task
PUT	    /api/tasks/:id	Update a task
DELETE	/api/tasks/:id	Delete a task



---

Let me know if you'd like the **README.md file generated as a real file** or if you'd like me to **upload everything to GitHub** directly on your behalf using a temporary repo.

