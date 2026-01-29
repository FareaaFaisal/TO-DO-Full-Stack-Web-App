# TO-DO Full Stack Web App

A modern full-stack To-Do web application built with Next.js / React for the frontend and FastAPI + SQLModel for the backend.
This project was developed following Spec-Driven Development (SDD) using Gemini-CLI with SpecKit Plus, and I also created agents and skills using Claude Code to automate certain frontend and backend tasks.
The UI features beautiful moving animations, and the backend uses a Neon database for storage along with enhanced authentication for secure user management.
Users can create, update, complete, and delete tasks with real-time updates and a smooth, visually appealing interface.

---

## Features

- **User Authentication:** Sign up and log in with JWT tokens.
- **CRUD Operations:** Create, Read, Update, Delete tasks.
- **Task Completion:** Mark tasks as completed or pending.
- **Filtering & Sorting:** Filter tasks by status and sort by date or title.
- **Responsive UI:** Works on desktop and mobile devices.
- **Secure API:** Backend validates users and protects task access.

---

## Tech Stack

**Frontend:**

- Next.js (React)
- TypeScript
- Tailwind CSS
- Axios for API requests

**Backend:**

- FastAPI
- SQLModel + PostgreSQL
- JWT/Better Auth Authentication
- Uvicorn server

**Database:**

- NEON Serverless POSTGRES Database

---

## Getting Started

### **Backend Setup**

1. Go to the backend folder:
   ```bash
   cd backend
   ```

2. Create virtual environment and activate:
  ```bash
  python -m venv venv
  venv\Scripts\activate      # Windows
  source venv/bin/activate   # Mac/Linux
  ```

3. Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```

4. Set up environment variables (.env):
  ```env
  DATABASE_URL=postgresql://username:password@localhost:5432/todo_db
  SECRET_KEY=your_secret_key
  ```

5. Run the backend server:
  ```bash
  uvicorn app.main:app --reload --port 8000
  ```

---

### **Frontend Setup**

1. Go to the frontend folder:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables (.env):
```env
NEXT_PUBLIC_API_URL=http://localhost:8000/api/v1
```

4. Run the frontend:
```bash
npm run dev
```

5. Open your browser at http://localhost:3000

---

### **Usage**

1. Sign up or log in.
2. Create a new task using “Add Task” button.
3. Edit or delete tasks as needed.
4. Filter tasks by status (All, Pending, Completed) and sort them.
5. Mark tasks as completed using the Mark Done / Completed button.

---

### **License**

This project is open source and available under the MIT License.

---

### **Author**

Fareaa Faisal

GitHub: https://github.com/FareaaFaisal
