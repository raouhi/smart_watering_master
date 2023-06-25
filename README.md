# smart_watering_master

To import and run backend and frontend web applications using Spring Tools, follow these steps:

1- Install Spring Tools: Download and install Spring Tools Suite or Spring Tool Suite 4 from the official website (https://spring.io/tools).

2- Import Backend Project (smartwatering_api_lastV): Launch Spring Tools and select "File" from the top menu, then choose "Import." In the Import dialog, expand the "Maven" folder and select "Existing Maven Projects." Click "Next." Browse to the location where your backend project is stored and select the project folder. Ensure that the backend project's pom.xml file is selected, and click "Finish" to import the project.

3- Resolve Dependencies: Spring Tools will automatically resolve and download the necessary dependencies specified in the backend project's pom.xml file. Wait for the dependencies to be downloaded.

4- Run Backend Application: Once the dependencies are resolved, navigate to the main class of your backend application (typically annotated with @SpringBootApplication) in the project structure. Right-click on the main class and select "Run As" > "Spring Boot App" or "Java Application" to start the backend server.

5- Import Frontend Project (smartwateringV2-1): If your frontend application is a separate project, you can import it into Spring Tools as well. Follow a similar process to step 2, but choose the appropriate import option based on your frontend project structure (e.g., "Import Existing Maven/Gradle Projects," "Import Existing Project," etc.).

6- Serve Frontend Application: Depending on your frontend framework (e.g., Angular, React, Vue.js), you may need to serve the frontend application separately. Refer to the documentation of your frontend framework for instructions on serving the application. Typically, this involves running commands like npm install to install dependencies and npm start or a similar command to serve the application.

7- Access Web Application: Once both the backend and frontend applications are running, you can access the web application by opening a web browser and navigating to the appropriate URL. This URL will depend on the server and port configuration specified in the backend application and the frontend application's configuration.
