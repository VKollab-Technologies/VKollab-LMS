# VKollab LMS - Setup Guide

## Prerequisites

- XAMPP (Apache & MySQL)
- PHP
- MariaDB/MySQL
- Git

## Repository

Clone the repository:

https://github.com/VKollab-Technologies/VKollab-LMS

## Setup Steps

### 1. Clone Repository

Place the project in:

C:\xampp\htdocs\moodle

### 2. Create Database

Open phpMyAdmin and create a database:

moodle

### 3. Import Database

Import the file:

database/moodle.sql

### 4. Moodle Data Folder

Extract:

moodledata.zip

to:

C:\xampp\moodledata

### 5. Config File

Copy the provided:

config.php

to:

C:\xampp\htdocs\moodle

### 6. Start Services

Start:

- Apache
- MySQL

from XAMPP Control Panel.

### 7. Launch Application

Open:

http://localhost/moodle

### 8. Login

Use the existing administrator account credentials provided separately.

## Important Notes

Current Configuration:

Database Name: moodle

Default Moodle URL:
http://localhost/moodle

Default Moodle Data Directory:
C:\xampp\moodledata

If the application is installed in a different location, update:

- config.php
- $CFG->wwwroot
- $CFG->dataroot
- Database credentials

accordingly.
