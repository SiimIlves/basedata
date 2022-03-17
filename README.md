Unbelievably basic RubyRails app

* Versions
Ruby3.1.1/Rails7.0.2.2/Any MariaDB version

* System Dependencies
Will probably work on any basic Linux OS, could not for the life of me run anything rails-based on windows.

* Configuration
Should create an account for MariaDB and then add it to database.yml. Also needs database name which you can create by entering mariadb and then "CREATE DATABASE data"

* Database creation
AFter creating the database just type "USE data;" and "CREATE TABLE users (name VARCHAR(255), id integer PRIMARY KEY AUTO_INCREMENT);"

* Database initialization
Make sure you're cmd'd into the project folder and then run "rake db:create" + "rake db:migrate" (probably not necessary)

* How to run the test suite
Rails s OR rails start

* Services (job queues, cache servers, search engines, etc.)
-
* Deployment instructions
-
* ...
