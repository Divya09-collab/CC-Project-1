# Backend

Express REST API for the application tier. Set `MONGODB_URI` and `FRONTEND_URL` in `.env`, then run `npm install` and `npm run dev`.

For local development, `FRONTEND_URL` can be left blank; the API allows `http://localhost:5173` by default.

For Render, set build command `npm install`, start command `npm start`, and configure `MONGODB_URI` plus `FRONTEND_URL=https://cc-p1-frontend.netlify.app`.
