# 📁 ___logApp-scaling-octo___ 📁

## __Description__ 📘
*This repository is an activity for Practice 5-06. 
It is a website designed for a basic user data insertion such as names and addresses to its own database.*

___

## __Visuals__ ✨
### 1️⃣ ***Registration*** 

<img src= "https://i.imgur.com/rbCcSpo.png" width="700" height="350" />

### 2️⃣ ***Login*** 

<img src= "https://i.imgur.com/QwTpjPf.png" width="500" height="500" />

### 2️⃣ ***List gathered from the registered users through the database*** 

<img src= "https://i.imgur.com/iYPDqdE.png" width="700" height="350" />
___

## __Installation__ 📋

### *Download*
1. Download [XAMPP](https://www.apachefriends.org/download.html "XAMPP download") so you can have access to your local phpMyAdmin. You can also use [freesqldatabase](https://www.freesqldatabase.com/) so you can access your database online.

### *Database Making*
2. When you have your XAMPP downloaded or your account logged in on the *freesqldatabase* site, you can now proceed in making your own database by naming it first, then add the tables needed and their respective columns.

    *Example:*
   * Database Name: **guestlist**
   * Table 1 Name: **account**
   * Table 2 Name: **person**

### *Database Connection Setup*
3. You should open the file config.php in the project/repository and define the values set for DB_HOST, DB_USER, DB_PASS, DB_NAME. These values vary from which database host you are using, whether it is from your local database or online database.

#### *For Online Database*
     define('DB_HOST', 'sql6.freesqldatabase.com');
     define('DB_USER', 'sql6447446');
     define('DB_PASS', 'RFi9iEXbgG');
     define('DB_NAME', 'sql6447446');

#### *For Local Database*
     define('DB_HOST', 'localhost');
     define('DB_USER', 'root');
     define('DB_PASS', '');
     define('DB_NAME', 'guestlist');

___

## __Author__ 📌

<img src= "https://i.imgur.com/q2vM6OJ.jpg" width="200" height="200" />

***Kaye Janiecka J. Parcon***

***BSCS 3 - B1*** 🎉

