# 🍽️ Restaurant Management System (C)

A console-based Restaurant Management System developed in **C**, using **Doubly Linked Lists** to manage menu items, customer orders, billing, and total sales efficiently.

---

## 🚀 Features

### 👨‍💼 Admin Section
- View total sales summary
- Add new food items to the menu
- Delete existing food items
- Display current order/menu list

### 👨‍🍳 Customer Section
- View available food menu
- Place food orders with quantity
- View ordered items
- Delete items from order
- Generate final bill with total price

---

## 🧠 Core Concepts Used
- Doubly Linked Lists
- Dynamic Memory Allocation (`malloc`, `free`)
- Structures in C
- Menu-driven program design
- Pointer manipulation
- Modular programming

---

## 🏗️ Data Structures
Each food item is stored as a node containing:
- Food ID
- Food Name
- Quantity
- Price
- Previous & Next pointers

> This allows efficient insertion, deletion, and traversal.

---

## ⚙️ How to Run

### Prerequisites
- GCC compiler
- Any C-compatible IDE or terminal

### Steps
```bash
gcc restaurant.c -o restaurant
./restaurant
```

---

## 📋 Default Menu Items
- Hot and Sour Soup
- Manchow Soup
- Manchurian Noodles
- Fried Rice
- Hakka Noodles
> (Admin can add/delete items dynamically)

---

## 📌 Future Enhancements
- File handling for persistent data storage
- User authentication for admin
- GST/Tax calculation
- Order history tracking
---
