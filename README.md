# Spring4Struts2HibernateIntegration
Java web application using spring 4 struts 2, hibernate, mysql, jsp, tlds, log4j, transaction mgnt and maven to deploy on tomcat server as war file

Reference site :
----------
https://howtodoinjava.com/struts2/spring-4-struts-2-hibernate-integration-tutorial/#Integration_Overview

Database : MySQl
----------
CREATE DATABASE test

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
