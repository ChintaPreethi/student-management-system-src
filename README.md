# Student Management System 🎓

A simple console-based Student Management System developed using Java. It allows users to manage student records through a menu-driven interface.

## 🚀 Features

* Add student
* Unique Student ID validation
* View all students
* Search student by ID
* Update student details
* Delete student
* Store student name, age, course, and marks
* Menu-driven console interface

## 🛠️ Technologies Used

* Java
* Object-Oriented Programming (OOP)
* ArrayList
* Scanner
* Getters and Setters

## 📁 Project Structure

```text
student-management-system/
│
├── src/
│   ├── Student.java
│   └── StudentManagementSystem.java
│
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Afrin-D/student-management-system.git
```

### 2. Compile the project

```bash
javac -d out src/*.java
```

### 3. Run the application

```bash
java -cp out StudentManagementSystem
```

## 💻 Sample Output

```text
===== STUDENT MANAGEMENT SYSTEM =====

1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit

Enter your choice: 1

Enter Student ID: 101
Enter Name: Afrin
Enter Age: 20
Enter Course: CSE
Enter Marks: 88.5

Student added successfully!
```

### Duplicate ID Example

```text
Enter Student ID: 101

Student ID already exists!
Please enter a unique ID.
```

## 📚 Learning Outcomes

* Practiced classes and objects
* Learned encapsulation
* Used constructors
* Practiced getters and setters
* Used ArrayList
* Implemented CRUD operations
* Added unique ID validation
* Built a real-world Java application

## 🔮 Future Improvements

* Add database connectivity
* Add login authentication
* Add grade calculation
* Add attendance management
* Create a graphical user interface

## 👩‍💻 Author

**Preethi c**
