# SpringBootProject
Smart contact manager project is used to save update and delete contact from contact list. The project is designed in java using spring boot framework.

Prerequesties  :

# 
1-Eclipse (download it from official website https://www.eclipse.org/)
# 
2-Java Devlopment kit (download it from offical website https://www.oracle.com/in/java/technologies/downloads/)
# 
3-MySql database (download it from offical website https://dev.mysql.com/downloads/mysql/)
# 
4-Spring Tool suite (Download it from official website https://spring.io/tools)


# Start creating our project in eclipse
# 
First step -> file ->new -> Spring starter Project -> 
# 
Select Java version that required for the project , Type of project maven or gradle as per your choise , Packaging war or jar (war packaging is used to develop web apploications and jar is used to create standalone application in spring starter project )
#
Create GroupId, Artifact ,and package name for your project.

# Project Dependencies that is required to create new Project :
#
1- Spring starter-web
#
2- Spring starter-thymleaf
#
3- Spring data-Jpa
#
4- spring starter-security
#
5- Spring- boot-devtools
#
6- mysql-connector-java
#
7- validation-api
#
8- Hibernate validation
#
9- tomcat-embeded-jasper


#DataBase configuration
#
Database configuration is done in spring boot inside application.proiperties file where we wil use some properties key of database and values for connecting our database to project
#
spring.datasource.url=url_of_your_database
#
spring.datasource.username=Username_of_your_database
#
spring.datasource.password=paswword_of_your_database
#
spring.datasource.driver-class-name=your_driver_class_name

#Hibernate configuration of table auto-creation and updation
#
spring.jpa.properties.hibernate.dialect=dialect_name
spring.jpa.show_sql=true/false
spring.jpa.hibernate.ddl-auto=create/update/drop-create

