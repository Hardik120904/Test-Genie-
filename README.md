# Quiz Genie - Interactive Quiz Platform

A modern quiz platform where users can take subject-based quizzes, track their progress, and compete on the leaderboard.

## Features
- User authentication (Login/Register)
- Subject-based quiz generation
- Dynamic question generation
- Real-time leaderboard
- Responsive design with Tailwind CSS

## Tech Stack
- Frontend: React.js with Tailwind CSS
- Backend: Express.js
- Database: MongoDB
- Authentication: JWT

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Create a `.env` file in the backend directory with:
   ```
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```

4. Start the development servers:
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Start frontend server
   cd ../frontend
   npm start
   ```

## Project Structure
```
quiz-genie/
├── frontend/          # React frontend
├── backend/           # Express backend
└── README.md
``` 