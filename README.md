

## 📘 Student Management Information System (MIS) – IPRC Karongi

A simple **Web-Based Student Management System** for managing student records using AJAX, JSON, and XML technologies. Built as part of a deployment and data integration project.

---

### 🚀 Features

✅ Register new students
✅ Display all students dynamically (no page reload)
✅ Promote student level (AJAX `PUT`)
✅ Expel student (AJAX `PUT`)
✅ Export data to XML file
✅ Real-time department-based filtering
✅ Validates form inputs (including email)
✅ Integrated with free JSON server backend (Render)
✅ Responsive layout

---

### 🏗️ Project Structure

```
student-management-mis/
├── public/
│   └── index.html                # Main frontend
├── mock-api/
│   └── db.json                   # JSON data for backend
├── schemas/
│   ├── student-schema.json       # JSON Schema for validation
│   └── student-schema.xsd        # XML Schema (XSD)
├── screenshots/
│   └── deployment.png            # Example screenshots
└── README.md                     # This file
```

---

### 🌐 Live Demo

* 🔗 Frontend: [https://your-username.github.io/student-management-mis](#)
* 🔗 Backend API: [https://student-mis-api.onrender.com/students](#)

---

### 🧑‍💻 How to Run Locally

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/student-management-mis.git
   cd student-management-mis
   ```

2. **Run JSON Server Locally (Optional)**

   ```bash
   npm install -g json-server
   json-server --watch mock-api/db.json
   ```

3. **Open `public/index.html` in browser**

---

### 🗃️ Sample API Endpoints

* `GET /students` → Get all students
* `POST /students` → Register a new student
* `PUT /students/{id}` → Update student level or status
* `DELETE /students/{id}` → (Optional) Remove student

---

### 🧪 Screenshots

![Student Table](screenshots/deployment.png)

---

### 📑 Data Models

**JSON Schema**: Validates fields such as ID, name, department, email, etc.
**XML Export**: Downloadable `.xml` file with `<student>` records.
**XSD**: Used to validate XML report structure.

---

### 📦 Deployment Tools Used

| Component       | Platform                  |
| --------------- | ------------------------- |
| Frontend        | GitHub Pages / Vercel     |
| Backend         | Render (Free JSON Server) |
| Version Control | Git + GitHub              |

---

### ✍️ Author

Developed by the IT Technician  – **RP Karongi, Nyamishaba Campus**
Contact: *\[blaiseniyonsenga@gmail.com]*

