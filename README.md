# Airline-Reservation-java-console-
Java console based project  jdbc connectivity using Mysql
Airline Reservation System (Java + MySQL)
A console-based Airline Reservation System developed using Java (JDBC) and MySQL.
This project allows users to view flights, book tickets, view booking details, and cancel reservations through a simple command-line interface.
________________________________________
 Features
•	 Automatic Database & Table Creation
•	View Available Flights
•	Book Tickets
•	 View Booking Details
•	 Cancel Tickets
•	Seat Availability Auto-Update
•	Auto-generated Booking ID
________________________________________
 Technologies Used
•	 Java (JDK 8+)
•	MySQL
•	 JDBC (Java Database Connectivity)
•	 Console-Based Interface
•	 Developed using IDE (Eclipse / VS Code)
________________________________________
 Database Details
Database Name: airline_db
Port: 3308
Username: root
Password: root
Tables Created Automatically:
1. flights
Column	Type
flight_no	VARCHAR(10) (Primary Key)
source	VARCHAR(50)
destination	VARCHAR(50)
date	VARCHAR(20)
available_seats	INT
price	DOUBLE
2.bookings
Column	Type
booking_id	VARCHAR(20) (Primary Key)
passenger_name	VARCHAR(100)
age	INT
gender	VARCHAR(10)
flight_no	VARCHAR(10)
seats_booked	INT
total_amount	DOUBLE
________________________________________
Sample Flights Inserted Automatically
•	AI101 – Mumbai → Delhi
•	AI102 – Delhi → Bangalore
•	AI103 – Chennai → Mumbai
________________________________________
 Project Structure
connectivity/
 └── AirlineReservationSystem.java
________________________________________
 How to Run the Project
Step 1: Install MySQL
Ensure MySQL server is running on port 3308.
Step 2: Add MySQL JDBC Driver
Add MySQL Connector JAR file to your project build path.
Step 3: Run the Program
Run AirlineReservationSystem.java
The system will:
•	Create database automatically (if not exists)
•	Create required tables
•	Insert sample flights (if empty)
________________________________________
 Application Menu
1. View Flights
2. Book Ticket
3. View Booking
4. Cancel Ticket
5. Exit


