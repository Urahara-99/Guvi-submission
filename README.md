**Description**
This project is a web application that involves user registration, login, and profile management. The application uses MySQL for storing registered user data and MongoDB for managing user profile details. Sessions are managed using Redis on the backend, and localStorage is used for maintaining login sessions in the browser.

*Technologies Used*

HTML: For structuring web pages.
CSS: For styling web pages (using Bootstrap for responsiveness).
JavaScript: For client-side logic.
jQuery: For DOM manipulation and AJAX requests.
PHP: For server-side logic.
MySQL: For storing registered user data.
MongoDB: For storing user profile details.
Redis: For managing session information on the backend.

_Installation and Setup:_

Prerequisites
XAMPP or similar environment with PHP and MySQL.
MongoDB server installed and running.
Redis server installed and running.
Composer for managing PHP dependencies.
Setup Instructions
Clone the Repository

cd <repository-directory>
Set Up the Database

Import the SQL schema into your MySQL database for user management.
Create a MongoDB database for user profiles.
Install PHP Dependencies

Ensure you have Composer installed.
Run the following command to install the Predis library for Redis:
bash
Copy code
composer require predis/predis
Configure Environment

Update php.ini to include the Redis extension if needed.
Configure your MySQL, MongoDB, and Redis connection settings in your PHP files.
Start the Servers

Start your XAMPP (Apache and MySQL).
Start the MongoDB and Redis servers.
Access the Application

Open your browser and navigate to http://localhost/
