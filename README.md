# Online Exam System with Real-Time Proctoring

## 📌 Overview
A secure, time-bound online examination platform that allows teachers to create MCQ-based tests and monitor them in real time.  
The system includes automatic scoring, violation detection, and exam termination rules to ensure fairness.

---

## 🚀 Key Features

### 👨‍🏫 For Teachers
- Create exams with MCQs and set a time limit.
- Share a **direct exam link** with students — no signup needed.
- View student scores immediately after the exam.
- Monitor student activity with real-time violation tracking.
- Exams end automatically after **three violations**.

### 🧑‍🎓 For Students
- No registration — enter your name and start the test.
- Time-bound MCQs with automatic submission when the timer ends.
- Proctoring ensures fair conduct during the exam.

---

## 🔒 Security & Integrity
- Real-time violation detection.
- Automatic termination after repeated violations.
- No login requirement reduces friction for students but still ensures identity capture through name input.

---

## 📖 Exam Flow

1. **Teacher creates exam** and shares a unique link.
2. **Student opens link** and enters their name.
3. **Exam starts** with a visible timer.
4. **Violation monitoring** runs during the attempt.
5. **Exam auto-submits** when:
   - Time runs out, or
   - Three violations occur.
6. **Teacher views results** instantly.

---

## 🛠 Tech Stack
- **Frontend:** [Vite](https://vitejs.dev/) (React)
- **Backend:** [Convex](https://convex.dev/)
- **Proctoring:** Real-time face violation detection
- **Deployment:**
  - **Frontend:** [Vercel](https://vercel.com/)
  - **Backend:** Convex Cloud Hosting

---

## 🌟 Advantages
- Simple and fast exam setup.
- No complicated student onboarding.
- Automatic scoring for instant results.
- Built-in integrity checks.

---

## 📜 License
This project is proprietary.  
No part of the code or system may be copied, modified, or distributed without explicit permission.
