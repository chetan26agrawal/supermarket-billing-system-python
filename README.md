# Supermarket Billing System Using Python

## 📌 Project Overview

This project is a Python-based mini project that automates the billing process in a supermarket. It calculates item-wise prices, processes multiple shopping items, applies a discount based on the subtotal, and generates an itemized bill with the subtotal, discount, and final payable amount.

The objective was to develop a simple and practical billing application that demonstrates how Python programming can automate everyday retail operations.

The project combines user input, arithmetic calculations, conditional statements, loops, and list-based data handling to create a structured billing workflow.

## 🎯 Business Problem

Manual billing can become time-consuming when customers purchase multiple products. Calculating individual item amounts, applying discounts, and preparing a final bill manually can also lead to calculation errors.

This project focuses on addressing the following requirements:

- How can multiple shopping items be processed in a single transaction?
- How can item amounts be calculated using quantity and unit price?
- How can discounts be applied automatically based on billing conditions?
- How can the subtotal and final payable amount be calculated accurately?
- How can an itemized receipt be generated in a readable format?
- How can Python programming simplify the basic supermarket billing process?

## 📊 Project Scope

The project covers five major billing operations:

1. Item Input and Data Collection
2. Item-Wise Amount Calculation
3. Conditional Discount Application
4. Final Bill Calculation
5. Itemized Receipt Generation

The system accepts product details from the user, processes the purchase, calculates the bill, and displays the final receipt.

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Python Lists
- User Input Handling
- Loops and Conditional Statements
- Arithmetic Operations
- Basic Data Handling
- Receipt Formatting
- Program Testing

## 📄 Project Workflow — Item Input & Billing

### 🎯 Objective

The first step collects the details of each product purchased by the customer.

### 📌 Key Inputs

- Item Name
- Quantity
- Price per Item

### 🔍 Operations Performed

- Accepted item details from the user.
- Processed multiple products in a single transaction.
- Stored item information for subsequent calculations.
- Calculated the amount for each item using quantity multiplied by unit price.
- Continued accepting products until the user finished entering items.

## 📄 Billing Logic — From Items to Final Amount

### 🎯 Objective

This stage calculates the subtotal, checks the discount condition, and determines the final amount payable by the customer.

### 📌 Key Calculations

- **Item Amount:** Quantity × Price per Item
- **Subtotal:** Sum of all item amounts
- **Discount:** 10% of the subtotal when the subtotal exceeds ₹1,000
- **Final Amount:** Subtotal − Discount

### 🔍 Analysis & Processing Performed

- Calculated the amount for each product.
- Added individual item amounts to the subtotal.
- Checked whether the subtotal exceeded ₹1,000.
- Applied a 10% discount when the condition was satisfied.
- Calculated the final payable amount after discount.
- Used conditional statements to control the billing logic.

## 📄 Code Walkthrough & Actual Output

### 🎯 Objective

This section demonstrates how Python programming concepts are used to implement the billing process and generate the final receipt.

### 📌 Key Programming Concepts

- Variables for storing billing values
- `input()` for collecting user information
- `while` loop for processing multiple items
- `if-else` statements for discount logic
- Lists for storing item details
- Arithmetic operations for billing calculations
- Formatted output for displaying the receipt

### 🔍 Operations Performed

- Collected product information from the user.
- Calculated item-wise amounts.
- Stored item details in a list.
- Applied the discount condition.
- Generated an itemized receipt.
- Displayed the subtotal, discount, and final total.

The project also demonstrates how a straightforward Python program can automate a common real-world business process.

## 📈 Example Billing Calculation

The presentation demonstrates the following sample purchase:

| Item | Quantity | Price | Amount |
|---|---:|---:|---:|
| Apple | 2 | ₹20.00 | ₹40.00 |
| Banana | 10 | ₹5.00 | ₹50.00 |
| Carrot | 6 | ₹3.00 | ₹18.00 |
| Radio | 1 | ₹500.00 | ₹500.00 |
| Speaker | 1 | ₹2,500.00 | ₹2,500.00 |
| **Subtotal** | | | **₹3,108.00** |
| **Discount (10%)** | | | **₹310.80** |
| **Final Total** | | | **₹2,797.20** |

*Note: These are the example values shown in the project presentation.*

## 💡 Key Learnings

The project demonstrates practical applications of fundamental Python programming concepts:

- **Loops & Conditions:** Used loops and conditional statements to control the billing workflow and discount calculations.
- **Lists & Data Handling:** Managed multiple shopping items and their details using lists.
- **User Input & Output:** Collected product information and displayed a formatted receipt.
- **Arithmetic Calculations:** Calculated item amounts, subtotal, discount, and final total.
- **Real-World Application:** Applied Python programming to automate a supermarket billing scenario.

## 💼 Practical Applications

The project illustrates how basic programming can support routine retail operations, including:

- Automated billing calculations
- Item-wise price calculation
- Conditional discount processing
- Receipt generation
- Reduction of repetitive manual calculations
- Improved readability of billing information

## 🚀 Project Outcome

Developed a Python-based Supermarket Billing System that processes multiple products, calculates item-wise amounts, applies a 10% discount when the subtotal exceeds ₹1,000, and generates an itemized receipt showing the subtotal, discount, and final payable amount.

The project demonstrates the practical use of Python fundamentals to automate a common retail billing workflow and provides a foundation for developing more advanced billing applications.

## 🔮 Future Scope

The project presentation identifies the following opportunities for further development:

- **GST Calculation:** Add GST based on product categories and applicable tax rates.
- **Product ID & Barcode Support:** Support faster product identification and billing.
- **Inventory Management:** Track stock levels and alert users when inventory is low.
- **Save Bill to File:** Store billing history for future reference.

These enhancements could extend the current mini project into a more comprehensive supermarket management solution.

## 📚 Key Skills Demonstrated

### 🐍 Python Programming

- Variables and Data Types
- User Input and Output
- Loops and Conditional Statements
- Lists and Data Handling
- Arithmetic Operations
- Output Formatting

### 📊 Billing & Business Logic

- Item-Wise Price Calculation
- Subtotal Calculation
- Conditional Discount Logic
- Final Bill Calculation
- Itemized Receipt Generation
- Billing Workflow Automation

### 💻 Development & Problem Solving

- Logic Building
- Process Automation
- Basic Program Testing
- Real-World Problem Solving
- Structured Programming

## 📂 Repository Structure

```text
supermarket-billing-system-python/
│
├── Supermarket_Billing_System.ipynb
├── Supermarket_Billing_System.py
├── Screenshots/
│   └── Billing_Output.png
├── Presentation/
│   └── Super_Market_Billing_By_Chetan_Agrawal.pptx
└── README.md
```

*This is a suggested repository structure. Keep only the files you actually upload, and update the filenames to match your repository.*

## 👤 Author

**Chetan Agrawal**

Python | Data Analytics | Excel | SQL | Power BI

## 🏷️ Project Type

Python Mini Project | Supermarket Billing System | Billing Automation | Beginner Python Project

## ⭐ Key Takeaway

This project demonstrates how Python fundamentals such as loops, conditional statements, lists, and arithmetic operations can be used to automate supermarket billing, apply discount rules, and generate clear itemized receipts. It provides a practical foundation for building more advanced retail billing and inventory management applications.
