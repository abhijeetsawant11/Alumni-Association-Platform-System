
# Key Features 

Alumni Registration and Profiles: Allow alumni to register, create, and update personal profiles, enabling the institution to maintain up-to-date records.

Networking Opportunities: Provide platforms for alumni to connect based on interests, professions, or geographic locations, fostering professional and social networks.

Event Management: Organize and promote events such as reunions, workshops, and seminars, with features for announcements, registrations, and feedback.

Job Portals: Offer job search and posting functionalities, connecting alumni with potential employers and career opportunities within the network.

Donation and Fundraising Modules: Facilitate secure online donations, supporting various institutional projects and initiatives.

Discussion Forums and Communication Tools: Enable interactive discussions, mentorship programs, and information sharing among alumni and current students.

Success Story Showcases: Highlight notable alumni achievements, inspiring current students and enhancing the institution's reputation.



# 🎓 Alumni Association Platform

A full-stack web application designed to manage alumni records and user roles. Built with Spring Boot and React.js.

---

## 🚀 Features

- 📝 Alumni registration and login
- 🔐 Role-based access (`STUDENT`, `ALUMNI`, `ADMIN`)
- 📚 Admin dashboard to manage alumni
- 🔍 Search and filter alumni by name, email, or batch
- ✏️ Edit or delete alumni profiles (Admin only)
- 🌐 Frontend: React.js + Bootstrap

---

## 🛠️ Tech Stack

| Layer        | Technology                |
|--------------|---------------------------|
| Backend      | Java 17, Spring Boot      |
| Frontend     | React.js, Axios, Bootstrap |
| Database     | MySQL                     |
| API Testing  | Postman                   |
| Build Tool   | Maven                     |
| Version Control | Git + GitHub            |

---

## ⚙️ Project Structure

```
/alumni-association-platform
│
├── backend/
│   ├── controller/
│   ├── model/
│   ├── repository/
│   ├── service/
│
├── frontend/
│   ├── React components
│   └── Alumni dashboard UI
```

---

## 🔧 How to Run the Project

### 🖥️ Backend (Spring Boot)

```bash
cd backend
mvn spring-boot:run
```

- Set DB connection in `application.properties`

### 🌐 Frontend (React.js)

```bash
cd frontend
npm install
npm start
```

---

## 🧪 Sample APIs

| Endpoint                | Method | Description |
|-------------------------|--------|-------------|
| `/api/alumni`           |    GET | Get all alumni |
| `/api/alumni/{id}`       | GET | Get alumni by ID |
| `/api/alumni/search?name=` | GET | Search alumni |
| `/api/alumni/{id}/update` | PUT | Update alumni profile |
| `/api/alumni/{id}/delete` | DELETE | Delete alumni profile |

---

## 👨‍💻 Author

**Abhijeet Sawant**  
🎓 PG-DAC | Java | Spring Boot | React  
📧 sawant40abhi@gmail.com

---


