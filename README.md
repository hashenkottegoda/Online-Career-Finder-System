# 💼 CareerFinder

**CareerFinder** is a full-featured job portal web application where users can:

- 🔍 Search for **jobs**, **companies**, and **interview questions**
- 📄 Upload and manage **resumes**
- 🧑‍💼 Share **interview experiences** to guide future applicants
- 🏢 Employers can **post jobs**, **advertise companies**, and manage listings

---

## 🧰 Tech Stack

Built with the **MEAN Stack**:

| Technology | Role                          |
|------------|-------------------------------|
| 🟢 MongoDB | NoSQL Database                 |
| 🚂 Express | Backend Framework (Node.js)   |
| 🅰️ Angular | Frontend Framework (TypeScript) |
| 🟨 Node.js | Backend JavaScript Runtime     |

---

## 🚀 Getting Started

### ✅ Prerequisites

- **Node.js** installed: [Node.js official site](https://nodejs.org/)
- **Angular CLI** installed globally:
  ```bash
  npm install -g @angular/cli
  ```

---

### 📦 Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/careerfinder.git
   cd careerfinder
   ```

2. **Install server-side dependencies**:
   ```bash
   cd server
   npm install
   ```

3. **Install client-side dependencies**:
   ```bash
   cd ../client
   npm install
   ```

4. **Run client & server concurrently**:
   ```bash
   npm run both
   ```

   > This script will start both the Angular frontend and the Express backend at once.

---

## 🧪 Features

- **Job Search** with filters
- **Resume Upload & Management**
- **Company Directory**
- **Interview Question Bank**
- **Employer Dashboard** for job posting and advert management
- **User Feedback** via interview experience posts

---

## 📁 Folder Structure (Simplified)

```
careerfinder/
├── client/       # Angular frontend
├── server/       # Express backend
├── README.md
```

---

## 📌 Notes

- The project uses `concurrently` to run backend and frontend in one terminal.
- Make sure MongoDB is running before starting the app.
- Use `.env` for configuring backend variables (e.g., DB URL, ports).

---

## 📃 License

This project is intended for academic and professional learning purposes.
