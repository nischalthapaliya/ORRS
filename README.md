

Introduction

This is a PHP Project entitled Online Railway Reservation System. 
It is a web-based application that provides an online platform for railway or train station passengers or possible passengers to explore their schedules and reserve a seat. 
This application does not support any payment API and was developed only for educational purposes to give an idea to the IT/CS students and self-taught programmers about how to develop a web application like this. 
The application has a pleasant user interface using Bootstrap Framework and AdminLTE Framework. It is easy to use or user-friendly.

About the Online Railway Reservation System

I developed this project using the following:

XAMPP v3.3.0 as my local webserver that has a PHP Version 8.0.7

        PHP Language
        MySQL Database
        HTML
        CSS
        JavaScript
        jQuery
        Ajax
        Bootstrap
        AdminLTE
        and some other plugins/libraries.

The Simple Online Railway Reservation System has 2 modules which are the Management Side and Public Side. 
The Management Module is the side of the system where the management can manage the system information, schedules, and reservations. 
On this side, the admin user can update also the content pages that are shown on the website such as the 'About' and 'Contact' Information Contents. 
The Public Module serves as the website that can be accessed by visitors or possible passengers. The visitors can read the information about the station, list the schedules, and reserve their seats on their selected schedule. 
The passenger can submit multiple seat reservations at once.

Features

Management Side

    Secure Login and Logout

    Dashboard

        Display Summary

    Manage Trains

        Add New Train
        List All Trains
        Update Train Details
        Delete Train Details

    Manage Schedules

        Add New Daily Schedule
        Add New One-Time Schedule
        List All Daily Schedule
        List All One-Time Schedule
        Update Schedule Details
        Delete Schedule

    Manage Reservation

        List All Reservations
        View Reservations Details
        Print Reservations Details
        Delete Reservations Details

    Manage Inquiries

        List All Inquiries
        View/Read Inquiry Details
        Delete Inquiry Details

    Manage Users list (CRUD)
    Manage Account Details/Credentials
    Manage System Information

Public Side

    Home Page (Displays the Welcome Content)
    Display Railway's Schedules
    Filter Schedule or Search Available Schedule near the entered date and time
    Submit Reservation
    Print Reservation Ticket(s)
    Read About Content
    Send Inquiry


How to Run ??

Requirements

    Download and Install any local web server such as XAMPP/WAMP.
    Download the provided source code zip file. (download button is located below)

Installation/Setup

    Open your XAMPP/WAMP's Control Panel and start Apache and MySQL.
    Extract the downloaded source code zip file.
    If you are using XAMPP, copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory. And If you are using  
    WAMP, paste it into the "www" directory.
    Browse the PHPMyAdmin in a browser. i.e. http://localhost/phpmyadmin
    Create a new database naming orrs_db.
    Import the provided SQL file. The file is known as orrs_db.sql located inside the database folder.
    Browse the Online Railway Reservation System in a browser. i.e. http://localhost/orrs/

Default Admin Access Information

    Username: admin
    Password: admin123
