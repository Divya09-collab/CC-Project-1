# Student Management System

A MERN student directory with a React/Vite frontend, Express API, and MongoDB database.

## Local installation

The frontend uses `http://localhost:5000/api` by default. Leave `VITE_API_URL` blank in `frontend/.env` for local development; fill it with the deployed API URL only when you deploy. The backend uses `MONGODB_URI` from `backend/.env`; a hosted Atlas database works while running the app locally. `FRONTEND_URL` may be set to `http://localhost:5173` or left blank to use the local default.

Start the API in one terminal:

```bash
cd backend
npm install
npm run dev
```

Start the client in a second terminal:

```bash
cd frontend
npm install
npm run dev
```

## API endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/api/students` | List students |
| GET | `/api/students/:id` | Get one student |
| POST | `/api/students` | Create student |
| PUT | `/api/students/:id` | Update student |
| DELETE | `/api/students/:id` | Delete student |

Request fields: `studentId`, `name`, `email`, `department`, `semester`, and `contact`.
