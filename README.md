# Restaurant-Management-System---Object-Oriented-Programming-
Created a fully functional Restaurant Management System. Developed a separate interface with admin privileges for the dealer role providing functionalities to configure prices of different cuisine. managing employees ,table booking system ,preparing bills etc.

=====================================================================
ReadMe for the assignment submitted by 2019B3A70317P and 2019B3A70516P
Project Number: 16
=====================================================================
Team:
1. Aviral Jain - 2019B3A70317P
2. Prakhar Gupta - 2019B3A70516P
=====================================================================
Description of how to run the code and observe the output:
1. The input files are Admin.txt, menu_item.txt and Person.txt. Admin.txt contains login
credentials of Administrators which are verified when a user enters login credentials while
logging in as Admin. Person.txt is used to store login credentials details of new customers using
the Restaurant management system. It verifies the login details of customers when customers try
to enter login credentials.
## For Logging in as Admin Login details are as follows
- ID:1000 Password:prakhar
- ID:2306 Password:aviral
Note: Also tick the checkbox (login as admin)
## For Logging in as Customer (Allowed only when Restaurant is in an open state and not full
otherwise only Administrator login is allowed and Register new Customer button disabled)
login without ticking the checkbox (login as admin) if already registered customers
If the unregistered new customer then click on Register New Customer
A registration panel will open in which you need to set id (only numbers allowed) and
password and enter name and surname in corresponding fields
After registering click on the login button on the top panel and enter id and password (set
earlier) and press login without ticking the checkbox (login as admin)
If tick the checkbox (login as admin) and try to log in as a customer then an error message will
be displayed.
2. If you have logged in as a Customer then initially only Show Menu, Reserve Table will be
enabled and after booking a table in reserve table panel (containing buttons of the table of size
2,4,6) will be enabled.
As a customer, you can view the menu and place an order by clicking on Place Order Button.
## In Show menu Panel
You can see all menu items by clicking the ALL button, and items in particular categories by
clicking the Drink, Fast Food, Main, or Dessert button.
## In place Order Panel
You can place an order by clicking on the Place Order button and then, clicking on the "New"
button to create a new order.
Select adding items by clicking from the menu list on the right side.
Enter quantity and click the "Add" button on the left side. (If the quantity is empty, one item
will be added)
You can delete the ordered item from the order detail by clicking the "Delete" button
### To Edit order
Click the "Place Order" button on the left
Select the order from the order list to edit
Click the "Edit" button
You can add, delete ordered items
## To finalise Order
Select the order from the order list
Click the "Close" button
The order will be closed and go in taken state and then served.
Bill Total Amount will also be displayed in the same panel
## To Cancel Order
Select the order from the order list
Click the "Cancel" button
The order will be cancelled.
## To leave the Restaurant click on log out button
(Note: As soon as the customer will log out the table reserved by the customer will become
vacant)
3. If you have logged in as Admin then all the buttons will be enabled at once.
show Menu, Place Order, Reserve Table will work as described above.
As Admin Manage Restaurant state, Manage Menu Item, Show Revenue is also enabled.
Administrators can control the state of the restaurant (open or closed) by clicking on the
Manage Restaurant state button.
## To close Restaurant
Click on the "Close Restaurant Button"
## To open Restaurant
Click on "Open Restaurant Button"
You can also manage menu items in the menu list by clicking on "Manage Menu Item".
##To add a new item
Click the "Manage menu items" Button on the right
Click the "Add new menu item" button
Fill in all information in the panel opened after clicking "Add new menu item" (Item ID, type,
Name, Price) and clicking OK
##To edit menu item
Click the "Manage menu items" Button on the right
Select a menu item from the menu list
Click the "Edit menu item" button
Fill in all information (Item ID, type, Name, Price) and click OK
##Delete menu item
Click the "Manage menu items" Button on the right.
Select a menu item from the menu list.
Click the "Delete menu item" button.
You can also view Revenue for the day by clicking on the "Show Revenue Button" on the
right.
An Orderlist will appear along with the total price paid by the person (who dinned in)
You can also generate a .txt file of the total Revenue of the day by clicking on "Generate .txt
file". (given all orders are closed)
