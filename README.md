# PHP MVC framework not for production
This project just was to learn and understand how MVC design pattern works.
----
## Features
1. Created Models and Controllers file structure.
2. created Views and public folders to make assets accessable by the browser through '.htaccess' file.
3. created a routing system and middlwares to be executed during the request-response lifecycle.
4. created a simple authentication system with data validation and validation rules to validate input data.
5. created migrations and database schema not to create DB structure each time you clone the project.

----
## Installation

1. Download the archive or clone the project using git
2. Create database schema
3. Create `.env` file from `.env.example` file and adjust database parameters (including schema name)
4. Run `composer install`
5. Run migrations by executing `php migrations.php` from the project root directory
6. Go to the `public` folder 
7. Start php server by running command `php -S 127.0.0.1:8080` 
8. Open in browser http://127.0.0.1:8080

