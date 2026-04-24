# Sari-Sari-Store-Small-System
Small inventory and sales system for a sari-sari store.

# 🏪 Sari-Sari Store Management System (Python Console App)

A simple Python-based console application that simulates a sari-sari store system with ordering, cart management, and payment via GCash.

Built using only Python and Visual Studio Code for educational purposes.

---

## 📌 Features

### 🛒 Ordering System
- View available products
- Add items to cart
- Specify quantity per item

### 🧺 Cart Management
- View cart items
- Delete items from cart
- Auto-update total price

### 💰 Payment System
- Displays total amount to be paid
- Simulated GCash payment method
- Shows GCash number for payment
- Accepts reference number input
- Confirms payment success

### 🧾 Receipt System
- Automatically generates a receipt file (`resiboo.txt`)
- Stores item name, quantity, price, and subtotal

### 🎨 Console UI
- Colored terminal interface
- Simple menu navigation

---

## 💳 Payment Method

This system uses a **simulated GCash payment process**:

- After ordering, the system shows:
  - Total amount to pay
  - GCash number: `9999999999`
- User inputs a reference number
- System confirms payment completion

> ⚠️ Note: This is a simulation only (no real API integration).

---

## 🛠️ Technologies Used

- Python 3
- Visual Studio Code (VS Code)
- File handling (TXT-based receipt storage)
- Console/terminal UI

---

## 🚀 How to Run

1. Open the project in VS Code

2. Open terminal

3. Run the program:

```bash
python main.py

