# Contact Book

A GUI-based contact management application built with Python, Tkinter and MySQL.

## Project Overview

This desktop app replaces manual contact records with a simple, organized interface. It supports full CRUD (create, read, update and delete) operations, and stores all contact data in a MySQL database.

## Features

- Add new contacts
- View saved contacts
- Update existing contacts
- Delete contacts
- Contact data stored securely in MySQL

## Tools Used

- Python
- Tkinter (GUI)
- MySQL

## Screenshots

![Contact Book main window](images/main_window.png)

## Database Setup

Create the database and table before running the app. Edit the columns to match the ones used in the code:

```sql
CREATE DATABASE contact_book;
USE contact_book;

CREATE TABLE contacts (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    phone VARCHAR(15),
    email VARCHAR(100)
);
```

## How to Run

1. Install Python and MySQL.
2. Install the connector: `pip install mysql-connector-python`
3. Create the database using the SQL above.
4. In the code, enter your own MySQL username and password (never upload your real password to GitHub).
5. Run the app: `python contact_book.py`

## Repository Files

| File | Description |
|---|---|
| `contact_Books.ipynb` | Application code |
| `README.md` | Project description |

## Author

Mayuri Nalage | nalagemayuri111@gmail.com
