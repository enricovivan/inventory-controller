# inventory-controller
A simple inventory management app

# Info
- Made with Laravel 9

# To run
 - First make sure you have PHP 8.0 installed.
 - In terminal of the root folder, to install all dependencies, type:
$ composer install
 - Make a copy of the file ".env.example" with the name ".env" and paste in root folder.
 - Create a new schema in your database with any name. In this example it will be "butter".
 - Modify the ".env" file with the information you need to connect in the database, like this:
 ![code](https://user-images.githubusercontent.com/36749683/215916472-8ac55800-722b-4e37-b187-5f7dbf472a79.png)

 - In the terminal, run the command to install the migrations table in your database:
 - $ php artisan migrate:install
 - If the previous step was successful, your Laravel is connected to your database, if not, check if you didn't misspell anything.
 - In the terminal (again) to create the tables in the database. run the command: 
 - $ php artisan migrate
 - And finally, to run the server, type the command in the terminal:
 - $ php artisan serve
 - To view the page, acess:
 - > 127.0.01:8000
 - Have fun (or not).
 
 # About
 - I made this as a way to develop my skills with Laravel, since I'm a beginner.
 - So, the fact that I'm in a learning process, means a lot of mistakes (and bugs), but I'll get rid of them (probably).
