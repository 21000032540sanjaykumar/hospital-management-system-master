
# JAVA FULLSTACK PROJECT BASED ON HOSPITAL MANAGEMENT SYSTEM 

This Hospital Management System exemplifies a Java full-stack application, demonstrating the power of modern web technologies for healthcare administration. The frontend, developed using HTML, CSS, and JavaScript, ensures a responsive and intuitive user interface. The backend, built on the Spring framework, provides a robust and scalable foundation for handling diverse functionalities.

The system is structured around four key modules: Admin, Doctor, Pharmacist, and Receptionist. Each module is tailored to address the specific needs of the corresponding roles within a healthcare facility. The MySQL database serves as a secure and efficient repository for managing and retrieving data.

By adopting a full-stack Java approach, this project exemplifies best practices in software development, offering a scalable, maintainable, and user-friendly solution for hospital management. Whether it's streamlining administrative tasks or enhancing patient care, this system contributes to the overall efficiency and effectiveness of healthcare operations.


# Hospital Management System (HMS) Web Application Configuration Guide

This guide will walk you through the steps to configure and set up the Hospital Management System (HMS) Java full-stack web application on your system. Follow these instructions to ensure a smooth installation process.

### Prerequisites
1.Eclipse for Java EE Developers and Tomcat Server:

1.1 Download and install Eclipse for Java EE Developers from https://eclipseide.org/.

1.2 Install and set up the Tomcat server. You can follow the instructions provided in the Eclipse documentation.

2.MySQL Workbench:

2.1 Download and install MySQL Workbench from https://dev.mysql.com/downloads/workbench/.


3.Clone or Download the Project:

Clone or download the HMS project from the GitHub repository. You can find the repository here.

## Project Setup
1. Import Project in Eclipse:
1.1 Launch Eclipse and select the 'import existing maven project' option.

1.2 Navigate to the location where you cloned or downloaded the project and select it.

1.3 Follow the prompts to import the project into Eclipse.

2. Configure Database:

2.1 In MySQL Workbench, create a new schema named hospital_management.

2.2 Update the database login and password in the application.properties file in the project.

2.3 Locate the application.properties file in the project's resources folder.

2.4 Modify the spring.datasource.username and spring.datasource.password properties with your MySQL database credentials.

3. Run the Application:

Right-click on the project in Eclipse.
Choose 'Run as' and select 'Spring Boot App' to start the web application.

4. Access the Application:

Once the application is running, open a web browser and navigate to http://localhost:8080/ to access the Hospital Management System.

## Additional Information
** For additional configuration options or troubleshooting, refer to the project documentation or search online for specific queries.

** Make sure your system meets the minimum requirements specified in the project documentation.

** If you encounter any issues during the setup process, check the project's GitHub repository for known issues or contact the project maintainers for support.

