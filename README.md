# 🎓 Capstone Project Management & Review System  

A role-based web application to streamline **capstone project selection, guide/reviewer assignment, and review scheduling** in colleges.  
The system automates manual tasks, provides dashboards for each role, and ensures transparent project tracking.  

---

## ✨ Features  

### 👨‍💼 Admin  
- Upload student, guide, and reviewer data in **JSON format**  
- Upload predefined project titles  
- Auto-assign guides and reviewers to groups  
- Manage deadlines, view all progress, and generate reports  

### 👩‍🎓 Students  
- Form groups (up to 3 members)  
- Select project titles (or propose new ones)  
- Upload project-related documents (proposal, report, PPT, etc.)  
- View assigned guide and reviewer  
- Book review slots based on reviewer availability  

### 👨‍🏫 Guides  
- View assigned groups/projects  
- Approve/reject proposed project titles  
- Provide guidance and progress feedback  

### 📝 Reviewers  
- View assigned projects  
- Set **availability slots** for reviews  
- Provide structured feedback and scores  

---

## ⚙️ Tech Stack  

- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js (Express.js) or Django  
- **Database:** MongoDB / PostgreSQL  
- **Authentication:** JWT / Firebase Auth (role-based)  
- **File Storage:** Firebase Storage / AWS S3  
- **Notifications:** Email / in-app alerts  

---

## 📂 Project Structure  

```bash
capstone-project-management/
│── backend/          # APIs, authentication, database models
│── frontend/         # React.js frontend code
│── data/             # JSON files for students, guides, reviewers, project titles
│── docs/             # Project documents, reports, diagrams
│── README.md         # Project documentation
