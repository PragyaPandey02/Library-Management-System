# Library Management System

A Java-based Library Management System developed to simplify the management of library records, transactions, and user interactions. This system includes features for book management, issuing and returning books, and handling user data, with an emphasis on simplicity, ease of use, and operational efficiency.

## Features

### Library Operations:
- Calculate Fines: Automatically calculate fines for overdue books.
- Check Availability: Verify book availability in real-time.
- Track Overdues: Monitor and track overdue book returns.
- Issue/Return Books: Facilitate the issuing and returning of books.

### User Management:
- Admin Functions: Add, view, and delete librarian records.
- Librarian Functions: Add, view, and delete book records.
- Persistent Storage: Manage user data with reliable storage using CSV files.

### File Handling:
- Data Persistence: Use file handling techniques to store and manage user data, ensuring consistent and reliable data persistence.

### Command-Line Interface:
- User-Friendly Interface:A simple command-line interface for adding, deleting, modifying, and displaying employee records, making data management straightforward and accessible.

## How It Works

1. Login: Admin or Librarian logs in to access the system.
2. Book Management: Admin or Librarian can add, view, or delete books from the system.
3. Issue and Return: Librarians can issue books to users and handle their returns.
4. User Data Management: The system loads and saves user data to a CSV file, ensuring persistent record-keeping.
5. Logout: After completing operations, Admin or Librarian logs out, and the system saves all user data.

## Usage

To run the Library Management System:

1. Compile the Java Files: Run `javac LibraryManagementSystem.java` to compile the files.
2. Run the Application: Execute `java LibraryManagementSystem` to start the system.
