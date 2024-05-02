# PG-LIFE
The PG-Life Web Application is a platform designed to facilitate the management and search for Paying Guest (PG) accommodations. It allows users to explore available PG options, view details, and connect with potential landlords or tenants.

Installation
To set up the PG-Life Web Application on your local system, follow these steps:

Clone the repository:
git clone https://github.com/Devil8107/PG_Life.git 
Database Connectivity:
Create a database with phpMyAdmin using the same name as the provided SQL file name. Import the given SQL file into the created database.

Update database connectivity: In the file includes/database_connect.php, modify the following line:
php

$conn = mysqli_connect("localhost", "username_of_phpmyadmin", "password_of_phpmyadmin", "Database_name(PGLife)");
Replace "username_of_phpmyadmin", "password_of_phpmyadmin", and "Database_name(PGLife)" with your phpMyAdmin credentials and the database name you created.

Usage
After completing the installation steps, open the PG-Life Web Application on your local server.
Explore the available PG accommodations by browsing through the listings.
View details of each listing, such as location, amenities, pricing, and contact information.
Connect with landlords or potential tenants by using the provided contact information.
Use the search functionality to filter PG accommodations based on specific criteria.
Technologies Used
The PG-Life Web Application utilizes the following technologies:

HTML
CSS
JavaScript
PHP
MySQL (phpMyAdmin)
Thank you for using PGLife!
