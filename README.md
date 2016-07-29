# Credit-Card-Application


- the database schema was exported via MySQL Workbench

- the database connection details set up in the project are:

  jdbc.driverClassName=com.mysql.cj.jdbc.Driver
  jdbc.url=jdbc:mysql://localhost:3306/creditcardapp
  jdbc.username=root
  jdbc.password=1234

  To change them, please access file /projectDB/src/main/resources/jdbc.properties

- in order to display the credit card requests and to be able to update their status it is necessary to insert on the database in tables
USERS and AUTHORITIES an user that has the role "ROLE_BACKOFFICE".
