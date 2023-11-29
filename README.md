# ST10165867-PROG6212-PART3
# Student Time Management System

## Table of Contents
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Key Features and Functionality](#key-features-and-functionality)
  - [Technologies and Frameworks Used](#technologies-and-frameworks-used)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Configuration](#configuration)
  

## Description
<br>The Student Time Management System Application is a desktop application developed in C# and ASP.NET Web Application(.NET Framework). This tool is designed to help students and individuals manage their time efficiently during an academic semester. Study hours are tracked and organized for each module in a semester, ensuring that users can allocate their study time effectively.<br>

## Key Features and Functionality<br>

<li>User Registration: The user is able to register their account if their first time users. They registered all their details which are saved in a database. The software shall stores the hash of the password in the database to secure the users data</li>
</ul>

<li>User Login: The application uses a login feature whereby the user enters their username and their password in order to be able to login. If they forget their password they can recover it.</li>

<ul><li>Module Management: Users can add multiple modules for the semester, providing essential details for each module, including code, name, number of credits, and class hours per week.</li>

<li>Semester Configuration: Users can specify the number of weeks in the semester and set a start date for the first week.</li>

<li>Self-Study Calculation: The application calculates and displays the number of hours of self-study required for each module per week. This calculation is based on the number of credits a module has and the total number of weeks in the semester, taking into account class hours per week.</li>

<li>Hour Recording: Users can record the number of hours they spend working on a specific module on a specific date. This feature allows for accurate tracking of study hours.</li>

<li>Self-Study Tracking: The application keeps track of the remaining self-study hours for each module for the current week. This calculation considers the hours already recorded on days during the current week, ensuring users stay on top of their study goals.</li>

<li>Data Storage: User data is stored in memory while the software is running, ensuring privacy and data security. The application does not persist user data between runs, which means that data is only available during the current session.</li>

<br>The Time Management Desktop Application offers an intuitive and user-friendly interface for managing study hours and ensuring effective time management during an academic semester.


## Technologies and Frameworks Used 
<br>
1. C#:The primary programming language for application logic.<br>
2. ASP.NET Web Application (.NET Framework): Used for creating the desktop user interface.<br>
3. .NET Framework: Provides essential libraries and tools for Windows desktop application development.<br>
4. Visual Studio 2022: The integrated development environment (IDE) for C# and ASP.NET application development.<br>
5. SQL Server Management Studio Management: Used for creating or uploading database.<br>


## Prerequisites
<br>
1. As the application uses Windows Presentation Foundation (WPF), you must have a Windows operating system (Windows 7 or later).<br>
2. It is necessary to have a development environment that supports C# and WPF. Microsoft Visual Studio is recommended for development.<br>

## Installation
<br>
<ul>
<li>Download zip file</li>
<li>Open zip file and choose 'Extract to'
<li>Save the application on the 'repos' folder</li>
<li>Open the 'UserRegistration' folder</li>
<li>Open the file 'UserRegistration.sln' Microsoft Visual Studio 2022</li>
<li>Go to the folder called 'Database'</li>
<li>Run the script files 'LoginUser' and 'Modules' in SQL Sever Management</li>
<li>Go to Visual Studion and 'Connect to a database' </li>
<li>Run the code</li>
<br>
</ul>

## Configuration
<br>
Find a bug?<br>
If you found an issue or would like to submit an improvement to this project please submit an issue using the issues tab above.
<br><br>
<br>
This application is still has been completed. For any queries contact the github link below

<br><br>
<h4>Created by: ST10165867 Sukoluhle Ndlovu</h4>
<br> Github link: https://github.com/ST10165867/ST10165867-PROG6212-PART3
