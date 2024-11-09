
# Car Rental System

A car rental system built using Java and SQL. This project provides the basic features needed for a car rental website, including customer registration, car availability checking, booking, and payment processing. The system allows customers to easily rent cars online.

## Features

- **Customer Registration and Login**: Allows customers to create an account, log in, and manage their profiles.
- **Car Availability**: Customers can view available cars, their prices, and details.
- **Car Booking**: Users can rent cars by selecting rental dates and confirming the booking.
- **Payment Processing**: Basic payment functionality for rental booking.
- **Admin Panel**: Admin users can manage car inventory, customer accounts, and bookings.
- **SQL Database**: Used to store car, customer, and booking information.

## Technologies Used

- **Java**: Main programming language used to develop the application.
- **SQL**: Relational database for storing user, car, and rental data.
- **JDBC (Java Database Connectivity)**: Used for connecting the Java application to the SQL database.
- **Swing (Optional)**: For building a graphical user interface (GUI) for the app (if applicable).
- **MySQL**: Database used for storing records of customers, cars, and bookings.

## Prerequisites

- **Java Development Kit (JDK)**: Version 8 or above.
- **MySQL**: Installed on your machine to manage the database.
- **IDE (Optional)**: Any Java IDE like IntelliJ IDEA, Eclipse, or NetBeans.

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/car-rental-system.git
```

### 2. Set up the Database

1. Install MySQL and set up a database called `car_rental_system`.
2. Create tables for `customers`, `cars`, `bookings`, and `payments` in your SQL database. You can use the provided SQL scripts to create the necessary tables.
3. Update the **Database Connection** details in the `DBConnection.java` (or similar) file with your MySQL username, password, and database name.

Example connection setup in `DBConnection.java`:
```java
String url = "jdbc:mysql://localhost:3306/car_rental_system";
String user = "root";
String password = "your_password";
```

### 3. Build the Project

If you're using an IDE like IntelliJ IDEA or Eclipse:

1. Open the project in your chosen IDE.
2. Make sure that your MySQL database is running and accessible.
3. Compile and run the Java application. The program will connect to the database and allow you to interact with the car rental system.

### 4. Run the Application

1. Start the application by running the main class (e.g., `CarRentalSystem.java` or `Main.java`).
2. The app should prompt you to either register as a new user or log in with an existing account.
3. Once logged in, you can check available cars, make a booking, and view booking details.

## Contributing

Feel free to contribute to this project by:

- **Reporting issues**: If you encounter any bugs or have suggestions, please open an issue on GitHub.
- **Submitting pull requests**: Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.

