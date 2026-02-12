# Lampstack-Lab

## Description
COLORS application that is done for the Colors Lab in COP4331. This project is a demonstration of a full-stack implementation usigin LAMP stack

## Technologies
* GitBash
* Linux
* Apache
* MySQL 
* PHP 
* HTML, CSS, JavaScript

## Set Up
1. Connect
    * Open an SSH with root@yourIP, log in with your credentials
1. Clone the Repo
    ```bash
    git clone https://github.com/Olyguy/lampapi-lab.git
    sudo git clone https://github.com/your-username/colors-lamp.git
1. Configure the Database
    * Access the MySQL terminal: mysql -u your_username -p
    * Create your database and import the schema:
        ```bash
        mysql> CREATE DATABASE colors_db;
        mysql> use colors_db;
        mysql> source /var/www/html/colors-lamp/database.sql;
1. Deploy to Server
    Place the project folder in your server's root directory (/var/www/html)
1. Access the App
    Navigate to `http://your_server_ip/colors-lamp/public/index.html`.

## Run
Index Page: The primary entry point for the application.\
Color Page: Used for color management tasks as designed in the lab sessions.

## Assumptions, Limitations, or AI Usage (as per class policy)
**Assumptions:** The server has the mysqli extension enabled for PHP.

    Requires a functioning MySQL 8.0+ instance.

**Limitations:** Designed for educational purposes as a single-user demonstration.

**AI Usage:** Used AI to write down the SET-UP instructions in README.md
