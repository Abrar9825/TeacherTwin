# 🎓 AI Teacher Assistant

An **AI-powered Teacher Twin** platform where:
- Students can **ask doubts** anytime using a chatbot (text/voice).
- Teachers can **upload lectures, assignments**, and view student queries.
- AI replies in the **teacher's style/voice** to help students 24x7.

---

## 🚀 Features

### 👩‍🎓 Student Side
- Dashboard: View lectures, notifications, quick links
- Chatbot Page: Ask doubts → AI replies (text + optional voice)
- Assignments Page: See assignments, upload submission
- Profile Page: Manage student details

### 👨‍🏫 Teacher Side
- Dashboard: Overview of subjects, queries, notifications
- Upload Page: Upload lectures & create assignments
- Queries Page: View student questions & AI replies
- Profile Page: Manage teacher details (bio, specialization)

### 🤖 AI Integration
- Student queries → AI reply (OpenAI API)
- AI reply saved in DB + optional voice cloning

---

## 📂 Pages Overview (Total 9)

### Common
- `index.html` → Login/Register

### Student
- `student_dashboard.html`
- `student_chatbot.html`
- `student_assignments.html`
- `student_profile.html`

### Teacher
- `teacher_dashboard.html`
- `teacher_upload.html`
- `teacher_queries.html`
- `teacher_profile.html`

---

## 🛠️ Tech Stack

**Frontend:**  
- HTML, CSS, JavaScript (basic, beginner-friendly)  

**Backend:**  
- Node.js + Express.js  
- MongoDB (Atlas) + Mongoose ORM  

**AI:**  
- OpenAI API (GPT) for text replies  
- Optional: Coqui/Bark/OpenVoice for teacher-style voice  

---

## 👥 Team Roles

### Member 1 – Database (MongoDB Hero)
- Setup MongoDB Atlas (collections: users, subjects, lectures, queries, assignments)
- Insert dummy data

### Member 2 – Backend Developer
- Node.js + Express setup
- Auth, Lectures, Queries, Assignments APIs
- Integrate AI replies into queries

### Member 3 – Student Frontend
- Pages: Dashboard, Chatbot, Assignments, Profile
- Connect APIs via fetch()

### Member 4 – Teacher Frontend
- Pages: Dashboard, Upload, Queries, Profile
- Connect APIs via fetch()

### Member 5 – AI Integration
- OpenAI API integration
- Save AI replies in DB
- Voice cloning (future upgrade)

---

## 📅 Roadmap

### Week 1 – Setup
- MongoDB Atlas cluster + collections
- Node.js + Express backend skeleton
- Static HTML pages: index, student dashboard, teacher dashboard

### Week 2 – Auth + Lectures
- Auth API (login/register)
- Lectures APIs (add/view)
- Student + Teacher connect frontend to backend

### Week 3 – Queries + Chatbot
- Queries API
- Student chatbot → ask & see AI reply
- Teacher queries page → see student doubts
- AI integration (OpenAI reply stored in DB)

### Week 4 – Assignments + Profiles
- Assignment API + Submissions
- Student assignments page + Teacher upload assignment
- Student & Teacher profile pages

### Week 5 (Optional)
- Notifications system
- Voice reply integration

---

## 🔮 Future Improvements
- Real-time chat with AI (WebSockets)
- Advanced voice cloning per teacher
- Admin panel for managing users & subjects
- Analytics for teacher (student performance insights)

---

## 🤝 Contributing
1. Fork this repo  
2. Create a branch (`feature-new`)  
3. Commit changes  
4. Push and create Pull Request  

---

## 📜 License
MIT License – free to use and modify

