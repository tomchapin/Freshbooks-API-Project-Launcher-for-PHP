-----------------------------------------------------------------------------
Freshbooks API Project Launcher for PHP (version 0.0.1)
-----------------------------------------------------------------------------
The goal of this project is to provide a basic re-usable framework for
Freshbooks-related API projects built in PHP. This framework consists
of third-party classes to connect to Freshbooks and MySQL, as well as
functions to synchronize everything with a local database (for fast access).
All of the Freshbooks API calls are also available so you can combine it
all together and make your own application.
 
IMPORTANT: THIS APPLICATION IS NOT CURRENTLY FUNCTIONAL!!! Please check back soon!
 
-----------------------------------------------------------------------------
Author: Tom Chapin (tchapin@gmail.com)
        http://www.tchapin.com
-----------------------------------------------------------------------------
Git: http://github.com/tomchapin/Freshbooks-API-Project-Launcher-for-PHP
-----------------------------------------------------------------------------
Third-Party Libraries Used:
 - Freshbooks PHP Library (http://code.google.com/p/freshbooks-php-library/)
 - QuickBase (http://github.com/ashrewdmint/quickbase)
-----------------------------------------------------------------------------

Server Requirements:

 - PHP 5
 - Curl (with access to external sites)
 - MySQL database
 - Freshbooks API access

-----------------------------------------------------------------------------

Instructions for installation/deployment:

1. Set up a MySQL database and import the initial_mysql_database.sql file
   so that you have the required structure and initial data.

2. Copy the config.example.php file to "config.php" and edit
   it to enter your database connection information, as well
   as your Freshbooks API url and authorization key.
   For more information, please see:
   http://developers.freshbooks.com/blog/view/wheres_my_api_key/

3. Change the server permissions for the /log/ and /tmp/ folders to have
   0777 (write,read,execute) permissions.
   
4. Access the application by loading the index.php file in the root folder.

