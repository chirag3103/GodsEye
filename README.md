GodsEye application

Database setUp:
     MySql: login as root user and perform the following steps:
         1. create database godseye_db;
         2. create user 'godseye_user1'@'localhost' identified by 'godseye_user1';
         3. grant all privileges on godseye_db.* to 'godseye_user1'@'localhost';
         4. flush privileges;
 
Start the GodsEyeApplication, it will launch the application on tomcat at localhost:8480.