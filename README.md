💸 BudgetMate – Expense Tracker System

BudgetMate is a desktop-based expense tracking application developed in Java Swing with MySQL as the database.
It helps users record, categorize, and analyze their income and expenses efficiently.
With an easy-to-use interface and powerful analytics, BudgetMate makes personal finance management simple and effective.

🚀 Features

User Authentication – Secure login and registration for multiple users.

Income & Expense Management – Add, edit, delete, and search transactions.

Category Management – Create, update, and delete categories with custom names and colors.

Transaction Filtering & Search – Filter transactions by date, category, or keywords.

Year-wise Analytics – Visual representation of income and expenses using bar charts.

Customizable Themes – FlatLaf-based modern UI themes.

Database Integration – MySQL for reliable data storage.

🛠️ Technologies Used

Java (Swing for UI)

MySQL (Database)

JDBC (Database Connectivity)

JFreeChart (Data Visualization)

FlatLaf (Custom UI Themes)

📂 Project Structure
BudgetMate-Expense-Tracker-System/
│
├── src/                  # Java source code
├── database/             # SQL scripts for database setup
├── lib/                  # Required JAR dependencies
├── assets/               # UI assets and icons
├── README.md              # Project documentation
└── LICENSE                # License file

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/aarya1210/BudgetMate-Expense-Tracker-System.git
cd BudgetMate-Expense-Tracker-System


Set up the database

Import the SQL file from the database/ folder into MySQL.

Update database credentials in the Java code (usually in DBConnection.java).

Add dependencies

Ensure required JAR files (JFreeChart, FlatLaf, MySQL Connector) are in the lib/ folder and added to the project.

Run the application

Compile and run the Main.java file.
