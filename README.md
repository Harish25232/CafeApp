☕ CafeApp – Java Console-based Cafe Ordering System
📌 Overview
CafeApp is a simple Java console application that simulates a cafe ordering system. It allows users to:

View a predefined menu,

Place an order,

Get suggestions for discounts if close to discount thresholds,

Apply discounts based on total order amount,

Save order details to a text file,

Cancel the order if not confirmed.

It also demonstrates the use of:

Custom exceptions

File handling

Object-oriented programming principles

Input validation

🧾 Features
📋 Interactive Menu Display

✅ Input Validation (name format, valid item selection, quantity)

💰 Dynamic Discount Suggestion

5% discount for orders ₹500 or more

10% discount for orders ₹1000 or more

💾 Order History Saved to File

❌ Graceful Cancellation

🔐 Custom Exception Handling

🧠 Technologies Used
Java SE (Standard Edition)

Core Java concepts:

Classes & Objects

File I/O (FileWriter, File)

Collections (ArrayList)

Exception Handling (try-catch, custom exceptions)

📂 Project Structure
cpp
Copy
Edit
CafeApp.java           // Main application file
order_filename.txt     // Generated per customer (e.g., John_Doe.txt)
🚀 How to Run
✅ Prerequisites:
JDK 8 or above

Command line or any IDE (e.g., IntelliJ IDEA, Eclipse)

🔧 Steps:
Save the code into a file named CafeApp.java

Open a terminal/command prompt.

Compile:

bash
Copy
Edit
javac CafeApp.java
Run:

bash
Copy
Edit
java CafeApp
📥 Sample Run
vbnet
Copy
Edit
Enter your name: Alice

Welcome to Team Kalisi Cafe, Alice!
Here is our menu:
1. Cappuccino - ₹99
2. Tea        - ₹19
...

Enter the number of the item you want to order (or 0 to finish):
1
How many Cappuccino(s) would you like to order?
2
...

You're ₹15.00 away from getting a 5% discount.
Would you like to add more items to get the discount? (yes/no):
...
📄 Output Example (Saved File: Alice.txt)
yaml
Copy
Edit
Cappuccino x 2 = ₹198.0
Tea x 1 = ₹19.0
Pizza x 1 = ₹149.0
Total: ₹366.0
Discount: ₹0.0
Final Bill: ₹366.0
❗ Error Handling
Type	Description
CafeException	Custom errors like invalid menu choice or quantity
NumberFormatException	Catches non-numeric inputs
IOException	Catches file write errors

✍️ Author
Developed by [K.Harish]

Thank You! 
