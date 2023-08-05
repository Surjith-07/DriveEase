# DriveEase
    The Offline Car Rental System is a Java-based application that facilitates car rental
    management in an offline environment. This system uses Java Database Connectivity (JDBC)
    to interact with a MySQL database for storing and retrieving car rental and users information.

# Features
    -> Car registration and details management

    -> Customer registration and details management

    -> Booking and rental management

    -> Invoicing and payment tracking

# Requirements
    -> Java Development Kit (JDK) 8 or higher

    -> MySQL Server (Installed and running locally or remotely)

    -> MySQL Connector/J JDBC driver (Included in the project's lib directory)

    -> IDE (Eclipse, IntelliJ, or any Java IDE of your choice)

# Setting up the Database
    -> Create a new database in MySQL, e.x, "car_rental_db".

    -> Execute the SQL script "car_rental_db.sql" located in the "sql" directory to create the necessary tables and initial data.

# Configuring the Database Connection
    -> private static final String DB_URL = "jdbc:mysql://your_database_host:port/car_rental_db";

    -> private static final String DB_USERNAME = "your_mysql_username";

    -> private static final String DB_PASSWORD = "your_mysql_password";

# Running the Application
    -> import the project into your Java IDE.

    -> Ensure that the MySQL Server is running and the database is set up as described above.

    -> Build the project and run the "Main.java" file to start the car rental application.

# Usage
    -> Upon running the application, the main menu will appear.

    -> Use the provided options to navigate through the system's functionalities (car management, customer management, booking, etc.).

    -> Follow the prompts and input instructions to add, update, or delete car and customer details, make bookings, generate invoices, and process payments.

    -> All data will be stored and retrieved from the MySQL database in real-time.
