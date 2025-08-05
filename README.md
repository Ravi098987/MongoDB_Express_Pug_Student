# 🎓 Student Management System

A simple full-stack web application to manage student records using **Node.js**, **Express**, **MongoDB**, and **Pug**. This app supports CRUD operations like adding, editing, viewing, and deleting students.

---

## 🚀 Features

- ➕ Add a new student
- 📋 View list of all students
- ✏️ Edit student details
- ❌ Delete a student
- 🖼️ Templated with Pug and styled with CSS

---

## 🧰 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Templating**: Pug
- **Styling**: CSS

---

## 📁 Folder Structure

```
📦 root/
├── models/
│   └── Student.js         # Mongoose schema for Student
├── public/
│   └── style.css          # Stylesheet
├── views/                 # Pug templates
│   ├── edit.pug
│   ├── index.pug
│   ├── layout.pug
│   └── new.pug
├── server.js              # Main Express server
├── package.json           # Project dependencies
└── package-lock.json      # Dependency lock file
```

---

## 🛠️ Installation & Setup

### 1. 📦 Install Dependencies

```bash
npm install
```

### 2. 🌐 Set Up MongoDB

Ensure MongoDB is running locally or use MongoDB Atlas. Update the connection URI in `server.js` if needed.

Example:

```js
mongoose.connect("mongodb://localhost:27017/studentDB", {
  useNewUrlParser: true,
  useUnifiedTopology: true,
});
```

### 3. ▶️ Run the App

```bash
node server.js
```

Visit: [http://localhost:3000](http://localhost:3000)
