# CodeIgniter-MongoDB-Library


CodeIgniter (CI) does not currently support MongoDB however, CodeIgniter-MongoDB-Library library allows you to use mongodb within your CI project. This library is based on [intekhabrizvi's "Codeigniter-mongo-library"] (https://github.com/intekhabrizvi/Codeigniter-mongo-library), however that library only supports php mongo extension which is deprecated http://php.net/manual/en/mongo.setup.php. 

CodeIgniter-MongoDB-Library aims to bridge that gap to allow you easily migrate to the new PHP MongoDB extension http://php.net/manual/en/set.mongodb.php if you are currently using the deprecated mongo extension. Also if you are thinking of using MongoDB for your CI project's database, this library provides a easy and clear way to integrate MongoDB with CI.

### Prerequisite
Step 1
Add PHP MongodB extension to your project using composer *composer require mongodb/mongodb* 
OR
Add the following to your composer.json file 
"require": {
    "php": ">=5.3.7",
    "mongodb/mongodb": "^1.2"
},

Step 2 
Run composer install.

Step 3
Copy the contents of application into your CI's application folder.

Step 4
Edit config/mongo_db.php with your database credentials.

Step 5
Start your mongodb server

Step 6
Run the Test Controller to make sure everything is working fine.

Enjoy using this library.

## Bugs/Issues  
Feel free to report any bugs or issues.
