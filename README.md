## 📒 Contact Book Management System

### 📘 Overview

This project is a **Python-based Contact Book Application** that allows users to **add, view, search, update, and delete contacts** directly through a simple command-line interface (CLI).
It helps manage personal or professional contacts efficiently without relying on external tools or databases.

---

### 🧩 Project Structure

**1. contact.py**
Defines the `Contact` class, which represents an individual contact.
Each contact stores key information such as **name**, **phone number**, and **email**.

**2. contact_book.py**
Contains the `ContactBook` class that manages multiple `Contact` objects.
It includes methods to:

* Add a new contact
* Display all saved contacts
* Search for a specific contact
* Update contact details
* Delete a contact

**3. main.py**
Acts as the entry point of the program.
It provides a **menu-driven interface** for users to interact with the contact book through the terminal.

---

### 🧠 Key Features

* ➕ **Add Contact** – Save new contact details including name, phone number, and email.
* 📖 **Display All Contacts** – View all saved contacts neatly formatted.
* 🔍 **Search Contact** – Quickly find a contact by name.
* ✏️ **Update Contact** – Modify existing contact details easily.
* 🗑️ **Delete Contact** – Remove a contact from the list permanently.
* 🚪 **Exit Option** – Gracefully close the program.

---

### ⚙️ Technologies Used

* **Programming Language:** Python
* **Concepts Used:**

  * Object-Oriented Programming (OOP)
  * Classes and Objects
  * Functions and User Input Handling
  * File Importing and Modular Programming

---

### 🧩 Code Flow

1. The program starts by displaying a **main menu** with available operations.
2. The user selects an option (Add, Search, Update, etc.).
3. Corresponding functions handle each operation.
4. The menu repeats until the user chooses to exit.

---

### 💡 Learning Outcomes

* Understand how to structure Python programs using multiple files.
* Learn to apply **OOP principles** in real-world applications.
* Improve skills in **user input handling** and **data management**.
* Build a fully functional **menu-driven console app**.

---

### 🚀 Future Enhancements

* Add data persistence using **CSV, JSON, or SQLite**.
* Introduce **contact grouping** (e.g., Family, Work, Friends).
* Add **validation** for phone numbers and email formats.
* Implement a **GUI version** using Tkinter or PyQt.
