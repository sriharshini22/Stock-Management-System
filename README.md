# Stock-Management-System
This is a Stock Management System in PHP and MySQL Database. 
This is a web-based application that provides an online and automated platform for shops or businesses. This project can manage the company's Purchase Orders, Receiving, Back Orders, returns, and Sales Records. The application has a pleasant user interface with the help of Bootstrap Library and AdminLTE template. This has also user-friendly functionalities.

![inventory-management-software-500x500](https://github.com/sriharshini22/Stock-Management-System/assets/82818345/86722309-7c3b-488f-850e-26fad8862cf6)

About the Stock Management System

I have developed this PHP application using the following:

1. XAMPP v3.3.0 as my local webserver that has a PHP Version 8.0.7
2. PHP Language
3. MySQL Database
4. HTML
5. CSS
6. JavaScript
7. jQuery
8. Ajax
9. Bootstrap
10. AdminLTE
    
This Stock Management System can be only accessed by 2 types of users which are the System Admins and Staff. The Admin User can access and manage all the pages, forms, and features do the web application does while the Staff Users have limited access only.

The Stock Records such as the Purchase Order, Receiving, etc. in this project have print features for each record. Talking about the flow of this project, first, the admin users must populate all the important lists which are the supplier list and the item list. Next, users will create a Purchase Order Record for a supplier. After that, users can receive the items in each purchase order which means PO Record is required in order to add stock of the item. Then, when receiving the items when the supplier will only deliver some of the items or not complete, the system will automatically create a new Back Order Record for the items that are not delivered yet. BO records work like the Purchase Order Record. Next, when the received items have problems, issues, or etc., the management can create the Return Record and upon saving this file, the system will also automatically deduct the damaged items to the stock availability. Lastly, the sales record is the record of the company for stocks that have been purchased by their clients or customers. Each stock listed in the sales record will also be deducted from the stock availability.

FEATURES: 

    Secure Login and Logout
    Manage Supplier List (CRUD)
    Manage Item List (CRUD)
    Manage Purchase Order Records
      1. Create New
      2. Edit Record
      3. View Record
      4. Print Record
      5. Delete Records
    Manage Receiving Records
      1. Receive From PO (Purchase Order)
      2. Automatically Creates New Back Order for Lacking Items/Stocks
      3. Edit Record
      4. Print Record
      5. Automatically adds to Item stock availability
      6. Delete Record
    Manage Back Order Records
      1. View Record
      2. Receive BO
      3. Print Record
    Manage Return Records
      1. Create New Records
      2. View Record
      3. Edit Record
      4. Print Record
      5. Delete Record
      6. Automatically updates the stock availability upon saving
    Manage Sales Records
      1. Create New Records
      2. View Record
      3. Edit Record
      4. Print Record
      5. Delete Record
      6. Automatically updates the stock availability upon saving
    Manage Users list (CRUD)
    Manage Account Details/Credentials
    Manage System Information

REQUIREMENTS: 

Download and Install any local web server such as XAMPP/WAMP.
Download the provided source code zip file.

INSTALLATION: 

1. Open your XAMPP/WAMP's Control Panel and start Apache and MySQL.
2. Extract the downloaded source code zip file.
3. If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. And If you are using WAMP, paste it into the "sms" directory.
4. Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
5. Create a new database naming login_signup_php.
6. Import the provided SQL file. The file is known as login_signup_php.sql located inside the database folder.
7. Browse the Stock Management System in a browser,i.e. http://localhost/sms/.


