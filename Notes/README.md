Notes Project Using Spring Boot And React
===============================

This is a simple web application that allows users to create and manage their notes. It is built using Spring Boot as the backend and React as the frontend.
Getting Started
---------------

### Prerequisites

-   Java 17 or higher
-   Node.js and npm
-   MySQL


### Installation

1.  Clone the repository:
        https://github.com/SimonEdnz/NotesApp.git
2.  Configure the database:

    Create a new MySQL database and update the configuration in `src/main/resources/application.properties`:

    ```bash

    spring.datasource.url=jdbc:mysql://localhost:3306/Notes/your-database-name
    spring.datasource.username=your-database-username
    spring.datasource.password=your-database-password
    ```

3.  Build the backend:

    cd server/Notes
    mvn clean install

4.  Run the backend:

    java -jar target/Notes-0.0.1-SNAPSHOT.jar
 

5.  Install frontend dependencies:

    cd client
    npm install

6.  Run the frontend:

    npm start

7.  Access the application:

    Open [http://localhost:3000](http://localhost:3000/) in your web browser.

Usage
-----

-   The homepage shows a list of notes.
-   Click the "New Note" button to create a new note.
-   Click the title of a note to view or edit its contents.
-   Click the "Delete" button to delete a note.
