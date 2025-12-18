# ☕ Coffee Machine Simulator (OOP)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python) 
![Status](https://img.shields.io/badge/Status-Completed-success) 
![License](https://img.shields.io/badge/License-MIT-green) 
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange) 
![DaysOfCode](https://img.shields.io/badge/90DaysOfCode-Python%20Challenge-9cf)

A professional Object-Oriented Python coffee machine simulation built using multiple classes and modules. Developed as part of the #90DaysOfCode challenge, this project focuses on clean OOP design, modular architecture, and real-world logic such as resource management, payment handling, and user interaction via the command line.

---
# 🚀 Features

☕ Multiple drink options (Espresso, Latte, Cappuccino)

🧱 Fully Object-Oriented design using classes

🧮 Resource management system (water, milk, coffee)

💰 Coin-based payment processing

🔄 Change calculation & profit tracking

📊 Machine status report (report command)

❌ Graceful handling of unavailable drinks & insufficient resources

📦 Modular multi-file project structure

⌨️ Beginner-friendly command-line interface

🧪 Excellent practice project for Python OOP fundamentals

---
# 📁 Project Architecture
```
CoffeeMachine/
│
├── main.py            # Main program loop
├── menu.py            # Menu & MenuItem classes
├── coffee_maker.py    # CoffeeMaker class (resource handling)
├── money_machine.py   # MoneyMachine class (payment system)
└── README.md          # Project documentation
```
---

# 🛠 Installation & Running the Program

1️⃣ Clone the repository
```
git clone https://github.com/faizhsnnn/CoffeeMachine.git
cd CoffeeMachine
```
2️⃣ Run the program
```
python main.py
```
---

# 🖥 Example Interaction
```
What would you like? (latte/espresso/cappuccino/): latte
Please insert coins.
How many quarters?: 10
How many dimes?: 0
How many nickles?: 0
How many pennies?: 0
Here is $0.0 in change.
Here is your latte ☕️. Enjoy!
```
📊 Report Command
```
What would you like? (latte/espresso/cappuccino/): report
Water: 100ml
Milk: 50ml
Coffee: 72g
Money: $2.5
```
---
# 🧩 Concepts Practiced

* Object-Oriented Programming (OOP)
* Classes & Objects
* Constructors (__init__)
* Methods & attributes
* Encapsulation
* Modular programming
* Conditional logic
* Loops
* User input handling
* Command-line applications
* State & resource management
---
# 🔮 Future Enhancements

* Input validation for non-numeric coin entries
* Retry payment if insufficient money
* Refill resources feature
* Persistent data storage
* Advanced OOP (inheritance & polymorphism)
* GUI version using Tkinter or PyGame
---

# 👨‍💻 Author

Faiz Hasan
BCA Final Year @ Graphic Era University

🚀 #90DaysOfCode 🐍 Python Developer ☕ OOP & CLI App Builder

---
“Clean code is not written all at once — it evolves, one class at a time.”
