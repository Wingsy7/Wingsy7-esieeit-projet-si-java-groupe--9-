# Project SI Java

![Status](https://img.shields.io/badge/status-in%20progress-yellow)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit%205-25A162?style=flat&logo=junit5&logoColor=white)

Java backend project scaffold prepared with Gradle, Java 21 and JUnit 5.
This repository currently focuses on clean project setup, test readiness and the initial structure for a layered backend application.

## Current Scope

- Gradle wrapper and build configuration
- Java 21 toolchain setup
- Application entry point
- JUnit 5 test scaffold
- Backlog file to track project evolution

## Tech Stack

| Technology | Usage |
|---|---|
| Java 21 | Application language |
| Gradle | Build automation |
| JUnit 5 | Test scaffold |
| Git | Version control |

## Goals

- Build a cleaner backend architecture
- Practice layered project organization
- Add more business logic and tests
- Improve documentation and maintainability

## Run Locally

```bash
# Run tests
./gradlew test

# Run the application
./gradlew run
```

## Repository Structure

```text
project/
├── app/
│   ├── src/main/java/com/esieeit/projetsi/App.java
│   └── src/test/java/com/esieeit/projetsi/AppTest.java
├── BACKLOG.md
├── gradlew
├── settings.gradle
└── README.md
```

## Why This Repository Matters

Even in its current state, this project shows useful engineering habits:

- reproducible Java setup
- test-oriented initialization
- clean build tooling
- preparation for a more structured backend project

## Author

**Miroslav**  
GitHub: [Wingsy7](https://github.com/Wingsy7)
