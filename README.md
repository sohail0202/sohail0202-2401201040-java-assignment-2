# 🎓 Student Management System (Java)

**Robust, console-based CRUD app to manage students, built with core Java.**

---

## ✅ Status
**Java Platform**

---

## ✨ Features

- ✅ Add, update, delete, and list students  
- 🧭 Search students by ID or name  
- 🧩 Simple model + service design for clarity  
- 💾 In-memory storage for easy testing and demos  

---

## 🗂️ Project Structure


> **Note:** There may be duplicate sources under `src/model/.../service` from intermediate work. Use the `src/` top-level as the canonical source path.

---

## 🧰 Requirements

- Java 8 or newer (JDK)  
- Windows PowerShell, CMD, or any terminal

---

## 🚀 Build & Run

Compile to `bin/` and run the CLI app.

### From project root:

```bash
# 1) Create bin dir if missing
mkdir bin 2> NUL

# 2) Compile sources to bin
javac -d bin -sourcepath src src/MainApp.java

# 3) Run the program
java -cp bin MainApp

mkdir bin -ErrorAction SilentlyContinue
javac -d bin -sourcepath src src/MainApp.java
java -cp bin MainApp
===== Student Management System =====
1. Add Student
2. Update Student
3. Delete Student
4. List Students
5. Search Student
0. Exit
Enter choice: 1
Enter id: 101
Enter name: Alice
Enter age: 20S
Enter course: CS
Student added successfully ✅

Enter choice: 4
ID   NAME    AGE  COURSE
101  Alice   20   CS


# sohail khan (2401201040)
---


