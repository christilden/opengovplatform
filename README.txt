-------------------------
Installation Instructions
-------------------------

1.  Refer to webapp/core/INSTALL.txt file for server requirements.
    mod_rewrite is required for opengovplatform to function.

2.  Copy contents under webapp/core to the web server's document root
    directory. Make sure .htaccess file is copied.

3.  Copy webapp/sites directory to web server's document root.

4.  Create a new database in MySQL.

5.  Load data from a SQL file found under db/development into the
    new database.

6.  Copy webapp/sites/default/default.settings.php file as
    webapp/sites/default/settings.php and update the
    database connection settings.  (Line 91)

7.  Default Drupal administration username and password is:
    Username: admin
    Password: password!

