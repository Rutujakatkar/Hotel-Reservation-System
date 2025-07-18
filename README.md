# 🏨 Hotel Reservation System (Java + JDBC)

A Java-based Hotel Reservation System that allows hotel staff to manage room bookings efficiently. Built using **JDBC** for database operations, the system performs core reservation tasks including booking, updating, deleting, and retrieving reservations.

## 📌 Features

- 🛏️ **Reserve a Room**: Add a new reservation with guest details and assigned room
- 🔍 **Get Room Number**: Retrieve the room number for a specific reservation ID or guest
- ✏️ **Update Reservation**: Modify existing guest or room information
- ❌ **Delete Reservation**: Cancel a reservation and free up the room
- 📃 **View All Reservations**: Display a list of all booked rooms with guest details

## 🛠️ Technologies Used

- **Java (Core & JDBC)**
- **MySQL / Any RDBMS**
- **IDE**: Apache NetBeans IDE 17

## 🧠 Project Highlights

- Database connection handled through JDBC
- All operations follow structured SQL execution via DAO classes
- Code designed with separation of concern: model, dao, service, and controller layers
