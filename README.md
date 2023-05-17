## RCDS - Java Web Application
## Description

This is a mock README.md file for the rcds repository, given the sensitive nature of the actual code. 

RCDS is a Java web application that utilizes various technologies to create a robust and scalable system. It incorporates HTML, CSS, JavaScript, JQuery, AJAX, Spring, Hibernate, Apache Maven, Apache Derby, Apache Tomcat, and JUnit. The application aims to provide a flexible and user-friendly interface for managing and organizing tuition calculations of families whose children attend the Risen Christ School.

## Table of Contents

    Features
    Technologies
    Installation
    Usage
    Contributing

## Features

    Tuition calculator page for users or administrators to compute their expected tution and show their resulting discount.
    Allows input for household income, family size, students attending, faculty checks and comment box for exigent circumstances.
    Rates page for adminsitrators to adjust individual tuition rates for each school year.
    User page containing lists of pending and approved calculations. Admin ability aprove tuition requests, all users may delete pending calculations and restart given a change in circumstances. 
    Bilingual functionality for both English and Spanish for all web pages. 
    Email approval notifications for users and faculty for approvals and changes. 

## Languages

The following programming languages, server-side tools, and development applications are used in the RCDS application:

    HTML
    CSS
    JavaScript
    JQuery
    AJAX
    Spring
    Hibernate
    Apache Maven
    Apache Derby
    Apache Tomcat
    JUnit

## Installation

Clone the repository:

    git clone https://github.com/RWThompson7/rcds.git

Change into the project directory:

    cd rcds

Build the project using Apache Maven:

    mvn clean install

Deploy the generated WAR file to Apache Tomcat:

Replace path/to/tomcat with the path to your Apache Tomcat installation.

    cp target/rcds.war path/to/tomcat/webapps

Start Apache Tomcat:

    path/to/tomcat/bin/startup.sh

## Usage

Start your web browser and navigate to http://localhost:8080/rcds.
When starting for the first time, navigate to http://localhost:8080/rcds/user/add to create a new user account, then sign in with your email and password. 

## Contributing

Contributions to RCDS are welcome! If you would like to contribute, please follow these steps:

Fork the repository.
Create a new branch:

    git checkout -b feature/your-feature-name

Make your changes and commit them:

    git commit -m 'Add some feature'

Push to the branch:

    git push origin feature/your-feature-name

Create a pull request.

## About the Team
This project was developed by a team of developers including:

    Ryan Thompson
    Tucker Johnson
    David Braun
    Owen Hiskey
