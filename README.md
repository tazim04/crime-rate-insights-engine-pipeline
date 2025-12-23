# CrimeLens Pipeline

Spring Boot microservice responsible for fetching, normalizing, and persisting
public crime data for the CrimeLens platform.

This service ingests data from the Ottawa Police public API, transforms it into
a normalized domain model, and stores it in a PostGIS-backed PostgreSQL database.

---

## Running the Application

From the project root:
```Bash
mvn sprint-boot:run
```

## Running Tests

Documentation TBD.

## Code Formatging

This project uses **Spotless** with **Google Java Format**.

Format code:
```Bash
mvn spotless:apply
```

Check code:
```Bash
mvn spotless:check
```