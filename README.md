# Online Store Orders Data Processing

## Overview
This project processes and analyzes order data from an online store stored in JSON format. It provides tools to:
- Load and display order information
- Convert data to Excel format
- Perform basic data analysis

## Features
- **Data Loading**: Loads order data from JSON files
- **Data Display**: Prints formatted order information to console
- **Excel Conversion**: Exports data to Excel spreadsheets
- **Pandas Integration**: Uses DataFrames for efficient data handling

## Data Structure
Each order contains:
- `order_id`: Unique order identifier
- `customer_name`: Customer's name
- `product`: Product name
- `category`: Product category
- `quantity`: Quantity ordered
- `price_per_unit`: Unit price
- `order_date`: Order date (YYYY-MM-DD)
- `payment_method`: Payment method used
- `city`: Customer's city

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/online-store-orders.git
   cd online-store-orders
   Install dependencies:
   pip install pandas openpyxl
## Usage
Run the Jupyter notebook Task_1.ipynb which contains:

Load Data:
```
data = load_data("Task_1_data.json")
```

##Display Data:
```
 display_data(data)  # Prints all orders to console 
```
##Export to Excel:
```
convert_json_to_excel("Task_1_data.json", "orders_output.xlsx")
```
##Example Output
```
Order id: 1001
Customer: Alice Johnson
Product: Wireless Mouse
Category: Electronics
Quantity: 2
Unit Price: $25.99
Order Date: 2025-04-10
Payment Method: Credit Card
City: New York
```

Future Enhancements
Add data visualization

Implement filtering/sorting

Create web interface

Add more analytics functions
