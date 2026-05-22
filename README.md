# 🏨 Hotel Reservation System

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

Simple room reservation system developed in Java with a focus on Object-Oriented Programming and custom exception handling.

The project simulates hotel booking creation and updates via terminal, applying business rules and date validation.

---

## 📸 Preview

![Preview](https://github.com/user-attachments/assets/d4c1c7d3-c17b-48d3-bb2b-e769722ab9a9)

---

## 🚀 Project Goals

This project was developed to practice core backend concepts in Java, including:

- **Object-Oriented Programming (OOP)**
- **Encapsulation**
- **Constructors & Method Overloading**
- **Exception Handling** (Custom exceptions with `DomainException`)
- **Date Handling** using `Date`
- **User Input** with `Scanner`

---

## 🛠️ Technologies Used

- **Java**
- **VS Code**
- **Git & GitHub**

---

## 📂 Project Structure

```text
src/
├── application/
│   └── Program.java
└── model/
    ├── entities/
    │   └── Reservation.java
    └── exceptions/
        └── DomainException.java
```

## ▶️ How to Run
1. Clone the repository
Bash
git clone [https://github.com/Hyouem/exceptions-java.git](https://github.com/Hyouem/exceptions-java.git)
2. Enter the project folder
Bash
cd exceptions-java
3. Compile the project
Bash
cd src
javac application/Program.java model/entities/Reservation.java model/exceptions/DomainException.java
4. Run the program
Bash
java application.Program

## 💻 Example Output
Plaintext
Room Number: 101  
Check-in date (dd/MM/yyyy): 25/05/2026  
Check-out date (dd/MM/yyyy): 30/05/2026  

Reservation: Room 101, check-in: 25/05/2026, check-out: 30/05/2026, 5 nights

## ⚠️ Business Rules

Check-out date must be after check-in date
Reservations cannot be updated with past dates
Input validation and domain rule enforcement

## 📚 Concepts Applied

Clean Code fundamentals
Layered architecture
Separation of concerns
Custom exception handling
Java best practices

## 🎯 Purpose

This project was developed for educational purposes to strengthen backend development skills in Java.

## 👨‍💻 Author

Maurício Dos Santos

LinkedIn: https://www.linkedin.com/in/mauricio-dos-santos-/

GitHub: https://github.com/Hyouem
