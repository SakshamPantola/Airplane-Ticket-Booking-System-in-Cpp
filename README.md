# ✈️ flySRM - Airline Ticket Booking System

A simple console-based Airline Ticket Booking System developed in **C++** using **Object-Oriented Programming (OOP)** concepts.

This project was created as a beginner-level academic project to simulate the basic functionalities of an airline reservation system, including flight booking, ticket management, cancellation, and customer feedback.

## 🚀 Features

* Flight Booking
* Booking Summary/View Ticket
* Edit Existing Booking
* Cancel Booking
* Customer Feedback System
* Passenger-Based Fare Calculation
* Multiple Travel Classes

  * Executive Class
  * Business Class
  * Economy Class
* Special Discount Offers

  * Student Offer
  * Defence Personnel Offer
  * First-Time Customer Offer
  * Senior Citizen Offer
* Frequent Flyer Benefits
* Basic Date Validation

## 🛠️ Technologies Used

* C++
* Object-Oriented Programming (Classes & Objects)
* Standard Template Library (STL - string)
* Console-Based User Interface

## 📋 Project Structure

The project is implemented using a single class:

### `flySRM`

Contains functionalities such as:

* `book()` → Book a flight ticket
* `view()` → View booking details
* `edit()` → Modify booking information
* `cancel()` → Cancel an existing booking
* `customer_feedback()` → Store customer feedback

## 💰 Fare Calculation

| Class     | Price Per Passenger |
| --------- | ------------------- |
| Executive | ₹10,000             |
| Business  | ₹7,500              |
| Economy   | ₹5,000              |

Additional discounts and upgrades are applied based on selected offers and frequent flyer status.

## ▶️ How to Run

### Compile

```bash
g++ flySRM.cpp -o flySRM
```

### Execute

```bash
./flySRM
```

For Windows:

```bash
g++ flySRM.cpp -o flySRM.exe
flySRM.exe
```

## 📸 Sample Workflow

1. Launch Application
2. Book a Flight
3. Enter Departure & Destination
4. Select Travel Class
5. Add Meals/Luggage
6. Apply Available Offers
7. View Booking Summary
8. Edit or Cancel Booking if Required

## 🎯 Learning Outcomes

This project helped in understanding:

* Classes and Objects
* Constructors
* Member Functions
* Conditional Statements
* Switch Cases
* User Input Handling
* Basic Validation Techniques
* Menu Driven Programming

## ⚠️ Known Limitations

* Data is not stored permanently.
* Single-user booking system.
* No database integration.
* Limited input validation.
* Booking information resets when the program closes.

## 🔮 Future Improvements

* Database Integration (MySQL/SQLite)
* File Handling for Persistent Storage
* Seat Selection System
* Multiple Flight Management
* Payment Gateway Simulation
* GUI Version using Qt or C++
* Online Booking Portal

## 👨‍💻 Author

Developed as a first-year C++ academic project to practice Object-Oriented Programming concepts and build a real-world inspired application.

---

⭐ If you found this project interesting, consider giving it a star on GitHub.
