WEb Site :
----------
https://howtodoinjava.com/struts2/spring-4-struts-2-hibernate-integration-tutorial/#Integration_Overview


Database Queries
-------------------
https://study.com/academy/lesson/mysql-commands-list-examples.html

MySQL
root 
password
CREATE DATABASE test;
Use test;
to change password in mysql
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'yourpassword';



create database mydemodb;
use mydemodb;
CREATE TABLE EMPLOYEE
(
    ID          INT PRIMARY KEY AUTO_INCREMENT,
    FIRSTNAME   VARCHAR(30),
    LASTNAME    VARCHAR(30),
    TELEPHONE   VARCHAR(15),
    EMAIL       VARCHAR(30),
    CREATED     TIMESTAMP DEFAULT NOW()
);
show tables;

Tomcat deployment :
------------------
http://localhost:8080/Spring3Struts2HibernateIntegration/list

Azure deployment
-----
https://azuredevopslabs.com/labs/vstsextend/tomcat/
1) create RG
2) create Service plan
3) create mysql database and allow app service connection, firewall ip
4) create web app and set configuration to use tomcat 
5) use eclipse azure toolkit deploy application

Tomcat connection string
----
jdbc:mysql://demosachinmysqldb.mysql.database.azure.com:3306/mydemodb?useSSL=true&requireSSL=false&autoReconnect=true&useTimezone=true&serverTimezone=UTCuser=mysqluser@demosachinmysqldb&password=password@123

Java properties
----
jdbc.databaseurl=jdbc:mysql://demosachinmysqldb.mysql.database.azure.com:3306/mydemodb?useSSL=true&requireSSL=false&characterEncoding=utf8&useTimezone=true&serverTimezone=UTC
jdbc.username=mysqluser@demosachinmysqldb
jdbc.password=password@123