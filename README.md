# SemiGoogleSheetsProject
A spreadsheet-like application with limited features, inspired by Google Sheets. The application is implemented in Java, featuring a backend hosted on Tomcat, which provides APIs for data processing and storage. The user interface is developed using a JavaFX desktop client.

A detailed documentation of the project's technical specifications and features is available here:

[ReadmeForProject](readmeForProject.pdf)

Here is the updated and copyable version of the instructions with the added detail about extracting the JavaFX SDK to the same directory as the `project_code` folder:


**Program Activation Instructions:**

1. **Download and extract the project code ZIP file.**
   
2. **Download and install Tomcat.** Ensure Tomcat is properly installed on your system.
   
3. **Download and set up JavaFX:**
   
   - Download the **JavaFX SDK version 22.0.2** from the official website.
     
   - Extract the downloaded JavaFX SDK to the same directory where you extracted the `project_code` folder.
     
4. **Deploy the application:**
   
   - Locate the `ex3.war` file in the extracted `project_code` folder.
     
   - Copy and paste the `ex3.war` file into the `webapps` folder in your Tomcat installation directory.
    
5. **Start the Tomcat server:**
   
   - Navigate to the `bin` folder in your Tomcat installation directory.
   
   - Run the `startup.bat` file to start the Tomcat server.
     
6. **Run the client application:**
   
   - Navigate to the extracted `project_code` folder.
     
   - Ensure the path to the JavaFX libraries is included in your system environment or the run script (if not already configured).
     
   - Run the `run.bat` file to start the JavaFX client application.  
