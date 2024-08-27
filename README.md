# 🏨 Hotel Reservation System

Welcome to the **Hotel Reservation System**! This Java-based application leverages Object-Oriented Programming (OOP) concepts to provide a comprehensive solution for managing hotel reservations. It offers a variety of features including creating, viewing, updating, and deleting reservations, as well as retrieving room numbers for a seamless guest experience.

## 🌟 Key Features

- **New Reservation:** Easily create a new reservation for guests, specifying details like guest name, room number, and contact information.
- **View Reservations:** Display all current reservations along with relevant details such as guest name, room number, contact information, and reservation date.
- **Get Room Number:** Retrieve the assigned room number for a reservation by providing the reservation ID and guest name.
- **Update Reservation:** Modify reservation details such as guest name, room number, or contact information.
- **Delete Reservation:** Cancel reservations that are no longer needed, using the reservation ID.
- **Exit:** Exit the system gracefully with a countdown and thank you message.

## 🚀 Technologies Used

- **Java:** The core programming language, leveraging OOP principles for robust and modular code.
- **JDBC (Java Database Connectivity):** For seamless interaction with the MySQL database.
- **MySQL:** A relational database management system used to store reservation data.
- **OOP Concepts:** Utilizes classes, objects, inheritance, polymorphism, encapsulation, and abstraction to create a flexible and maintainable codebase.

## 📂 Project Structure


## 📖 Getting Started

To get started with the project, follow these steps:

### Prerequisites

- Java Development Kit (JDK) 11 or above
- MySQL Database Server
- MySQL JDBC Driver

### Setting Up the Database

1. **Create a Database:**
   ```sql
   CREATE DATABASE hotel_db;
USE hotel_db;

CREATE TABLE reservations (
   reservation_id INT AUTO_INCREMENT PRIMARY KEY,
   guest_name VARCHAR(100),
   room_number INT,
   contact_number VARCHAR(15),
   reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

git clone https://github.com/GihanJeewantha/hotel-reservation-system.git
cd hotel-reservation-system

