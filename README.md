# Car Sales Management Console Application

This is a command-line based Car Sales Management System that allows users to view car stock, purchase cars, view sales data, and collect customer feedback. The system is built using C programming language and implements a user-friendly experience with data validation, storage, and processing capabilities.

## Features

### 1. Looping Menu
The main menu offers the following options for interaction:
- **View Car Stock**: Displays the available car models, year of manufacture, and quantity in stock.
- **Buy Cars**: Facilitates the purchasing process, including car selection and payment details.
- **View Sales Data**: Shows an overview of total sales, organized by car model and customer purchases.
- **Customer Feedback**: Collects and displays customer ratings and comments after a purchase.
- **Exit Program**: Terminates and closes the program

### 2. Car Data Management
The system maintains essential car information using arrays, each limited to a maximum of 15 models:
- **Car Price and Model**: Stores the price and model name of each car.
- **Year of Manufacture**: Stores the production year of each car model.
- **Stock Quantity**: Tracks the number of cars available in stock.

### 3. View Cars Stock
- Displays all available car models along with their price, year of manufacture, and the number of units in stock.
- **Sorted by year of manufacture** in descending order to provide a clear overview of the latest models first.

### 4. Car Purchase System
The purchase system captures the following data during a transaction:
- Customer details: name and age.
- Purchase information: model, price, discount applied (if any), number of cars bought, and the total purchase amount.
- Date of purchase is recorded for tracking purposes.
- The car stock is updated automatically based on the sale.

### 5. Input Validation
Robust input validation ensures that only correct and meaningful data is entered by the user. The system continues to prompt the user until valid information is received.

### 6. Sales Data
- Sales data is displayed as a total sum for each car model, showing the total units sold and the total revenue generated.
- Additionally, it provides a breakdown of each customer's purchase.
- **Sorted by total sales amount** in descending order for quick analysis of top-selling models.

### 7. Persistent Sales Data
- Sales data is stored in a file and loaded upon program startup to maintain data continuity between sessions.
- The system reads and updates the file as new sales are made, ensuring that past and current sales data is always available.

### 8. Customer Feedback
After completing a purchase, customers have the option to leave feedback, including a rating (out of 5) and a short comment. Feedback is stored and linked to the car model they purchased for future reference.

### 9. OS Validation
The program includes a feature that detects the user's environment and adjusts its behaviour based on the operating system upon launching. The system supports the following:
- Windows
- macOS
