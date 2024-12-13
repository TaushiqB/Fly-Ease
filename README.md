# Fly-Ease
Developed a console-based Airlines Reservation System in C++ that allows users to book flight tickets, manage flight details, and track bookings. The system supports booking tickets for multiple flights, handles user input for name and ticket numbers, and updates flight information dynamically. The project also interacts with a MySQL database.

A C++ based Airlines Reservation System that allows users to manage flight details, book tickets, and modify or delete flight records. This system connects to a MySQL database for efficient data management and incorporates features like flight scheduling, ticket issuance, and real-time updates for flight status.

## Features

- **Flight Management**
  - Add, edit, and delete flight details such as flight number, name, departure and destination, time, and price.
  - Edit flight schedules, including leave and arrival times, availability status, and flight information.
  - View all flight details in a structured format.

- **Ticket Booking**
  - Book tickets with automatic ticket number generation.
  - Generate and issue unique tickets with flight number, ticket number, and passenger details.
  - Automatic flight assignment after every 25 tickets sold.
  
- **Flight Status Management**
  - Manage flight status (available/unavailable) and update arrival and departure times.
  - Enable real-time status updates for flights.

- **Database Management**
  - Use of **MySQL** to store and manage flight and ticket data.
  - CRUD operations for flight details using SQL queries.
  - Secure data handling with user-friendly input validation.

- **User Interaction**
  - Console-based user interface for ease of interaction.
  - Menu-driven system to navigate through different functionalities such as viewing flights, booking tickets, and updating flight schedules.

- **Exception Handling**
  - Includes robust exception handling for invalid input and database interaction issues, ensuring smooth operation.

## Technologies Used

- **C++**: Core programming language for implementing the system logic.
- **MySQL**: Database for storing flight and booking information.
- **C++ MySQL Connector**: To facilitate communication between the C++ application and MySQL database.
- **C++ Standard Library**: Used for managing system input, output, and string operations.

