# Library Management System

This is a simple library management system implemented in Java. It allows managing books in a library and users who can borrow and return books.

## Features

- Add new books to the library (fiction and non-fiction)
- Display available books in the library
- Users can borrow books
- Users can return borrowed books 
- Books are marked as unavailable when borrowed and available when returned

## Classes

The main classes are:

- **Book**: Represents a book with attributes like title, author, ISBN, availability
- **FictionBook**: Subclass of Book for fiction books
- **NonFictionBook**: Subclass of Book for non-fiction books
- **Library**: Manages lists of fiction and non-fiction books
- **User**: Users who can borrow and return books
- **LibraryManagement**: Main class with user interface

## Usage

The LibraryManagement class contains the main() method which has a menu-driven UI that allows:

- View available books
- Borrow a book (by ISBN) 
- Return a borrowed book (by ISBN)
- Add a new book
- Exit

Books are marked as unavailable when borrowed and back as available when returned.

## Running the code

Import the Librarymanagement.java file into an IDE like Eclipse or IntelliJ IDEA and run the main() method to start using the library management system.

## Enhancements

Some ways the library management system can be improved:

- Add a login system for users
- Track borrowing history of users  
- Impose limits on number of books users can borrow
- Search for books by title/author etc.
- Add book categories besides fiction/non-fiction