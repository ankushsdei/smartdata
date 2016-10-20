Requirements
------------
+ Apache web server
    + .htaccess turned on
    + disable directory browsing
    + make sure AllowEncodedSlashes is set to NoDecode in httpd.conf
+ PHP 5.4+ with the following extensions:
    + mcrypt
    + make sure PDO extension is enabled for mysql
    + make sure php-soap is installed
    + make sure php-xml is installed
    + oAuth
+ MySQL with timezone tables loaded
    + e.g. mysql_tzinfo_to_sql /usr/share/zoneinfo | mysql -u root -p mysql


Installation
------------
+ Run command "composer install" in root folder to install PHP component
+ Run command "bower install" in root folder to install JS components