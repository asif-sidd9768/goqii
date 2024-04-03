# PHP Application with CRUD Operations - README

This repository contains a simple PHP application with CRUD (Create, Read, Update, Delete) operations using MySQL database. Below are the steps to set up and run the application.

## Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) installed on your system.
- Basic understanding of PHP and MySQL.

## Installation Steps

### 1. Install XAMPP

- Download XAMPP from the [official website](https://www.apachefriends.org/index.html).
- Follow the installation instructions for your operating system (Windows, macOS, Linux).

### 2. Start Apache and MySQL Servers

- Launch the XAMPP Control Panel.
- Start the Apache and MySQL servers by clicking on the "Start" button next to each service.

### 3. Clone the Repository

- Clone this repository to your local machine using Git:
- git clone https://github.com/asif-sidd9768/goqii

  
### 4. Import Database

- Open phpMyAdmin by visiting `http://localhost/phpmyadmin` in your web browser.
- Create a new database named `goqii` or anything.

### 5. Configure Database Connection

- Open the `api.php` file located in the `root` directory.
- Update the database connection details (hostname, username, password, database name) as per your XAMPP configuration.

## Running the Application

- Start your web browser and navigate to `http://localhost/goqii`.

## Usage

- The application provides endpoints for CRUD operations on a user entity.
- You can perform the following operations:
- **Create**: Add a new user by sending a POST request to `/api.php`.
- **Read**: Fetch all users or a specific user by sending a GET request to `/api.php`.
- **Update**: Update an existing user by sending a PUT request to `/api.php`.
- **Delete**: Delete a user by sending a DELETE request to `/api.php`.


