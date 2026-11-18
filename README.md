# Caterpillar Mining API

Backend project for registering mining equipment units.

## Current milestone

Project setup only: Java 25, Spring Boot 3.5.8, Spring Web and Spring Data JPA. The API will listen on port 8080. Business functionality and MySQL connection configuration will be implemented in subsequent feature branches.

## Build

Set JAVA_HOME to a JDK 25 installation and run:

```powershell
.\mvnw.cmd -Dmaven.test.skip=true clean package
```

The package command verifies compilation and produces an executable JAR. Application startup requires the MySQL configuration planned for the persistence milestone. No H2 fallback is included.

## Project identity

The temporary artifact name is `pc2nrcucodigo` and the temporary root package is `com.caterpillar.platform.ucodigo`. Replace the NRC and student-code placeholders before submission.

Author: pending student full name.

## Branch workflow

- `main`: release history; currently the initial project snapshot.
- `develop`: integration branch.
- `feature/project-setup`: framework and base project configuration.

Feature changes are committed independently before being integrated into develop.
