# Blood Bank Donor Management System (BBDMS) PHPProject

## Overview
The **Blood Bank Donor Management System (BBDMS) phpproject** is a web-based application designed to facilitate the management of blood donors, blood banks, and hospital requests. The system helps in registering donors, tracking blood inventory, and coordinating blood requests between hospitals and blood banks. It is built using PHP, MySQL, HTML, CSS, and JavaScript.

## Features
- Donor registration and login
- Blood inventory management
- Hospital blood request system
- Donor donation history tracking
- Automated email notifications for donors and hospitals
- Responsive design for mobile, tablet, and desktop devices

---

## Prerequisites

1. **XAMPP** (or any local server environment supporting PHP and MySQL):
   - Download and install XAMPP from [here](https://www.apachefriends.org/index.html).

2. **Git** (optional, for cloning the repository):
   - Download and install Git from [here](https://git-scm.com/).

3. **Web Browser** (Google Chrome, Mozilla Firefox, Safari, etc.)

---

## Installation Steps

### Step 1: Download the Project

- Download or clone the **phpproject** project from the repository:
  
  **Option 1: Download the ZIP**
  - Download the ZIP file from the repository.
  - Extract the ZIP file, and you will get a folder named `bbdms`.

  **Option 2: Clone using Git**
  - Run the following command in your terminal to clone the repository:
    ```bash
    git clone https://github.com/RajaCS5x/phpproject.git
    ```

### Step 2: Move the Project to XAMPP's `htdocs` Folder

- After downloading or extracting the `bbdms` folder, move the entire folder to the `htdocs` directory inside your XAMPP installation folder. By default, it is located at:
  ```bash
  C:\xampp\htdocs\
### Step 3: Move the Project to XAMPP's `htdocs` Folder

- Open XAMPP Control Panel.
- Start the Apache and MySQL modules.

### Step 4: Set Up the Database
- Open your browser and navigate to phpMyAdmin:

bash
Copy code
http://localhost/phpmyadmin
Create a new database for the project:

Click on New in the sidebar.
Name the database (e.g., bbdms_db).
Click Create.
Import the database structure:

In the newly created database, click on the Import tab.
Choose the bbdms.sql file from the database folder inside the bbdms project folder.
Click Go to import the database structure and data.

### Step 5: Configure the Project
Open the config.php file inside the bbdms folder.
Update the database connection details as needed:
php
Copy code
$servername = "localhost";
$username = "root";        // Default XAMPP username
$password = "";            // Default XAMPP password (leave empty)
$dbname = "bbdms_db";      // Name of the database you created

### Step 6: Run the Project
Open your web browser and go to:

bash
Copy code
http://localhost/bbdms
You will be directed to the Blood Bank Donor Management System homepage.



### License
This project is licensed under the MIT License. See the LICENSE file for more details.
