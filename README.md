# Libapp 📚

Libapp is a Node.js-based backend application designed for managing library operations, including books, students, and borrowing records, powered by MongoDB.

---

## 🚀 Features

* **Book Management**: Add, update, and manage book records (`Libapp/models/Book.js`).
* **Student Management**: Maintain student profiles and information (`Libapp/models/Student.js`).
* **Borrowing System**: Track book borrowing and return transactions (`Libapp/models/Borrow.js`).
* **Database Integration**: Built-in support for MongoDB via the official MongoDB Node.js driver.

---

## 🛠️ Project Structure

```text
Libapp/
├── index.js             # Application entry point
├── models/
│   ├── Book.js          # Book schema/model
│   ├── Borrow.js        # Borrowing schema/model
│   └── Student.js       # Student schema/model
├── node_modules/        # Project dependencies
└── package.json         # Project metadata and dependencies
