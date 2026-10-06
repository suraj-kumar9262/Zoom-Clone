# Zoom

A full stack video conferencing web application

## Features

- Sign up and log in
- Create or join a video meeting with a meeting code
- Real-time video calling using Socket.IO
- Meeting history page

## Tech Stack

- **Frontend:** React
- **Backend:** Node.js, Express, Socket.IO
- **Database:** MongoDB (Mongoose)

## Project Structure

- `backend/` : Express server, Socket.IO, models, routes
- `frontend/` : React app (landing, authentication, home, history and meeting pages)

## Setup

### Backend

1. `cd backend`
2. `npm install`
3. Create a file named `.env` inside the `backend` folder and add one line: `MONGODB_URI=your-mongodb-connection-string`
4. `node src/app.js`

The server runs on port 8000.

### Frontend

1. `cd frontend`
2. `npm install`
3. `npm start`

The app opens at http://localhost:3000

## Note

Never commit your `.env` file. It is already listed in `.gitignore`.
