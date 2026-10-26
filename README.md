# file_Operator
Personal Journal Manager

(1)Project: File Operator

#A Python-based Personal Journal Manager that allows users to maintain journal entries using text file handling. The project demonstrates Object-Oriented Programming (OOP), file handling modes, exception handling, and a menu-driven user interface.

~Features

1.  Add a new journal entry

2.  Automatically save the entry with a timestamp

3.  Store journal entries in journal.txt

4.  View all saved journal entries

5.  Search entries using a keyword or date

6.  Delete all journal entries after confirmation

7.  Handle missing files and permission errors

8.  Demonstrate Python file modes: r, w, a, and x

9.  Menu-driven console interface

10. Exit the application safely

11. Technologies Used

Python 3

File Handling

Object-Oriented Programming (OOP)

Exception Handling

Project Structure

Personal-Journal-Manager/
├── personal_journal_manager.py
└── README.md

journal.txt is created automatically when the first journal entry is added. It contains journal data and does not need to be uploaded to GitHub.

How to Run

Install Python 3.

Open the project folder.

Run:

python personal_journal_manager.py

You can also run the code in Jupyter Notebook.

Main Menu

1. Add a New Entry
2. View All Entries
3. Search for an Entry
4. Delete All Entries
5. Exit

Features in Detail

1. Add a New Entry

The user enters a journal entry. The program saves it in journal.txt with the current date and time.

Example:

[2026-08-22 17:20:10]
Today I learned Python file handling.

2. View All Entries

The program reads journal.txt and displays all saved entries. If the file does not exist, a clear error message is shown.

3. Search for an Entry

The user can search the journal using a keyword or date.

Example:

Enter a keyword or date to search: Python

4. Delete All Entries

The program asks for confirmation before deleting the journal file.

Are you sure you want to delete all entries? (yes/no):

5. Exit

The user can safely exit the application from the main menu.

File Handling Modes

Mode

Purpose

r

Read data from a file

w

Write data and overwrite existing content

a

Append new data to existing content

x

Create a new file

OOP Structure

The project uses a JournalManager class.

Important methods include:

add_entry() - adds a new journal entry

view_entries() - reads and displays entries

search_entry() - searches for a keyword or date

delete_all_entries() - deletes all journal entries

demonstrate_file_modes() - demonstrates r, w, a, and x

The class object is created using:

manager = JournalManager()

Exception Handling

The program handles common file-related errors such as:

FileNotFoundError

PermissionError

FileExistsError

OSError

This helps prevent the program from crashing during common file operations.

Learning Objectives

This project demonstrates:

Classes and objects in Python

Instance methods

Reading and writing text files

File handling modes

Timestamps

Keyword/date searching

File deletion

Exception handling

Menu-driven programming

Assumptions

The application operates on text files.

Journal entries are stored in journal.txt.

The journal file is created automatically when the first entry is added.

Confirmation is required before deleting all entries.

The application is designed for a local console environment.

Author
Laxmankumar Prajapati
Personal Journal Manager - Python File handling
