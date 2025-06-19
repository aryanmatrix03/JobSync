# 💼 JobSync – Job Application Tracker

**JobSync** is a powerful job application tracking platform built with the MERN stack. It helps job seekers manage, monitor, and organize their job applications, with a clean UI and modern UX.

---

## 🚀 Features

- 🧾 Add and update job applications
- 🗂 Categorize applications by status (Applied, Interview, Offer, Rejected)
- 📄 Resume/Profile upload using Cloudinary
- 🔐 Secure login and registration using JWT
- 🌐 Responsive UI built with React & TailwindCSS
- 📊 Dashboard analytics (Upcoming)

---

## 🛠 Tech Stack

### 🌐 Frontend
- React.js (Vite)
- Redux Toolkit
- Tailwind CSS
- Axios

### 🖥 Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer, Cloudinary
- JWT (Authentication)

---

## 📦 Installation Guide

### 1. Clone the repository
```bash
git clone https:https://github.com/aryanmatrix03/JobSync
cd jobsync
```

### 2. Setup Backend
```bash
cd backend
npm install
cp .env.example .env   # Fill in your MongoDB and Cloudinary keys
npm start
```

### 3. Setup Frontend
```bash
cd frontend
npm install
cp .env.example .env   # Add VITE_BACKEND_URL etc.
npm run dev
```

---

## 📁 Environment Variables

### Backend `.env`
```env
MONGODB_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Frontend `.env`
```env
VITE_BACKEND_URL=http://localhost:8000
```

---

## 🌐 Live Demo

🧪 Front-end: https://job-sync-w4uh.vercel.app/ 


---

## 📸 Screenshots

> Upload screenshots/GIFs here once UI is ready.  

> https://github.com/aryanmatrix03/JobSync/blob/main/home.png
> https://github.com/aryanmatrix03/JobSync/blob/main/details.png
> https://github.com/aryanmatrix03/JobSync/blob/main/companies.png
> https://github.com/aryanmatrix03/JobSync/blob/main/job.png
> https://github.com/aryanmatrix03/JobSync/blob/main/updateprofile.png

---

## 👨‍💻 Author

**Aryan Chaudhary**  
📫 [LinkedIn](https://www.linkedin.com/in/aryanchaudhary11336/) | 

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
