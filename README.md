<div align="center">

# 🛍️ WeCare Inventory Management System

### A Python-Based Inventory, Billing & Stock Management Application

*A command-line inventory management system developed in Python for managing products, processing customer sales, handling supplier restocking, and generating invoices.*

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![CLI](https://img.shields.io/badge/Interface-Command%20Line-success?style=for-the-badge)
![File Handling](https://img.shields.io/badge/Data-Text%20Files-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 📖 Overview

**WeCare Inventory Management System** is a Python-based command-line application designed to simplify inventory management for retail businesses.

The system enables administrators to manage product inventory, process customer purchases, restock products from suppliers, generate invoices, and maintain inventory records using text files.

The project demonstrates the practical implementation of Python fundamentals including modular programming, file handling, exception handling, loops, conditional statements, and data manipulation.

---

# ✨ Features

## 📦 Product Inventory Management

Manage all products available in the inventory.

Features include:

- View available products
- Display product information
- Track stock quantity
- Monitor selling price
- Country of origin
- Brand information

---

## 🛒 Product Sales

Process customer purchases efficiently.

Features:

- Select products
- Purchase multiple items
- Automatic stock deduction
- Quantity validation
- Customer information collection
- Purchase history

---

## 🚚 Product Restocking

Restock products directly from suppliers.

Capabilities include:

- Supplier information
- Product selection
- Quantity updates
- Automatic inventory update
- Purchase bill generation

---

## ➕ Add New Products

Add completely new products into the inventory.

Information stored:

- Product Name
- Brand
- Cost Price
- Selling Price
- Quantity
- Country

---

## ❌ Remove Products

Remove products from the inventory whenever necessary.

Useful for:

- Discontinued products
- Outdated stock
- Inventory cleanup

---

## 🧾 Invoice Generation

Automatically generates customer invoices after every successful purchase.

Invoice contains:

- Customer Name
- Contact Number
- Purchased Products
- Quantity
- Free Items
- Price
- Total Cost
- Purchase Date

---

## 💰 Automatic Pricing

The application automatically calculates selling prices using the business rule.

```
Selling Price = Cost Price × 3
```

---

## 🎁 Buy 3 Get 1 Free Offer

A promotional offer is automatically applied.

Example:

```
Buy 3 Items
Receive 1 Item Free
```

The inventory is updated accordingly.

---

## 🧮 VAT Support

The application calculates applicable VAT during supplier restocking transactions.

---

## 💾 File Handling

Inventory data is permanently stored using text files.

Operations include:

- Read inventory
- Update inventory
- Save changes
- Generate invoices

---

## ⚠ Error Handling

The application prevents invalid input by validating:

- Invalid product numbers
- Invalid quantities
- Insufficient stock
- Incorrect menu selections
- Invalid numeric input

---

# 🛠 Technology Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Programming Language |
| Text Files | Data Storage |
| Modular Programming | Code Organization |
| Exception Handling | Error Handling |
| File Handling | Persistent Storage |

---

# 📂 Project Structure

```text
WeCare-Inventory-Management-System
│
├── main.py
├── operations.py
├── read.py
├── write.py
├── data.txt
├── invoices/
├── README.md
└── assets/
```

---

# 🚀 Getting Started

## Prerequisites

- Python 3.x
- VS Code (Recommended)

---

## Clone the Repository

```bash
git clone https://github.com/yourusername/WeCare-Inventory-Management-System.git
```

---

## Navigate to the Project

```bash
cd WeCare-Inventory-Management-System
```

---

## Run the Application

```bash
python main.py
```

---

# 🖥 Application Menu

```
==============================
      WeCare Store Menu
==============================

1. Sell Product

2. Restock Product

3. Add New Product

4. Remove Product

5. Exit

==============================
```

---

# 📸 Screenshots

Create an **assets/screenshots** folder and include images such as:

```
assets/
└── screenshots/
    ├── main-menu.png
    ├── product-list.png
    ├── sell-product.png
    ├── restock.png
    ├── invoice.png
    ├── add-product.png
```

---

# 📊 Workflow

```
Start
   │
   ▼
Load Inventory
   │
   ▼
Display Menu
   │
   ├── Sell Product
   ├── Restock Product
   ├── Add Product
   ├── Remove Product
   └── Exit
   │
   ▼
Update Inventory
   │
   ▼
Generate Invoice
   │
   ▼
Save Data
```

---

# 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

- Python Programming
- Modular Programming
- File Handling
- Exception Handling
- Inventory Management Logic
- Billing System Development
- Input Validation
- Business Logic Implementation

---

# 🔮 Future Improvements

Potential future enhancements include:

- Graphical User Interface (Tkinter/PyQt)
- SQLite/MySQL Database Integration
- Barcode Scanner Support
- User Authentication
- Admin Dashboard
- Sales Analytics
- PDF Invoice Generation
- Customer Management
- Product Categories
- Search & Filter Functionality
- Cloud Data Backup

---

# 🤝 Contributing

Contributions are welcome!

To contribute:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push your branch
5. Open a Pull Request

Bug reports and feature suggestions are always appreciated.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Yogesh Pant**

🎓 BSc (Hons) Computing  
🏛️ Islington College, Kathmandu  
🎓 London Metropolitan University

GitHub: **https://github.com/yogeshpan1**

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

Built with ❤️ using Python

</div>
