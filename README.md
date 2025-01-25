# Employee Management System (EMS)

Basically this project is small crud no-auth desktop application with rare combination of Spring Boot and JavaFx. 

![EMS Screenshot](https://github.com/user-attachments/assets/e3e49e03-ef0a-4f39-af66-2d7ebc9d3a23)

## Features
- Supports all kinds of employee records managing
- Simple UI
- Simple localizaton mechanic (two lang support through all text components)
- PopUps disappearing when out of your focus

## Technologies
- Java 21.0.5
- JavaFX 21.0.5
- Spring Boot 3.3.5
- PostgreSql 46.6.2
- Mapstruct 1.6.3
- Lombok 1.18.34
- JUnit 5.9.0
- JUnit-FX 4.0.18
- Layered Architecture
- DTO
- Unit testing
- IT testing

## Installation
### 1. Clone repository:
   ```bash
   git clone https://github.com/Dev1Art/ems.git
   ```
### 2. Import into IDE (Eclipse/IntelliJ) as Maven project (opt. cause you can launch via first method below)
### 3. Database Setup: 
You need to set up your own db working on your machine (localhost:5432). You can use PgAdmin4 for example.
### 4. Build and run:
#### First method: (No IDE)
```
mvn clean javafx:run
```
#### Second method (In IDE)
You need to set up JVM args to run this. In your launching config add:
```
java --module-path PATH/TO/YOUR/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml,javafx.graphics -jar target/ems-1.0-SNAPSHOT.jar
```
## License - MIT 
