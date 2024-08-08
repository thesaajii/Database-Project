# Markhor Motor Car Showroom Database

## Overview

The Markhor Motor Car Showroom Database is designed to manage and store information related to car inventory, sales, customers, and employees. This database facilitates the efficient handling of showroom operations, enabling streamlined processes and better decision-making.

## Database Structure

The database comprises several tables, each dedicated to storing specific types of information. Below is an overview of the main tables:

### 1. **Cars**
- **Table Name:** `cars`
- **Description:** Stores detailed information about each car available in the showroom.
- **Columns:**
  - `car_id`: Unique identifier for each car (Primary Key)
  - `make`: The manufacturer of the car (e.g., Toyota, Honda)
  - `model`: The model of the car (e.g., Corolla, Civic)
  - `year`: The manufacturing year of the car
  - `color`: The color of the car
  - `price`: The price of the car
  - `engine_type`: The type of engine (e.g., Petrol, Diesel, Electric)
  - `mileage`: The mileage of the car
  - `availability_status`: Whether the car is available for sale or sold

### 2. **Customers**
- **Table Name:** `customers`
- **Description:** Contains information about customers who have made purchases or inquiries.
- **Columns:**
  - `customer_id`: Unique identifier for each customer (Primary Key)
  - `first_name`: Customer's first name
  - `last_name`: Customer's last name
  - `email`: Customer's email address
  - `phone_number`: Customer's contact number
  - `address`: Customer's residential address
  - `purchase_history`: Details of cars purchased by the customer (Foreign Key)

### 3. **Sales**
- **Table Name:** `sales`
- **Description:** Records all transactions made in the showroom.
- **Columns:**
  - `sale_id`: Unique identifier for each sale (Primary Key)
  - `car_id`: Reference to the car sold (Foreign Key)
  - `customer_id`: Reference to the customer who made the purchase (Foreign Key)
  - `sale_date`: Date of the sale
  - `amount`: Total amount of the sale

### 4. **Employees**
- **Table Name:** `employees`
- **Description:** Manages employee information for showroom staff.
- **Columns:**
  - `employee_id`: Unique identifier for each employee (Primary Key)
  - `first_name`: Employee's first name
  - `last_name`: Employee's last name
  - `position`: Job title or role (e.g., Sales Manager, Technician)
  - `hire_date`: Date of hiring
  - `salary`: Employee's salary
  - `contact_number`: Employee's contact number

## Installation

To set up the Markhor Motor Car Showroom Database:

1. **Database Software:** Ensure that you have MS OFFICE install on your system
## Usage
It have user interface that help the user to navigate and learn how to use it
### Inserting Data
Use SQL `INSERT` statements or a user interface provided by your application to add data to the tables. Ensure that data is entered accurately to maintain database integrity.

### Querying Data
You can perform various queries to retrieve data from the database, such as:
- Listing all available cars
- Viewing customer purchase history
- Checking employee details

### Updating Data
Use SQL `UPDATE` statements to modify existing records in the database, such as updating car prices or customer contact details.

### Deleting Data
Use SQL `DELETE` statements to remove records from the database if necessary. Be cautious when deleting data to avoid unintentional loss of important information.

## Contributing

If you wish to contribute to the development or improvement of this database, please fork the repository and submit a pull request with your changes. Ensure that your contributions are well-documented and tested.

## License

This project is licensed under the UOC Project License.

## Contact

For any inquiries or support, please contact "thesajidbutt@gmail.com".

---
