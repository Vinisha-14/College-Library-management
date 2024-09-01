# Library Management System

This project is a C++ console-based **Library Management System** that simulates the operations of a basic library. The system allows library staff to perform tasks such as listing books, adding new books, removing books, issuing books to students, and viewing the history of issued books for a particular student.

## Features

1. **Books List**: Displays a list of all books available in the library along with details like Book ID, Name, Author, Published Year, and Status (Issued/Not Issued).

2. **Add Books**: Allows users to add new books to the library by providing details such as Book ID, Name, Author, and Published Year.

3. **Remove Books**: Users can remove books either by specifying the Book ID or the Book Name.

4. **Search Books**: Users can search for books by their name and view the details of matching books.

5. **Issue Books**: Books can be issued to students by specifying their Roll Number and the Book Name. The system checks if the book is already issued and updates its status.

6. **Student Book History**: Displays the list of books issued to a particular student by specifying the student's Roll Number.

## Classes

### 1. **Book**
Represents a book in the library. Each book has the following attributes:
- `bookid`: The unique ID of the book.
- `bookname`: The name of the book.
- `bookauthor`: The author of the book.
- `publishedyear`: The year the book was published.
- `issued`: Status of whether the book is issued or not.

### 2. **Student**
Represents a student in the library system. Each student has the following attributes:
- `name`: The student's name.
- `rollno`: The student's roll number.
- `issuebook`: A list of books issued to the student.

### 3. **Library**
Represents the library system itself and handles the operations related to books and students. The following operations are supported:
- Displaying all books.
- Adding new books to the library.
- Removing books from the library by ID or Name.
- Searching for books by name.
- Issuing books to students.
- Viewing the book history for a particular student.

## How to Use

1. **Run the Program**: Compile and run the program in any C++ compiler.

2. **Main Menu**: Once the program is running, a menu will be displayed allowing you to choose different operations. Simply enter the corresponding number to choose an option.

    ```plaintext
    LIBRARY MANAGEMENT SYSTEM
    1. BOOKS LIST
    2. ADD BOOKS
    3. REMOVE BOOKS
    4. SEARCH BOOKS
    5. ISSUE BOOKS
    6. STUDENT BOOK HISTORY
    7. EXIT
    ```

3. **Operations**:
   - **Books List**: Lists all the books available in the library.
   - **Add Books**: Add new books to the library. You will be prompted to enter details such as Book ID, Name, Author, and Published Year.
   - **Remove Books**: Remove books either by entering their ID or Name.
   - **Search Books**: Search for a book by entering its name.
   - **Issue Books**: Issue books to a student. You will be prompted to enter the student's roll number and the book's name.
   - **Student Book History**: View the list of books issued to a specific student by entering their roll number.

4. **Exit**: Choose option `7` to exit the program.

## Example Usage

```plaintext
LIBRARY MANAGEMENT SYSTEM
1. BOOKS LIST
2. ADD BOOKS
3. REMOVE BOOKS
4. SEARCH BOOKS
5. ISSUE BOOKS
6. STUDENT BOOK HISTORY
7. EXIT
Enter your choice: 1
--------------------------------------
Book ID : 1056
Book Name : The Silent Echo
Author of the Book : Rachel Adams
Published Year : 2012
Book Status : NOT ISSUED
--------------------------------------
