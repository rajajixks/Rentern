## Overview
This project is a web application for renting houses. It allows users to browse available properties and view property details. The website is built using HTML, CSS, JavaScript for the front-end, and PHP with MySQL for the back-end.

## Features
- User authentication (sign up, login, logout)
- Browse available properties
- View detailed property information

## Technologies Used
- **HTML**: Structure of the web pages
- **CSS**: Styling of the web pages
- **JavaScript**: Client-side scripting for interactivity
- **PHP**: Server-side scripting
- **MySQL**: Database management

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/RENTERN.git
    ```
2. Navigate to the project directory:
    ```bash
    cd RENTERN
    ```
3. Import the database:
    - Create a database named `RENTERN`.
    - Import the `database.sql` file located in the `db` folder.

4. Configure the database connection:
    - Open `config.php` in the `includes` folder.
    - Update the database credentials:
    ```php
    define('DB_SERVER', 'localhost');
    define('DB_USERNAME', 'your_username');
    define('DB_PASSWORD', 'your_password');
    define('DB_NAME', 'RENTERN');
    ```

5. Start the server:
    - If using XAMPP, place the project folder in the `htdocs` directory and start Apache and MySQL.
    - Access the website at `http://localhost/RENTERN`.

## Usage
- **Home Page**: Browse available properties.
- **Property Details**: Click on a property to view more details.
- **User Authentication**: Sign up or log in to access additional features.


## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Contact
For any inquiries, please contact [rajajixks@gmail.com].
