# Employees, Sales and Inventory-management-System:


SCOPE
The purpose of the whole project is to create a system for an organization that will manage their sales and inventory records. The scope of the project is to give a simple and attractive application to simplify the work of administrators and employees of the organization.
This project is affiliated to a bakery. It will maintain bakery’s sales and inventory’s record. It will enable bakery’s administrators and employees to maintain their record 
more efficiently and easily

IMPLEMENTATION
Project’s GUI is implemented using Python module Tkinter which has a Database at backend to maintain all records of the bakery. Project is implemented by using OOP Paradigm.
Database is implemented by a Python module Sqlite3.It is a SQl based database.
This project has two different account types, for bakery’s administrator and for bakery’s employee. Both accounts have different options according to their accessibility. 


RELATIONAL DATA BASE DESIGN

Login-: Login table is for keeping username, passwords and account type of users. Login table has three attributes -:

•	Username (Primary key)
•	Password (Not Null)
•	Account type (Not Null)
         Password and Account Type are mandatory fields.

Products-: Product table is for keeping details of products in the bakery. Product table has 6 attributes-:

•	Product id (Primary key)
•	Product name (Not Null)
•	Description
•	Category
•	Price (Not Null)
•	Stock (Not Null) 
        Product Name, Price and Stock are mandatory fields.

Sales-: Sales table is for keeping transaction records of the bakery. This table has 6 attributes-:	
•	Transaction id (Primary key)
•	Invoice no. (Not Null)
•	Product id (Foreign key)
•	Quantity (Not Null)
•	Date
•	Time
Invoice no. and Quantity are mandatory fields.
Here Transaction no. is for transaction of product and Invoice no. is bill number.
