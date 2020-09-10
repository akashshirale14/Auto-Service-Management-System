#README
It is project on Auto Service Management System.
Here you can add,delete,update and read your appointment details for your car service.
The project is built using Java and Spring framwork.

The application follows an MVC architecture.Basically, a web browser request is handled by the controller
which access the database and returns the result.This retreived result is then stored in a model
and then forwarded to display the data on a web page.
Thymeleaf template is used here to display web pages

The database operations are performed by hibernate framework with MySQL database.
The database data is stored in a database table called customer data.


Steps to compile:
Open the project in eclipse and then select maven build.

Steps to run:
Do spring boot:run to run the application

The project runs on web browser with url:localhost:8080/

