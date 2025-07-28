# 📝 Notes App

A full-stack Notes App built with **React.js** (Vite), **Node.js**, **Express**, and **MongoDB**. Users can register, log in, and manage their personal notes securely.

---

## 🚀 Features

* User registration and login with OTP-based email verification
* Create, edit, and delete notes
* Protected routes and localStorage session handling
* Responsive UI with Tailwind CSS
* MongoDB database with Mongoose models

---

## 📁 Project Structure

```
notes-app/
├── backend/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   └── index.js
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   └── components/
│   └── vite.config.js
└── README.md
```

---

## 🛠️ Prerequisites

* Node.js (v18+)
* MongoDB running locally or on MongoDB Atlas
* npm or yarn

---

## 🛆 Installation

### 🔧 Backend Setup

1. Go to the backend folder:

   ```bash
   cd backend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file and add your environment variables:

   ```env
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/notes-app
   JWT_SECRET=your_jwt_secret
   EMAIL_USER=your_email@gmail.com
   EMAIL_PASS=your_email_app_password
   ```

4. Start the backend server:

   ```bash
   node index.js
   ```

   > The backend will run on `http://localhost:5000`

---

### 💻 Frontend Setup

1. Go to the frontend folder:

   ```bash
   cd frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

   > The frontend will run on `http://localhost:5173` (or whatever port Vite chooses)

---

## 🏗️ Build for Production

To build the frontend for deployment:

```bash
npm run build
```

This will generate an optimized build in the `dist/` folder.

To preview the production build locally:

```bash
npm run preview
```

---

## 🌐 Deployment

* **Frontend**: Deploy the `dist/` folder to platforms like Netlify, Vercel, etc.
* **Backend**: Host on platforms like Render, Railway, or VPS (with Node.js and MongoDB)

---

## 🙋 Author

**Mohammad Zaid Khan**
🔗 [Portfolio](https://innospark.netlify.app) | [GitHub](https://github.com/64bitAtomic) | [LinkedIn](https://linkedin.com/in/mohammad-zaid-khan-020199260)

---

