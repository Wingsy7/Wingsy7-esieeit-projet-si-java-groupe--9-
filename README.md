# Project SI Java

Course repository for a Java backend project prepared with a clean Gradle setup and an initial testing scaffold.

This repository is not a finished product yet. It currently shows the project foundation and the development workflow that will support the next iterations.

## Current Status

The repository already contains:

- a Gradle wrapper and build configuration
- a Java 21 toolchain setup
- an application entry point
- a JUnit 5 test scaffold
- a project backlog in `BACKLOG.md`

## Goals

- build a clean backend structure
- practice collaborative Git workflow
- prepare controller, service and repository layering
- add automated tests and clearer technical documentation

## Tech Stack

- Java 21
- Gradle
- JUnit 5

## Repository Structure

- `app/src/main/java/com/esieeit/projetsi/App.java`: current entry point
- `app/src/test/java/com/esieeit/projetsi/AppTest.java`: test scaffold
- `BACKLOG.md`: project backlog and next steps

## Run Locally

```bash
./gradlew test
./gradlew run
```

## Why Keep This Repository Public

Even at an early stage, it shows useful engineering habits:

- project bootstrapping with Gradle
- versioned backlog and documentation
- test-first project setup
- preparation for a more structured backend architecture
