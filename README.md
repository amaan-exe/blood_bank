# 🩸 Blood Bank Management System

## 📦 Overview
This is a GUI-based Blood Bank Management System developed in Python using Tkinter and SQLite. It allows users to manage blood donations, receivers, and inventory records with features like adding, updating, searching, and printing slips.

---

## 🖥️ Requirements

- Python 3.7 or later

### Required Libraries
- `tkinter` (built-in)
- `sqlite3` (built-in)
- `Pillow`
- `tkcalendar`

### To install dependencies:
```bash
pip install pillow tkcalendar
```

---

## 🚀 How to Run

1. Clone the repository or download the project folder.
2. Open a terminal in the project directory.
3. Run the main file:

```bash
python Blood Bank.py
```

---

## ✨ Features

- **Donor Module**
  - Add, update, delete donor details.
  - Validate input (mobile number, disease check, etc.)
  - Automatically updates blood inventory.

- **Receiver Module**
  - Add, update, delete receiver details.
  - Ensures available stock before allocation.
  - Automatically deducts from inventory.

- **Inventory Module**
  - View and export total available blood types.
  - Print stock summary.

- **Login/Register System**
  - Secure user login.
  - New user registration with recovery question.

- **Slip Generation**
  - Generates receipts for donations and withdrawals.
  - Automatically opens in Notepad for printing.

---

## 🗃️ Database Structure

- `donater`: Stores donor details
- `receiver`: Stores receiver details
- `total`: Tracks inventory per blood type
- `login`: User authentication records

Tables are automatically created on the first run.

---

## 📁 Output Files

- `fg.txt`: Receipt of donation/withdrawal.
- `filerecord.txt`: Export of blood inventory.

---

## 👨‍💻 Author

This project was built as part of a college-level software application for blood bank management.

---

## 📜 License

This project is free to use and modify for educational purposes.
