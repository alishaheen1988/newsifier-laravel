
## About Project

This project is the main project, whick contains the articles pages and the editor js plugin

## Running Project
These are the commands you should execute one by one to run the project:
- git init
- git clone https://github.com/alishaheen1988/newsifier-laravel.git
- cd cd .\newsifier-laravel\
- composer install
- create an empty database on MySQL
- copy the .env.example to .env file and set the database connection settings
- php artisan migrate
- php artisan key:generate
- php artisan serve  
Open another command prompt and go to the project folder, then run these 2 commands:
- npm install
- npm run dev