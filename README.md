# BUS 18 - Fall 2022 #

### What is this repository for? ###

* Class DB Files

### How to Import the Class DB Files ###

* Click on the Cloud9 Terminal (feel free to make it larger)
+ Run the following commands in the terminal: 
    * sudo service mysql start
    * mysql -uroot
    * source createdb.sql
    * use sampdb;
    * source init_all_tables.sql

---
# Install Locally (Windows)
## Required
- [Git](https://git-scm.com/download/win)
- [MySQL](https://dev.mysql.com/downloads/installer/) (And set your PATH environment to `C:\Program Files\MySQL\MySQL Server 8.0\bin`, or where MySQL Server is installed. MySQL.exe MUST be at the path `C:\Program Files\MySQL\MySQL Server 8.0\bin\MySQL.exe`).

## Setup
1. Find a place for your files, then copy the file path.
2. Open PowerShell and `cd 'C:\your\path\to\your\folder\in\single\quotes'`
3. Clone this repository: `git clone https://github.com/sathrum/bus18`
4. Open MySQL: `mysql.exe -u root -p`
   - You will need the password that you set during the MySQL installation.
5. Create the Database: `source createdb.sql`
6. Use the database: `USE sampdb`
7. Import the Data: `source init_all_tables.sql`
You're good to go!
