✈️ Airline Management System

This project is a Java-based Airline Management System built using NetBeans IDE and MySQL Workbench. It allows users to manage flight schedules, customer bookings, ticketing, and other core functionalities of airline operations.


📁 Project Structure

AirlineManagementSystem/

│

├── src/                          # Java source files

│   └── airlinemanagementsystem   # Application packages and classes

│   

├── Database.txt                 # SQL script to set up the database

├── README.md                     # Project documentation

└── .gitignore



⚙️ Setup Instructions
1. Clone the Repository

git clone https://github.com/Vedantt31/Airline-Management-System.git

cd airline-management-system

2. Import Project into NetBeans
Open NetBeans IDE

Click on File > Open Project
Navigate to the cloned directory and open the project

3. Set Up the Database
Open MySQL Workbench
Run the script in Database.txt to create the necessary database and tables

Note: Modify the database connection details in the Java source code (e.g., DBConnection.java) to match your MySQL credentials.

String url = "jdbc:mysql://localhost:3306/airlinemanagementsystem";
String user = "root";
String password = "yourpassword";

📦 Dependencies:

Java JDK 8+

NetBeans IDE

MySQL Workbench

MySQL JDBC Driver

jcalendar-tz-1.3.3-4.jar

rs2xml.jar


🚀 Features

Show Boarding Passes

Book, cancel, and view tickets

Secure login system


❗ Notes
Ensure your MySQL service is running before launching the application.

Keep the database connection configurations updated.

Make sure all .jar files (like JDBC drivers) are added to the project libraries.

📬 Contact

For questions or support, feel free to contact: vedanttomar31@gmail.com
