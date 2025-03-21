# TrainEase - Online Gym & Personal Training Platform

## 📌 Project Overview
TrainEase is a web-based platform that provides online gym training and personal training services. Trainers can upload workout videos, and users can follow guided fitness programs. The platform enables remote coaching, personalized workout plans, and community engagement for fitness enthusiasts of all levels.

## 🚀 Features
🎥 **Video Upload & Streaming** - Trainers can upload workout videos to guide users.

🏋️‍♂️ **Personalized Training Plans** - Users can access structured training routines.

👥 **User & Trainer Profiles** - Create, manage, and update profiles.

🔐 **Authentication & Security** - Secure login with email/password and Google authentication.

📊 **Progress Tracking** - Users can log workouts and monitor progress.

💬 **Community Interaction** - Engage with trainers and other users through comments and likes.

🌎 **Responsive & Scalable** - Works seamlessly across devices.

## 🛠️ Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Authentication:** JWT, Google OAuth
- **Storage:** Cloudinary / Firebase Storage (for videos)
- **Deployment:** Vercel (Frontend), Render / Cloudflare (Backend)

## 📂 Folder Structure
📦 **TrainEase**  
 ┣ 📂 **client**       # React.js frontend  
 ┣ 📂 **server**       # Node.js backend  
 ┣ 📜 **.gitignore**   # Ignore unnecessary files  
 ┣ 📜 **README.md**    # Project documentation  
 ┣ 📜 **package.json** # Dependencies  
 ┗ 📜 **LICENSE**      # License details  

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/trainease.git
cd trainease
```
### 2️⃣ Install Dependencies
#### Backend:
```bash
cd server
npm install
```
#### Frontend:
```bash
cd ../client
npm install
```
### 3️⃣ Setup Environment Variables
Create a `.env` file inside `server/` and add:
```env
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your-secret-key
CLOUDINARY_API_KEY=your-cloudinary-api-key
```
### 4️⃣ Run the Project
#### Start Backend Server:
```bash
cd server
npm start
```
#### Start Frontend:
```bash
cd ../client
npm run dev
```

## 🌍 Deployment
- **Frontend:** Hosted on Vercel → [Live Link](#)  
- **Backend:** Hosted on Render / Cloudflare → [API Docs](#)

## 📌 Roadmap
✅ Video Upload & Streaming  
✅ Personalized Training Plans  
🔄 Live workout sessions (Real-time streaming)  
🔄 AI-based workout recommendations  
🔄 Mobile app version (React Native)  

## 📄 License
This project is licensed under the **MIT License**.

💡 **Contributions are welcome!** Feel free to open an issue or submit a pull request. 🚀