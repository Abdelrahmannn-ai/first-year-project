# first-year-project
This is a console-based supermarket management system developed in C++ using structs for data management and file I/O for persistence.

Data Structures:
- Customer struct: Stores ID, password, name, phone, location.
- Product struct: Includes code, name, category, production/expiration dates, price, quantity.
- Order struct: Contains customer ID, product names, total price, number of products.

Key Features:
- User authentication: Admin login (ID: admin, password: 1234) and customer signup/login.
- Product management: Add, edit, delete products with validation for dates and categories.
- Order creation: Customers can create orders, deducting stock in real-time.
- Data persistence: Saves customers, products, orders to text files (customers.txt, products.txt, orders.txt).
- Admin dashboard: Manage products, view orders.
- Customer menu: Edit profile, browse products by category, search, view orders, provide feedback.
- Input validation: Date validation, duplicate ID checks, stock availability.
- Pagination: For displaying products to improve usability.
- Feedback system: Collects user feedback in feedback.txt.

Workflow:
- Load data from files on startup.
- Main menu for signup, login, help.
- Admin menu for product management.
- Customer menu for shopping and profile management.
- Save data on exit.

This project demonstrates file handling, input validation, and user interface design in a console application.
