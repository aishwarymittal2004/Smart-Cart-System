# Smart Cart System 🛒

The Smart Cart System is an IoT-based retail automation project designed to eliminate long checkout queues in supermarkets. It enables customers to scan products while shopping, view real-time billing information, and prevent theft through automated verification.

---

## Problem Statement
Traditional supermarket billing systems rely on manual scanning at checkout counters, leading to:
- Long waiting times
- Higher manpower requirements
- Increased chances of billing errors

---

## Solution
Each shopping cart is equipped with:
- A barcode scanner
- An ESP32 microcontroller
- A weight verification system

Customers scan products themselves, and billing details are updated in real time on:
- An on-cart display
- A web-based billing interface

A weight sensor verifies scanned items to prevent theft.

---

## Features
- Real-time barcode scanning
- Live bill generation on a web interface
- On-cart display for product details and total cost
- Wi-Fi–based data synchronization
- Anti-theft weight verification system
- Future support for online payment

---

## Tech Stack

### Hardware
- ESP32
- Barcode Scanner
- Load Cell (Weight Sensor)
- Display Module
- Buzzer

### Software
- Arduino IDE
- HTML, CSS, JavaScript
- Node.js
- MySQL

---

## Working Principle
1. Product barcode is scanned using the scanner.
2. Product details (name, price, weight) are fetched from the database.
3. Information is displayed on the cart screen.
4. Data is sent to the web server via Wi-Fi.
5. The weight sensor compares actual and expected weight.
6. Any mismatch triggers a buzzer alert.

---

## Applications
- Supermarkets
- Hypermarkets
- Grocery stores
- Smart retail shops
- Self-checkout systems

---

## Advantages
- Reduces checkout time and queues
- Minimizes billing errors
- Lowers manpower dependency
- Enhances security and theft detection
- Improves overall shopping experience

---

## Future Enhancements
- Online payment integration (UPI/Card)
- AI-based product recognition
- RFID/NFC-based checkout
- Cloud analytics for inventory management

---

## Author
Aishwary Mittal  
B.Tech (Electronics Engineering)  
Rajiv Gandhi Institute of Petroleum Technology  

📧 Email: aishwarymittal2004@gmail.com

---

⭐ If you find this project interesting, feel free to star the repository!
