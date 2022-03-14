STEPS FOR EXECUTION:

STEP  1: Install xampp- Firstly, install a virtual server on your computer (eg Xampp, Wamp).
 Xampp is a free and open-source cross-platform web server solution stack package developed by Apache Friends, consisting mainly of the Apache HTTP Server, MySQL database, and    interpreters for scripts written in the PHP and Perl programming languages. 

STEP  2: Next we will require an editor where the HTML code has to be written. You can use any editor (such as Notepad++, Adobe Dreamweaver, NetBeans, etc). Here we will use Notepad ++.

STEP 3: Install Notepad++. 

STEP 4 :Make sure to run MYSQL and APACHE once you install the xampp.

STEP 5:Now type localhost/phpmyadmin in your browser url.

STEP 6:Then in the left side of the PHP MYADMIN page ,click on NEW,then you will be prompted to enter the Database name,then type "login_sample_db" as database name,then click on "CREATE" button,thus the database will be created.

STEP 7:once you click create,you will be prompted to  enter the table name,then type table name  as "users",select number of columns as 5,then click on 'GO' button .

STEP 8:Now you will be asked enter the details of the table,Enter as shown below:
CREATE TABLE users (
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    user_id BIGINT NOT NULL UNIQUE,
    user_name VARCHAR(100) NOT NULL UNIQUE,
    password VARCHAR(100) NOT NULL,
    secret  VARCHAR(100) NOTNULL,
    date DATETIME DEFAULT CURRENT_TIMESTAMP
);
Once you enter the details ,then press "SAVE" Button.

STEP 9:In the similar way create another table called"contacts",and enter the details as shown  below:
CREATE TABLE contacts(
   user_id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
   name VARCHAR(100) NOT NULL UNIQUE,
   password VARCHAR(100) NOT NULL,
   email VARCHAR(100) NOT NULL UNIQUE,
);
Once you enter the details ,then press "SAVE" Button.

STEP 10: Once the database is created ,now download the attached php files and place them in the "logo1" folder as shown below:
                          PATH:This pc->windows(c)->xampp->htdocs->logo1
                          
STEP 11:Now go to your browser Url and type -> "localhost/logo1/connection.php", and press enter,to make sure connection with database is established.

STEP 12: once the connection is established ,now type ->"localhost/logo1/signup.php",and press enter,now you will be prompted with SIGN UP webpage.

STEP 13:Make sure to enter unique values each time,as duplicate values are not allowed.

STEP 14:Now enter all the required fields in  SIGN UP webpage,and click on "SIGN UP " BUTTON ,now you will be directed to SIGN IN webpage.

STEP 15:Now enter all the required fields in  SIGN IN webpage,and click on "SIGN IN " BUTTON ,now you will be directed to CONTACTS webpage.

STEP 16:Now enter all the required fields in  CONTACTS webpage,and click on "SAVE " BUTTON ,now you will be directed to MY CONTACTS webpage,where the CONTACTS TABLE will be displayed.




    
