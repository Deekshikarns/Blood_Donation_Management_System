# Blood_Donation_Management_System
This Blood Bank Management System is a web-based application developed using PHP and MySQL, hosted on a local server using XAMPP.A Blood Donation Management System is a software application designed to manage and streamline the process of blood donation, including donor registration, patient registration. It also features patient request forms and search functionalities to efficiently match blood donors with patients in need.
# Features
1.User authentication (Admin, Donor, Recipient)

2.Manage blood donors and recipients

3.Record blood donations and transfusions

4.Search for available blood types

5.View donation history.
# Installation
1.Clone the Repository: git clone [https://github.com/Deekshikarns/Blood_donation_management_system.git]

2. XAMPP: Open XAMPP Control Panel and start Apache and MySQL.

3.Create Database: Open phpMyAdmin by navigating to http://localhost/phpmyadmin in your web browser.

4.Create a new database named blood_donation. Import the blood_donation.sql file located in the database directory of the cloned repository.

5.Configure Database Connection: Open the project directory and locate the config.php file.

6.Update the database connection settings with your MySQL credentials:

<!--
<?php

$host = 'localhost';

$user = 'root';

$pass = '';

$db = 'blood_donation';

$conn = new mysqli($host, $user, $pass, $db);

if ($conn->connect_error) {

    die("Connection failed: " . $conn->connect_error);
    
}

?>
-->
7.Run the Application: Place the project directory in the htdocs folder of your XAMPP installation. Open your web browser and navigate to http://localhost/Blood-donation-management-system.
# usage
1.Admin Login:

Navigate to the admin login page.

Use the following credentials to log in as an admin:

Username: admin

Password: password

2.Manage Donors:

Add, edit, and delete donor information.

Record new blood donations.

3.Manage Recipients:

Add, edit, and delete recipient information.

Record blood transfusions.

4.Search Blood Types: Search for available blood types and donors.
# Database
1.admin: Stores admin login information.

2.donors: Stores donor information.

3.patient: Stores patient information.

4.request: Stores blood require records.

# Technologies Used
1.PHP

2.MySQL

3.HTML

4.CSS

5.XAMPP
