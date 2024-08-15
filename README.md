# SuperMarket-Billing-System
This is a simple console-based Supermarket Management System implemented in C++. It allows the administrator to manage products by adding, editing, and deleting them from the inventory, and allows the buyer to view the list of products, place orders, and generate receipts.

Features :
Administrator
Add Product: Add new products to the inventory with a unique product code, name, price, and discount.
Edit Product: Modify the details of existing products.
Delete Product: Remove products from the inventory.
View Products: View a list of all products available in the inventory.
Buyer
View Products: View a list of all products available in the inventory.
Place Order: Purchase products by specifying the product code and quantity. Generates a receipt with the total amount including discounts.

Menu Navigation
The main menu provides options for the Administrator and Buyer.
The Administrator needs to log in using the email singhavkesh363@gmail.com and the password 1234567890 to manage products.
The Buyer can view products and place orders.

File Management
The program uses a text file named database.txt to store product details. This file is automatically managed by the program.
Temporary files such as database1.txt are created during edit and delete operations and are deleted automatically after the operations are completed.

Code Overview
shopping::menu(): Displays the main menu and handles user input for the Administrator and Buyer.
shopping::administrator(): Handles the administrator's tasks like adding, editing, and deleting products.
shopping::buyer(): Allows the buyer to view products and place orders.
shopping::add(): Adds new products to the inventory.
shopping::edit(): Modifies existing products.
shopping::rem(): Deletes products from the inventory.
shopping::list(): Displays the list of all products.
shopping::receipt(): Generates a receipt for the buyer's order.
