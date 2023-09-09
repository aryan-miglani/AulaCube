Prerequisites:

Clone my repo 

Open the application.properties file located in src/main/resources directory and update the following properties with your PostgreSQL database details:
spring.datasource.url=jdbc:postgresql://localhost:5432/<database-name>

spring.datasource.username=yourUsername

spring.datasource.password=yourPassword

Build the project using Maven:
mvn clean install

Run the project using Maven:
mvn spring-boot:run

The API should now be running on http://localhost:8080. You can test the API using any REST client like Postman.
API Endpoints:

GET /tasks - Fetch all tasks.

POST /tasks - Create a new task.

PUT /tasks/{id} - Update the status of an existing task.

That's it! You have successfully run the Simple RESTful API created using Java Spring.