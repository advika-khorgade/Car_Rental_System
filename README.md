# Car_Rental_System
# WanderWheel Car Rental System

WanderWheel is a comprehensive car rental system designed to simplify the process of renting cars for users while providing administrators with tools to manage cars, drivers, and bookings effectively. Built using Java and MySQL, it ensures smooth and secure operations for both end-users and administrators.

## Features

### For Users:
- **Registration & Login**: Create a new account or securely log in to the system.
- **Car Browsing**: View all available cars with details such as model, seating capacity, rental rates, and availability status.
- **Booking System**: Book cars for specific dates with automated cost calculation based on rental duration.
- **Rental History**: Track ongoing and completed rentals directly from your user profile.

### For Administrators:
- **Car Management**: Add, update, or delete car listings with relevant details like rental rate, availability, and assigned drivers.
- **Driver Management**: Assign drivers to cars and maintain driver details (name, license, and contact information).
- **Booking Insights**: View all bookings and generate reports on user spending, popular car models, and rental trends.
- **Data Management**: Ensure consistency with triggers and constraints, while securely handling user and booking data.

## Database Schema

The database includes the following tables:
1. **Users**: Stores user details like username, password, email, and phone number.
2. **Drivers**: Maintains driver information, including unique license numbers and contact details.
3. **Cars**: Contains car details such as model, seating capacity, rental rate, availability, and assigned driver.
4. **Bookings**: Records all active bookings with user, car, and rental information.
5. **BookingHistory**: Archives completed bookings for reporting and future reference.

## Technology Stack
- **Frontend**: Java (with user-friendly CLI for interaction).
- **Backend**: MySQL for structured data storage and retrieval.
- **Database Connectivity**: JDBC for seamless interaction between Java and MySQL.
- **Triggers & Stored Functions**: Used for automated operations like cost calculation and archiving booking history.

## How to Run

1. **Set up the Database**:
   - Import the `wanderwheel.sql` file into your MySQL server to create the required tables and triggers.
   - Update the connection details (username, password, and database name) in the Java code.

2. **Run the Application**:
   - Compile and run the `CarRentalApp.java` file using a Java compiler.
   - Follow the CLI prompts to log in, view cars, or manage bookings.

3. **Admin Access**:
   - Use the admin module to add or update cars, assign drivers, and monitor bookings.

## Key Highlights

- **Secure**: Passwords are encrypted, and sensitive operations are restricted to authorized users.
- **Efficient**: Real-time availability updates and cost calculations enhance the booking experience.
- **Scalable**: Modular architecture allows for easy updates and additional features in the future.

## Contribution

Contributions are welcome! If you’d like to improve the system or add new features, feel free to fork the repository and submit a pull request.

