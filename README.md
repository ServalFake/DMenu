# Fullstack Game App

This project is a fullstack game application that integrates a Vite + React frontend with a Spring Boot Java backend. The application allows users to select difficulty modes for the game.

## Project Structure

- **frontend/**: Contains the React application.

  - **src/**: Source files for the React app.
    - **components/**: React components.
      - **DifficultySelector.jsx**: Component for selecting difficulty modes.
    - **services/**: API service files.
      - **apiService.js**: Functions for making API requests to the backend.
    - **App.jsx**: Main application component.
    - **main.jsx**: Entry point for the React application.
  - **index.html**: Main HTML file for the React app.
  - **package.json**: Configuration file for npm.
  - **vite.config.js**: Configuration file for Vite.

- **backend/**: Contains the Spring Boot application.
  - **src/**: Source files for the Spring Boot app.
    - **main/**: Main application files.
      - **java/**: Java source files.
        - **com/game/**: Package for the game application.
          - **controller/**: Controllers for handling requests.
            - **DifficultyController.java**: Handles difficulty mode requests.
          - **model/**: Model classes.
            - **Difficulty.java**: Represents a difficulty mode.
          - **GameApplication.java**: Entry point for the Spring Boot application.
      - **resources/**: Resource files.
        - **application.properties**: Configuration properties for the Spring Boot app.
    - **test/**: Test files for the application.
  - **pom.xml**: Configuration file for Maven.
  - **mvnw**: Maven wrapper script.

## Getting Started

- **backend/**:
  - cd difficultyMenu/sudoku-app/backend
    ./mvnw spring-boot:run
- run ./mvnw spring-boot: run

- **frontend/**:
  - cd difficultyMenu/sudoku-app/frontend
    npm run dev
