Library Management System

A beginner-friendly Python program that tracks which books members have borrowed, using classes, lists, loops, and file handling.

![Python](https://img.shields.io/badge/python-3.x-blue)
![Status](https://img.shields.io/badge/status-learning%20project-green)

## What it does

- Shows the list of books available in the library
- Checks whether a book exists and whether it is already taken
- Collects member details (name, address, phone number) only when the book is available
- Saves every borrow record to a text file
- Lets you keep adding members until you type something other than `yes`

## Demo

```
The list of books in the library:
1 To Kill a Mockingbird
2 1984
3 The Great Gatsby
...

Enter the BOOK Title: The Hobbit
Book is Available
Enter member name: Ram
Enter address of member: Kathmandu
Enter phone no of member: 98XXXXXXXX
Enter the author name: J.R.R. Tolkien
Enter the book id: 5

Enter the BOOK Title: The Hobbit
Not Available, already taken
```

> Replace this with a real run of your own program (copy the output from your terminal).

## How to run

1. Install [Python 3](https://www.python.org/downloads/)
2. Download or clone this repository:
   ```
   git clone https://github.com/YOUR-USERNAME/library-management-system.git
   ```
3. Go into the folder and run:
   ```
   python library_management_system.py
   ```

No extra libraries are needed.

## How it works

| Part | Purpose |
|---|---|
| `famous_books` list | The books the library owns |
| `Book` class | Stores title, author, and book id |
| `Member` class | Stores name, address, and phone number |
| `is_taken()` function | Reads the file to see if a book was already borrowed |
| `libary.txt` | Created automatically; stores all borrow records |

## Concepts practiced

- Classes and objects
- Lists and loops
- Functions
- `if / elif / else` decisions
- Reading and writing files
- Basic error handling (`FileNotFoundError`)

## Roadmap

- [x] Check availability before borrowing
- [ ] Use `__init__` in the classes
- [ ] Return book option
- [ ] Validate the phone number
- [ ] Save records as CSV or JSON
- [ ] Add inheritance (`Person` parent class with `Member` and `Librarian`)

## About

Built while learning Python and OOP, with AI help for debugging and code review.

Made by **piratwwave32**, Hetauda, Nepal. Feedback and suggestions are welcome: open an issue or leave a comment.
