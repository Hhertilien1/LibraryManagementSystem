**Library Management System (LMS)**
**Introduction**
The Library Management System (LMS) is a simple console-based application designed to manage a library's collection of books. This project aims to provide basic functionalities such as adding books from a file, removing books, listing all books, and checking books in and out. This version focuses on the core logic and functionality, with future phases planned to introduce a graphical user interface (GUI) and database integration.

**Purpose**
The primary purpose of this LMS is to facilitate basic library operations through a user-friendly console interface. It helps librarians and users manage the library's book inventory efficiently by providing functionalities to add, remove, list, check out, and check in books.

**Features**
1. Add Books from File: Load books into the library's collection from a text file. Each line in the file represents a book with a unique ID, title, and author.
2. Remove Books by ID or Title: Remove books from the library's collection using their ID or title.
3. List All Books: Display all books currently in the library's collection.
4. Check Out Books: Mark a book as checked out by its title.
5. Check In Books: Mark a book as available by its title.

**Functional Requirements**
Book Class: Represents a book with attributes such as ID, title, author, and availability status.
LibraryManager Class: Manages the collection of books with methods to add, remove, list, check out, and check in books.
LibraryApp Class: Contains the main method to run the application and interact with the user.

**How to Use**
Setup: Clone the repository and open the project in your IDE.
Create Sample Text File: Prepare a text file with book entries, formatted as ID, Title, Author. Example:
css
Copy code
1, To Kill a Mockingbird, Harper Lee
2, 1984, George Orwell
3, The Great Gatsby, F. Scott Fitzgerald
Run the Application: Execute the LibraryApp class. The program will prompt you to enter the file name to load books.
Follow Prompts: Interact with the application by following the prompts to add books, remove books, list books, check out, and check in books.
