# PublicSoft Coding Project - Junior

**About**

This is a simple single-page web application for storing and editing information about entities that offers reading, creation, deletion and editing affordances to the user. The front-end side of the application is built with Vue Js while the back-end is a Spring Boot Rest API that handles the transactions with the database. 
The user may view the respective entries of two different entities (Persons and Suppliers), display information about a single entry in a modal, edit its fields or delete it. Furthermore, the Suppliers entries are displayed in a paginated format enabling the user to traverse the total of the entries five entries at a time. Also, the user may search for a Person by name or email and for a Supplier by company name or VAT number.

### Prerequisites

What things you need to install the software: 

* A Java IDE (e.g. Netbeans IDE)
* MySQL GUI (e.g. MySQL workbench)
* Maven 3.x
* Node.js

## Installation

To install this application, clone this repository to your Desktop. Create an empty database with name: springbootcrud. Then, open this project on your Java IDE and in the file springbootcrud-webapp/src/main/resources/application.properties modify the following properties, depending on your MySQL installation:
* spring.datasource.username=root
* spring.datasource.password=root 
Then run the Application.class file in springbootcrud-webapp module and check your database GUI. Your previously empty database must now contain tables, two of which hold the names person and supplier. That is where the entities’ data will be stored. After creating the database, go to springbootcrud-client folder, open a cmd and execute the following command: npm install. Once the installation of the node dependencies is finished, execute the command npm run dev and in your browser visit the link http://localhost:9000.

## Built With

* Maven - Dependency Management
* Spring boot
* Vue JS
* Node.js
