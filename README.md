# Project-CURD
---

# Customer Management System

This Java program demonstrates a simple Customer Management System using CRUD (Create, Read, Update, Delete) operations. It allows users to add, view, update, and delete customer records.

## Features

- **Add Customer:** Add a new customer with a unique ID, name, and bill amount.
- **View Customers:** View all existing customer records.
- **Update Customer:** Update the name and bill amount of an existing customer.
- **Delete Customer:** Delete a customer record by their ID.
- **Exit:** Quit the program.

## Prerequisites

- Java Development Kit (JDK) installed on your system.

## How to Run

1. Clone this repository to your local machine.
2. Open a terminal and navigate to the project directory.
3. Compile the Java files using the following command:
   ```
   javac ProjectDemo.java
   ```
4. Run the compiled Java program using:
   ```
   java ProjectDemo
   ```

## Usage

1. Upon running the program, you'll be presented with a menu displaying available operations.
2. Enter the number corresponding to the operation you want to perform.
3. Follow the prompts to input necessary details such as customer ID, name, and bill amount.
4. Based on your choice, the program will execute the selected operation.
5. To exit the program, select the "Exit" option from the menu.

## Sample Usage

```
CRUD Operations on Customer List:
1. Add Customer
2. View Customers
3. Update Customer
4. Delete Customer
5. Exit
Enter your choice: 1
Enter Customer ID: 101
Enter Customer Name: John Doe
Enter Bill Amount: 100.50
Customer added successfully!

CRUD Operations on Customer List:
1. Add Customer
2. View Customers
3. Update Customer
4. Delete Customer
5. Exit
Enter your choice: 2
Customer List:
Customer [customerId=101, name=John Doe, billAmount=100.5]

...
