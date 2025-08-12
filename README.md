# 🌟 My Portfolio — AI & MEAN Stack Intern

This is my personal **portfolio project** built during my internship, showcasing my skills in **MEAN stack development** and **AI/Machine Learning**.  
It contains a **frontend (Angular 20)** and **backend (Node.js + Express + MongoDB)**, with full CRUD functionality, a dashboard, and a contact form that sends messages directly to my database.

---

## 📂 Project Structure
```
backend/    # Node.js + Express + MongoDB server
frontend/   # Angular 20 application
```

---

## ✨ Features

### **Frontend (Angular 20)**
- **Beautiful UI** with Header, Footer, Home, About, Contact, Dashboard, Admin, and CRUD pages.
- **Home Page**: Displays profile, education, latest projects & skills with hover animations.
- **Projects**:
  - Add, edit, delete projects (with image upload).
  - Search projects by name.
  - View project details (like product pages).
- **Skills**:
  - Add, edit, delete skills (with icon upload).
  - Display skills as icons on home page.
- **Topics**:
  - Add course topics with grades (Intro, Backend, Frontend sections).
- **Dashboard**:
  - Project, skill, topic, and message counts.
  - Charts & histograms.
  - Messages table (mark read/delete).
- **Contact Form**:
  - Visitors can send messages.
  - Form validation (`*ngIf && (dirty || touched)` style from course).
- **CV Download Button**.

---

### **Backend (Node.js + Express + MongoDB)**
- **API Endpoints** for:
  - Projects (CRUD + image upload).
  - Skills (CRUD + icon upload).
  - Topics (CRUD).
  - Messages (create, get, mark read, delete).
  - Stats (counts for dashboard).
  - Download CV.
- File uploads stored in `/uploads` folder.
- Static serving of profile picture & CV.

---

## 🛠️ Technologies
**Frontend:**
- Angular 20
- HTML, CSS, TypeScript
- Reactive Forms
- Observables for data fetching

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- Multer for file uploads
- CORS

---

## 🚀 How to Run Locally

### 1️⃣ Clone the repo
```bash
git clone https://github.com/YourUsername/my-portfolio.git
cd my-portfolio
```

### 2️⃣ Run the backend
```bash
cd backend
npm install
npm start
```
Backend runs at: **http://localhost:4000**

> Place your CV file in `backend/public/CV.pdf`

---

### 3️⃣ Run the frontend
```bash
cd ../frontend
npm install
ng serve -o
```
Frontend runs at: **http://localhost:4200**

---

## 📸 Screenshots
_(Add screenshots of your portfolio UI here)_

---

## 📧 Contact Me
If you like my work or have opportunities for AI/MEAN stack roles, feel free to connect!
