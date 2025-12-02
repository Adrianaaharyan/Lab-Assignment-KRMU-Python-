# 📚 Library Inventory Manager
A simple Python Library Management System built using Object-Oriented Programming, JSON file handling, and logging.
# Overview
The Library Inventory Manager is a Python-based command-line application designed to manage a small library system. It allows users to add books, issue or return them, search the collection, and view all available books.
The program uses Object-Oriented Programming (OOP), JSON file storage, exception handling, and logging to create a reliable and user-friendly system. All library data is stored in catalog.json, and all actions are recorded in logs/app.log.
# 🚀 Features
1.Add new books
2.Issue & return books
3.Search by title or ISBN
4.View all books
5.Data stored in catalog.json
6.Logs stored in logs/app.log
7.Handles errors (missing/corrupted JSON, invalid input, Ctrl+C)
# 📁 Project Structure
main.py
library_manager/
    book.py
    inventory.py
data/
    catalog.json
logs/
    app.log
# 📘 Sample Menu Output
1. Add Book
2. Issue Book
3. Return Book
4. View All Books
5. Search Book
6. Exit
# How to Use:
. Add Book → Enter title, author, and ISBN to create a new book.
. Issue Book → Enter ISBN to mark a book as issued.
.Return Book → Enter ISBN to set a book's status back to available.
. Search Book → Search by title keyword or ISBN.
. View All Books → Displays all books with their current status.
. Exit → Safely close the program.
. All operations automatically update the JSON file and log actions for tracking
   

