Markdown
# 🏨 Hotel Reservation System

Simple room reservation system developed in Java with a focus on Object-Oriented Programming and custom exception handling.

The project simulates hotel booking creation and updates via terminal, applying business rules and date validation.

---

## 📸 Preview

![Preview](https://github.com/user-attachments/assets/d4c1c7d3-c17b-48d3-bb2b-e769722ab9a9)

---

## 🚀 Project Goals

This project was developed to practice core backend concepts in Java, including:

- Object-Oriented Programming (OOP)
- Encapsulation
- Constructors
- Method overloading
- Exception handling
- Custom exceptions (`DomainException`)
- Date handling with `Date`
- User input with `Scanner`

---

## 🛠️ Technologies Used

- **Java**
- **VS Code**
- **Git**
- **GitHub**

---

## 📂 Project Structure

```bash
src/
├── application/
│   └── Program.java
└── model/
    ├── entities/
    │   └── Reservation.java
    └── exceptions/
        └── DomainException.java

---

## ▶️ How to Run

### 1. Clone the repository

git clone https://github.com/Hyouem/exceptions-java.git

### 2. Enter the project folder

cd exceptions-java

### 3. Compile the project

cd src
javac application/Program.java model/entities/Reservation.java model/exceptions/DomainException.java

### 4. Run the program

java application.Program

---

## 💻 Example Output

Room Number: 101  
Check-in date (dd/MM/yyyy): 25/05/2026  
Check-out date (dd/MM/yyyy): 30/05/2026  

Reservation: Room 101, check-in: 25/05/2026, check-out: 30/05/2026, 5 nights

---

## ⚠️ Business Rules

- Check-out date must be after check-in date  
- Reservations cannot be updated with past dates  
- Input validation and domain rule enforcement  

---

## 📚 Concepts Applied

- Clean Code fundamentals  
- Layered architecture  
- Separation of concerns  
- Custom exception handling  
- Java best practices  

---

## 🎯 Purpose

This project was developed for educational purposes to strengthen backend development skills in Java.

---

## 👨‍💻 Author

**Maurício Dos Santos**

- LinkedIn: https://www.linkedin.com/in/mauricio-dos-santos-/
- GitHub: https://github.com/Hyouem
