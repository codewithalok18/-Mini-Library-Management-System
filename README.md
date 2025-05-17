# Mini Library Management System (Java Console Application)

This is a simple console-based Mini Library Management System built using Java and object-oriented programming principles. It allows users to add books, view all books, issue books, and return books, with data persistence using file I/O.

---

## Features

- Add new books (ID, Title, Author)
- View all books with their availability status
- Issue a book by its ID (marks it unavailable)
- Return a book by its ID (marks it available)
- Exception handling for invalid inputs
- Issued books are stored separately in a text file

---

## Project Structure

MiniLibraryManagementSystem/
├── Book.java
├── Library.java
├── Main.java
├── books.dat # Auto-created file storing books data (binary)
├── issuedBooks.dat # Auto-created file storing issued books (text)
└── README.md
Sample Output
--- Mini Library Management ---
1. Add Book
2. View All Books
3. Issue Book
4. Return Book
0. Exit
Choose option: 1
Enter Book ID: 101
Enter Title: Java Basics
Enter Author: John Doe
Book added successfully.

--- Mini Library Management ---
1. Add Book
2. View All Books
3. Issue Book
4. Return Book
0. Exit
Choose option: 2
ID: 101 | Title: Java Basics | Author: John Doe | Available: Yes

--- Mini Library Management ---
1. Add Book
2. View All Books
3. Issue Book
4. Return Book
0. Exit
Choose option: 3
Enter Book ID to issue: 101
Book issued successfully.

--- Mini Library Management ---
1. Add Book
2. View All Books
3. Issue Book
4. Return Book
0. Exit
Choose option: 2
ID: 101 | Title: Java Basics | Author: John Doe | Available: No

--- Mini Library Management ---
1. Add Book
2. View All Books
3. Issue Book
4. Return Book
0. Exit
Choose option: 4
Enter Book ID to return: 101
Book returned successfully.
Author
codewithalok18
