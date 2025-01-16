# File-Service
Description
This project is a File Upload and Download Service that allows users to upload and download the uploaded file. 

Features
Uploads the file like pdf and images.
Delete the uploaded file.
Technologies Used
Java (Spring Boot Framework)
MySQL Database
Prerequisites
Before you begin, ensure you have the following installed on your system:

Java Development Kit (JDK) 8 or higher
MySQL Server
Apache Maven
Apache Tomcat Server
An IDE such as Eclipse or IntelliJ IDEA
Local Setup
Follow these steps to set up the project locally:

Clone the Repository:

Open your terminal or command prompt.
Clone this repository using the following command: bash git clone https:https://github.com/nikamatharv/File-Service
Navigate to the Project Directory:

Change your working directory to the project folder: bash cd file service
Set Up the Database:

Start your MySQL server
Log in to MySQL and create the required database bash CREATE DATABASE filedb;
Open the Project in Eclipse or IntelliJ IDEA:

For Eclipse:

Open Eclipse.
Click on File > Import > Existing Maven Projects.
Browse to the project directory and select it.
Click Finish to load the project.
For IntelliJ IDEA:

Open IntelliJ IDEA.
Click on Open and select the project directory.
IntelliJ will automatically detect the Maven project and import it.
Update the application.properties file in the src/main/resources directory with your MySQL credentials::

 spring.datasource.url=jdbc:mysql://localhost:3306/filedb  
 spring.datasource.username=<your-username>  
 spring.datasource.password=<your-password>
Run the application:

For Eclipse: Navigate to the src/main/java/com.colan/FileServiceApplication.java, right-click > Run As > Java Application.
For IntelliJ IDEA: Navigate to the FileServiceApplication class, right-click > Run 'FileServiceApplication'.
The backend server will start at http://localhost:8080
Set Up the Frontend:

Ensure the script.js file and other frontend files are located in the src/main/resources/static directory.
Access the frontend in your browser at http://localhost:8080
Test the Features:

