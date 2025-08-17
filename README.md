# 📇 Contact Management System

A simple **command-line application** built with **Node.js** that lets you manage contacts — add, delete, view, and search.

---

## 🚀 Features

- ➕ **Add Contacts** (Name + Email)
- ❌ **Delete Contacts** (by ID)
- 📜 **View All Contacts** (with clean formatting)
- 🔍 **Search Contacts** (case-insensitive name matching)
- 🚪 **Exit Program** gracefully

---

## 🛠️ Tech Stack

- **Node.js** (JavaScript runtime)
- **prompt-sync** (for CLI user input)

---

## 📂 Project Structure

contact-management/  
│── index.js # Main application file  
│── package.json # Node.js dependencies  
│── README.md # Project documentation

---

## ⚙️ Installation & Setup

1. Clone the repository  
   git clone https://github.com/your-username/contact-management.git  
   cd contact-management

2. Install dependencies  
   npm install prompt-sync

3. Run the app  
   node index.js

---

## 🖥️ Usage

When you run the app, you’ll see:

Contact Management System

---

1. Add a Contact
2. Delete a Contact
3. View Contacts
4. Search Contacts
5. Exit

👉 Enter a number (1-5) to perform an operation.

---

## 🔍 Example

### Adding a Contact

Enter an operation (1-5): 1  
Name: Alice  
Email: alice@example.com  
Added!

### Viewing Contacts

Enter an operation (1-5): 3  
###########  
Name: Alice  
Email: alice@example.com

---

## 📌 Future Improvements

- Save contacts to a **JSON/Database file** (persistent storage)
- Add **phone number support**
- Export contacts to **CSV**
- Improve **search (regex / multiple fields)**

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

---

## 📜 License

This project is licensed under the **MIT License** – free to use, modify, and distribute.
