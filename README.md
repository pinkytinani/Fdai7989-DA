# Fdai7989-DA
Deployment and Github Setup
Server 1: Database Server

    Database Setup:
        Install the database server of your choice (e.g., MySQL, PostgreSQL).
        Create a new database for your application.
        Set up the necessary tables and schema.

    Database Configuration:
        Update the application.properties or application.yml file in your Spring Boot project to include the database connection details.
        Ensure that the firewall allows connections to the database server on the specified port.

    Database Server Security:
        Configure the database server to allow connections only from the application server's IP address for security.

Server 2: Application Server

    Application Build:
        Build your Spring Boot application using a build tool like Maven or Gradle.
        Package your application into a JAR or WAR file.

    Application Deployment:
        Transfer the built JAR/WAR file to the application server.
        Run the application using the java -jar command or deploy it in a servlet container like Tomcat.

    Application Configuration:
        Update the application.properties or application.yml file on the application server to point to the database server's IP and port.

    Firewall Configuration:
        Configure the firewall on the application server to allow traffic on the specified port used by your Spring Boot application.

    Run the Application:

**ReadME FILE**
Demo
ront End:

    A form with input field for name and phone number and submit button (input)
    A small div or table to display contents from the DB (output)

Backend:

    Takes data from frontend and send to DB via Backend 
    Takes data from DB and sends to front end via Backend

Database:
    Set up MySQL Workbench or similar
    Display records
    
**Prerequisites**
Azure student portal signin
Maven
Java
Spring Boot
Spring Core
MYSQL Workbench

**Troubleshooting**

Common issues and how to resolve them.
ssh user@your_server_ip
scp /path/to/local/file user@your_server_ip:/path/to/remote/location
ps aux | grep java
tail -f /path/to/your/application.log
sudo ufw allow 80/tcp
sudo nano /etc/ssh/sshd_config
sudo systemctl restart service_name
