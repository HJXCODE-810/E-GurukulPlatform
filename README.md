# 📚 E-GurukulPlatform

**E-GurukulPlatform** is a web-based learning management system designed to connect **teachers** and **students** in a virtual classroom environment.  
It provides **separate dashboards** and features for each role, enabling **online learning, test-taking, and performance tracking**.

---

## 🚀 Features

### 👨‍🏫 Teacher Module
- Create and manage lectures (live or recorded).
- Upload study materials and assignments.
- Track student activities (attendance, tests, performance).
- Evaluate student submissions and give feedback.
- Dashboard for class performance insights.

### 👩‍🎓 Student Module
- Attend live or recorded lectures.
- Access study materials uploaded by teachers.
- Attempt online tests and quizzes.
- View performance reports and teacher feedback.
- Dashboard to track learning progress.

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript (React / Vite)  
- **Backend:** Node.js / Flask (customizable as per setup)  
- **Database:** MySQL / MongoDB  
- **Authentication:** JWT-based login (separate roles: Student / Teacher)  

---

## 🔑 Roles

### 🎓 Student
- Sign up / log in.
- Join assigned courses.
- Attend lectures and attempt tests.
- Check scores and progress report.

### 🧑‍🏫 Teacher
- Log in with teacher credentials.
- Create courses and lectures.
- Schedule and manage tests.
- Monitor students’ activities and performance.

---

## 📊 Workflow
1. **Teacher creates course → uploads lectures → assigns tests.**  
2. **Student joins course → attends lectures → attempts tests.**  
3. **System stores data → teacher dashboard shows performance tracking.**  
4. **Student dashboard displays learning progress & reports.**  

---

## ⚙️ Installation

```bash
# Clone repo
git clone https://github.com/your-username/E-GurukulPlatform.git

# Move into project folder
cd E-GurukulPlatform

# Install dependencies
npm install   # For frontend (React/Vite)
# or
pip install -r requirements.txt   # For backend (Flask/Python)

# Run development server
npm run dev   # For frontend
# or
flask run     # For backend
```

## 📌 Future Enhancements
🤖 **AI-based performance recommendation system.**

💬 **Chat/Discussion forum between students and teachers.**

🔔 **Push notifications for lectures/tests.**

📱 **Mobile-friendly app version.**

🌐 **AI-based Live Translation using Sarvam AI.**
