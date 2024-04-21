E-commerce Application
Overview
This is an E-commerce application developed using Python and MySQL. The application provides functionalities for users to register, login, browse products, place orders, and make payments. It also includes an admin dashboard with functionalities to manage products, orders, and payments.

Features
User Registration/Login: Users can register with a username, password, and email. Registered users can login to the system using their credentials.
Product Management: Admin can add, update, and delete products.
Order Placement: Users can browse products, select the quantity, and place orders. The total price is calculated based on the selected product and quantity.
Payment Confirmation: Admin can confirm payments for orders placed by users.
Order Confirmation: Admin can confirm orders placed by users.
Inventory Management: Admin can view the inventory of products.
Technologies Used
Python: Programming language used for backend development and GUI using Tkinter library.
MySQL: Database management system used to store product, user, and order data.
Tkinter: Python library for creating GUI applications.
Installation and Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/e-commerce-application.git
Install requirements:
Copy code
pip install -r requirements.txt
Setup the database:
Import the database.sql file into your MySQL database to create the required tables and stored procedures.
Run the application:
Copy code
python e_commerce.py
Project Structure
bash
Copy code
e-commerce-application/
│
├── e_commerce.py          # Python code for the E-commerce application
├── database.sql           # SQL script for database setup
├── README.md              # Project README file
└── requirements.txt       # Required Python packages
Screenshots



Contribution
Contributions are welcome! Fork the repository and submit a pull request with your changes.


