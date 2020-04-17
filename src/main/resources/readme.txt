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

CREATE TABLE EMPLOYEE
(
    ID          INT PRIMARY KEY AUTO_INCREMENT,
    FIRSTNAME   VARCHAR(30),
    LASTNAME    VARCHAR(30),
    TELEPHONE   VARCHAR(15),
    EMAIL       VARCHAR(30),
    CREATED     TIMESTAMP DEFAULT NOW()
);

Tomcat deployment :
------------------
http://localhost:8080/Spring3Struts2HibernateIntegration/list