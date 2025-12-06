# 🏪 Inventory Management System (Python + Tkinter)

A complete **Inventory Management System** built using **Python and Tkinter GUI** that helps manage Employees, Suppliers, Categories, Products, Billing, and Sales efficiently.

---

## 👨‍💻 Author
**Deepak Kumar Singh**

---

## 📌 Project Overview

This project is a **desktop-based ERP-style Inventory Management System** developed using:

- `tkinter` → Graphical User Interface (GUI)
- `PIL (Pillow)` → Image handling
- `datetime` → Date & time handling
- `sqlite3` → Local database
- `os` → File system operations
- `matplotlib` → Graphs (Employee module)
- `plotly` → Sales analytics

The system is divided into **8 interconnected Python scripts**:

### 📂 Project Files

1. `dashboard.py` – Main dashboard  
2. `employee.py` – Employee management  
3. `supplier.py` – Supplier management  
4. `product.py` – Product management  
5. `category.py` – Category management  
6. `sales.py` – Sales & analytics  
7. `create_db.py` – Database creation  
8. `billing.py` – Billing & invoice generation  

---

## 📊 Application Modules

### 🖥️ 1. Dashboard (`dashboard.py`)
- Central control panel
- Provides access to:
  - Employee
  - Supplier
  - Category
  - Product
  - Sales
- Shows live updates of system data

---

### 👨‍💼 2. Employee (`employee.py`)
- Add, update, delete employee data
- Search by:
  - Name
  - Email
  - Contact

---

### 🚚 3. Supplier (`supplier.py`)
- Manage supplier details
- Search supplier using **Invoice Number**

---

### 📦 4. Product (`product.py`)
- Product addition & availability tracking
- Search product by:
  - Name
  - Category
  - Supplier

---

### 🗂️ 5. Category (`category.py`)
- Add & delete product categories  
- Example:
  > Product: iPhone → Category: Mobile

---

### 💰 6. Sales (`sales.py`)
- View stored bills
- Search using **Invoice Number**
- Sales analysis using graphs

---

### 🗄️ 7. Database (`create_db.py`)
- Creates all required database tables
- ⚠️ **Must be executed before running the system**

---

### 🧾 8. Billing (`billing.py`)
- Complete billing system with:
  - Customer details
  - Product cart
  - Discount calculation
  - GST
  - Final payable amount
- Built-in **calculator**
- Automatically saves bills in the `bill` folder

---

## ✅ How to Run the Project

### ▶️ Step-by-Step Execution

1. ✅ Run the database file first:
   ```bash
   python create_db.py
