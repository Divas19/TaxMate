# TaxMate

This ⁠ Java Swing ⁠ application calculates income tax based on user input.  It leverages a ⁠ SQL database ⁠ for data persistence and offers a user-friendly interface.

## Tech Stack

•⁠  ⁠⁠ Java ⁠ Programming Language 
•⁠  ⁠⁠ IntelliJ ⁠ (IDE)
•⁠  ⁠⁠ Java Swing ⁠ (GUI Development) 
•⁠  ⁠⁠ MySQL Database ⁠


## Screenshots

![Home_Page](https://github.com/AyushRawat1718/TaxMate/assets/143322694/174a9f01-cc21-4a22-ad0c-71353f26ed79)

![Signup_Page](https://github.com/user-attachments/assets/6d6ef889-352b-42d5-86c4-8db0cbda0a68)

![Profile_Page](https://github.com/user-attachments/assets/69e3ce9f-b5ac-4488-901c-b616bf55ad72)

![Calculation_Page_1](https://github.com/AyushRawat1718/TaxMate/assets/143322694/6b3f0b2b-c93e-4fdf-8153-a864f182474e)

![Calculation_Page_2](https://github.com/user-attachments/assets/f358ecd7-f765-4d84-83ed-e5b1ca8d4288)

![Version_Page](https://github.com/AyushRawat1718/TaxMate/assets/143322694/dc200734-b49c-444e-8912-11888edd2749)

## Installation

•⁠  ⁠*Clone the Repository*

⁠ bash
  git clone https://github.com/AyushRawat1718/TaxMate.git
 ⁠

•⁠  ⁠*Install JAVA*
  
    [JAVA](https://www.oracle.com/in/java/technologies/downloads/)
  
•⁠  ⁠*Set Up Database Connection*

    - Install and setup the [MySQL](https://dev.mysql.com/downloads/installer/) 
    - After setting up database, use the following code for creating the required ⁠ TaxMate_Database ⁠
    ⁠ sql
    create database TaxMate_Database; 
    use TaxMate_Database;
    create table User_All_Info
    (
    FirstName varchar(25) Not null,
    MiddleName varchar(25) Not null,
    LastName varchar(25) Not null,
    PanNumber varchar(20) Primary key,
    DateOfBirth varchar(15) Not null,
    ContactNumber varchar(15) Not null,
    Gender varchar(10) Not null
    );
     ⁠
    - Update the ⁠ username ⁠ and ⁠ password ⁠ in all the  java files.
    ⁠ java
    String url = "jdbc:mysql://localhost:3306/TaxMate_Database";
    String username = "YOUR_USERNAME";
    String Password = "YOUR_PASSWORD" ;
     ⁠ 

    - Make sure to install and configure the [mysql-connector-j](https://dev.mysql.com/downloads/connector/j/)

•⁠  ⁠*Update Images Path*
    - In Home_Page.java file  
    
⁠     II_HP_01 = new ImageIcon("Path_To_Image\\Home_BackGround.png";
     ⁠

    - In Profile_Page.java file
    
⁠     II_PP_01 = new ImageIcon("Path_To_Image\\Male_Logo.png");
