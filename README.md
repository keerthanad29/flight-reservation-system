<div align="center">

# ✈️ Flight Reservation System

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Console App](https://img.shields.io/badge/Console-Application-333333?style=for-the-badge&logo=windowsterminal&logoColor=white)](https://python.org)
[![OOP](https://img.shields.io/badge/OOP-Based-FF6B35?style=for-the-badge&logo=python&logoColor=white)](https://python.org)

> **A role-based flight booking system built entirely in Python.**
> Supports Passenger and Cashier roles with a full booking status workflow.

</div>

---

## 📌 Project Overview

A console-based Flight Reservation System that simulates a real-world ticket booking workflow. Users can sign up as **Passengers** to browse and book flights, while **Cashiers** manage and approve bookings — demonstrating role-based access control and state management in Python.

---

## 🎯 Project Highlights

| What | Detail |
|------|--------|
| 🐍 Language | Python 3 |
| 🖥️ Type | Console-based Application |
| 👥 Roles | Passenger + Cashier |
| 🔄 Workflow | Pending → Approved → Issued |
| 🔐 Auth | User authentication (sign up / log in / log out) |

---

## 🗂️ Project Structure

```
flight-reservation-system/
│
├── flight_reservation_system.py   # Main application — full booking system
├── output.py                      # Sample output / demo run
└── README.md
```

---

## 👥 Features by Role

**🧳 Passenger**
- Sign Up — create a new account
- Log In / Log Out
- Check flight availability and fares
- Book tickets
- View booking status

**🪙 Cashier**
- View all pending bookings
- Approve bookings
- Issue tickets to passengers

---

## 🔄 Booking Status Workflow

```
Passenger Books  →  [PENDING]  →  Cashier Approves  →  [APPROVED]  →  Cashier Issues  →  [ISSUED]
```

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/keerthanad29/flight-reservation-system.git
cd flight-reservation-system

# 2. Run the application (no dependencies needed!)
python flight_reservation_system.py
```

> Runs on pure Python 3 — no external libraries required!

---

## 💡 What I Learned

- Implementing **role-based access control** in a console application
- Managing **application state** (booking status transitions)
- Building **menu-driven programs** with clean user flows
- **User authentication** logic — sign up, login, session management
- Structuring a real-world system using **Object-Oriented Programming**

---

## 🔮 Future Improvements

- [ ] Add file/database storage for persistent data (currently in-memory)
- [ ] Build a GUI using Tkinter or a web interface using Flask
- [ ] Add seat selection and flight scheduling features
- [ ] Implement email confirmation on ticket issuance
