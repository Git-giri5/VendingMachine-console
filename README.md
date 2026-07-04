# 🥤 Vending Machine System in Java

A console-based **Vending Machine System** developed using **Object-Oriented Programming (OOP)** and **Low-Level Design (LLD)** principles in Java. The application simulates a real-world vending machine by managing product inventory, accepting coin payments, dispensing products, and returning change.

This project was created as part of **Weekend Dev Challenge #57: LLD Projects** to strengthen Java programming, software design, and problem-solving skills.

**Java | OOP | LLD | CodeChef**

---

# 🏆 About the Challenge

This project was developed for **Weekend Dev Challenge #57: Low-Level Design (LLD) Projects** to practice designing scalable applications using Java and Object-Oriented Programming concepts.

🔗 CodeChef: https://www.codechef.com

🔗 My CodeChef Profile: https://www.codechef.com/users/girit9080

---

# 🚀 Features

### 🥤 Supports Multiple Products

- Coffee
- Tea
- Soft Drinks
- Snacks
- Water Bottle

### 💰 Coin-Based Payment System

- Accepts multiple coin denominations
- Calculates total inserted amount

### 🛒 Product Selection

- Displays available products
- Checks stock availability
- Dispenses selected product

### 💵 Automatic Change Calculation

- Returns remaining balance after purchase

### 📦 Inventory Management

- Tracks product quantity
- Updates stock after every purchase

### ⚠️ Exception Handling

- Insufficient Balance
- Out of Stock
- Invalid Product Selection

### 📚 Modular Object-Oriented Design

---

# 📂 Project Structure

```
VendingMachine/
│
├── Main.java
├── Product.java
├── ProductType.java
├── Coin.java
├── Inventory.java
├── VendingMachine.java
├── Payment.java
├── Transaction.java
├── ChangeCalculator.java
└── CustomException.java
```

---

# 🛠 Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Low-Level Design (LLD)
- Java Collections Framework
- HashMap
- ArrayList
- Queue
- Exception Handling

---

# 🧩 OOP Concepts Implemented

- Classes and Objects
- Inheritance
- Abstraction
- Polymorphism
- Encapsulation
- Composition
- Enums
- Custom Exceptions

---

# 🏗 Design Highlights

## Product Inventory Management

The vending machine maintains a list of available products along with their prices and stock quantity.

## Payment Processing

The system validates the inserted amount before dispensing the selected product.

## Automatic Change Return

If the inserted amount exceeds the product price, the remaining balance is automatically returned as change.

---

# ▶️ How to Run the Project

## Clone the Repository

```bash
git clone https://github.com/Git-giri5/VendingMachineSystem.git
```

## Navigate to the Project Directory

```bash
cd VendingMachineSystem
```

## Compile the Program

```bash
javac *.java
```

## Run the Program

```bash
java Main
```

---

# 🎮 Sample Output

```
========== Vending Machine ==========

Available Products

1. Coffee       ₹20
2. Tea          ₹15
3. Coke         ₹40
4. Water        ₹10

Select Product: 1

Insert Coins: ₹20

Processing Payment...

Coffee Dispensed Successfully!

Remaining Balance: ₹0

Thank You for Using the Vending Machine!

=====================================
```

---

# 🔮 Future Enhancements

- Digital Payment Integration (UPI/Card)
- Product Restocking Module
- Admin Dashboard
- Sales Report Generation
- Multiple Vending Machines
- Database Integration (MySQL)
- Graphical User Interface (GUI)
- Online Inventory Monitoring

---

# 👨‍💻 Author

**Giri**

Computer Science Engineering Student (2027 Graduate)

Passionate Java Developer | Problem Solver | Continuous Learner

🔗 GitHub: https://github.com/Git-giri5

🔗 CodeChef: https://www.codechef.com/users/girit9080

---

# 🌟 Acknowledgement

This project was developed as part of **Weekend Dev Challenge #57: Low-Level Design (LLD) Projects** to strengthen Java programming, Object-Oriented Programming (OOP), and software design skills.

---

⭐ If you found this project useful, don't forget to **Star ⭐ the repository!**
