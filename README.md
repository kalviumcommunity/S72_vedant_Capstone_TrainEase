# S72_vedant_Capstone_TrainEase
TrainEase - Online Gym & Personal Training Platform

Overview

TrainEase is an online gym training and personal training web application where trainers can upload workout videos, and users can follow guided fitness programs. The platform enables remote coaching, personalized workout plans, and community engagement for fitness enthusiasts of all levels.

Features

🎥 Video Upload & Streaming – Trainers can upload workout videos to guide users.

🏋️‍♂️ Personalized Training Plans – Users can access structured training routines.

👥 User & Trainer Profiles – Create, manage, and update profiles.

🔐 Authentication & Security – Secure login with email/password and Google authentication.

📊 Progress Tracking – Users can log workouts and monitor progress.

💬 Community Interaction – Engage with trainers and other users through comments and likes.

🌎 Responsive & Scalable – Works seamlessly across devices.

Tech Stack

Frontend: React.js, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB Atlas

Authentication: JWT, Google OAuth

Storage: Cloudinary / Firebase Storage (for videos)

Deployment: Vercel (Frontend), Render / Cloudflare (Backend)

Installation

Prerequisites

Ensure you have Node.js and MongoDB installed.

Setup Instructions

# Clone the repository
git clone https://github.com/your-username/trainease.git
cd trainease

# Install dependencies
npm install

# Configure environment variables
cp .env.example .env
# Add MongoDB URI, Cloudinary keys, and other necessary environment variables

# Start the backend server
npm run server

# Navigate to frontend folder
cd client

# Install frontend dependencies
npm install

# Start the frontend server
npm start

API Endpoints

Authentication

POST /api/auth/register - Register a new user

POST /api/auth/login - User login

Users

GET /api/users/:id - Get user profile

PUT /api/users/:id - Update user details

Trainers & Workouts

POST /api/trainers/upload - Upload a workout video

GET /api/workouts - Fetch all workouts

GET /api/workouts/:id - Fetch a specific workout

DELETE /api/workouts/:id - Delete a workout

Deployment

Frontend: Hosted on Vercel - TrainEase Live

Backend: Hosted on Render / Cloudflare

Roadmap

📌 Live workout sessions (Real-time streaming)

📌 AI-based workout recommendations

📌 Mobile app version (React Native)

Contributing

Fork the repo

Create a feature branch (git checkout -b feature-name)

Commit changes (git commit -m 'Add feature')

Push branch (git push origin feature-name)

Open a Pull Request

License

This project is licensed under the MIT License.
