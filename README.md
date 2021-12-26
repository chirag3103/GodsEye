GodsEye application

Database SetUp:

    MySql: login as root user and perform the following steps:
         1. create database godseye_db;
         2. create user 'godseye_user1'@'localhost' identified by 'godseye_user1';
         3. grant all privileges on godseye_db.* to 'godseye_user1'@'localhost';
         4. flush privileges;
 
Application startup: 

    Start GodsEyeApplication java class, it will launch the application on tomcat at localhost:8480.