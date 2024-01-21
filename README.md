# TP3_JSF_Employe_Service

Web Application for Employee and Service Management
This JavaServer Faces (JSF) web application, integrated with Hibernate, is designed to handle services and employees within a company.

Project Structure
The project is structured into packages for clear organization of the source code.
- "entities" Package
In the "entities" package, you'll find the entities Employee and Service. These entities represent employees and services within the company.
- "services" Package
The "services" package contains the following classes:
a. AbstractFacade: A generic abstract class, AbstractFacade, implementing CRUD (Create, Read, Update, Delete) functionalities for a generic entity T.
b. EmployeeService and ServiceService: Two classes, EmployeeService and ServiceService, inheriting from AbstractFacade to provide specific functionalities for employee and service management.

Web Pages
- Service Management Page
The web page for service management allows users to display, add, edit, and delete services. It uses JSF components to interact with the service layer.
- Employee Addition Page
The web page for adding employees presents a form with necessary information such as name, surname, date of birth, manager, service, and a photo.
- Displaying Collaborators in a Service
A feature is implemented to display collaborators within a service. It indicates the service manager and employees under their responsibility. PrimeFaces components are utilized for an enhanced user interface.

Technologies Used
==> JavaServer Faces (JSF)
==> Hibernate
==> PrimeFaces (for a rich user interface)
==> Database (configured in the Hibernate configuration file)

Execution Instructions
- Ensure that Java, Apache Tomcat (or another JSF-compatible server), and a Hibernate-compatible database are installed on your machine.
- Configure the Hibernate configuration file with the connection parameters for your database.
- Deploy the application to your application server.
- Access the application using the appropriate URL (e.g., http://localhost:8080/jsf7).
- Utilize the different web pages to manage services and employees.


https://github.com/N0ur-edd1ne/TP3_JSF_Employe_Service/assets/117684844/0a228fe1-9f7d-4b7e-850b-dc7916051d2e
