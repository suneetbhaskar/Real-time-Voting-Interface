# Online Voting System

## Overview

The Online Voting System is a web-based application that allows users to participate in elections conveniently. Built using HTML, PHP, and MySQL, this project provides a user-friendly interface for voters and administrators. It utilizes XAMPP as a local server environment for development and testing.

## Features

- User registration and login
- Create and manage elections
- Cast votes securely
- View election results
- Admin dashboard for managing users and elections

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL (via phpMyAdmin)
- **Development Environment:** XAMPP

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Install [XAMPP](https://www.apachefriends.org/index.html) on your local machine.
- Basic knowledge of PHP, MySQL, and web development.

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/online-voting-system.git
   
2. **Move the project folder to XAMPP's htdocs directory:**

bash
mv online-voting-system /path/to/xampp/htdocs/

3. **Start XAMPP:**

Open XAMPP Control Panel and start Apache and MySQL.

4. **Create the database:**

Open phpMyAdmin by navigating to http://localhost/phpmyadmin.
Create a new database named voting_system.
Import the SQL file located in the sql directory of this project (if available).

5. **Configure database connection:**

Open the config.php file in the project directory.
Update the database connection settings to match your local environment.

6. **Access the application:**

Open your web browser and navigate to http://localhost/online-voting-system.

<h2>Usage</h2>

Register a new user account or log in with existing credentials.
Create elections as an admin and manage participants.
Users can vote in the elections and view results once they are finalized.

<h2>Contributing</h2>

Contributions are welcome! Please fork the repository and submit a pull request.

Fork the repository
Create your feature branch (git checkout -b feature/YourFeature)
Commit your changes (git commit -m 'Add some feature')
Push to the branch (git push origin feature/YourFeature)
Open a pull request

<h2>License</h2>
This project is licensed under the MIT License - see the LICENSE file for details.

<h2>Contact</h2>
For any inquiries or issues, please contact:

Suneet Singh Bhaskar - suneetsinghbhaskar11oct@gmail.com
