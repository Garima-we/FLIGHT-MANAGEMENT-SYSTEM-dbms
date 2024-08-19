# Flight Management System

## Project Overview
The Flight Management System is a database-driven application designed to manage the operations of an airline or airport. The system provides comprehensive functionality for flight scheduling, passenger reservations, ticket bookings, and crew assignments.

## Key Features
- **Flight Scheduling:** Manage flight numbers, departure and arrival times, routes, and aircraft details.
- **Passenger Reservations:** Handle passenger information, seating arrangements, and booking details.
- **Ticket Bookings:** Facilitate ticket bookings and manage payment details securely.


## Technologies Used
- **MySQL:** Backend database for storing and managing all data related to flights, passengers, and crew.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/flight-management-system.git
    ```
2. Navigate to the project directory:
    ```bash
    cd flight-management-system
    ```
3. Import the MySQL database schema:
    ```sql
    mysql -u your-username -p your-database-name < database/schema.sql
    ```
4. Configure the database connection settings in the application.

## Usage
1. Start the application by running:
    ```bash
    python main.py
    ```
2. Use the interface to manage flight schedules, handle reservations, book tickets, and assign crew members.

