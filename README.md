# Backend Code Coverage Example

## Overview

This project is designed to demonstrate the collection of backend code coverage using Jacoco after executing end-to-end (E2E) tests. The project is built using the Micronaut framework and Gradle as the build system. Jacoco is used to instrument the code and generate a coverage report based on the E2E tests.

## Prerequisites

Ensure you have the following installed:

- **Java Development Kit (JDK):** 17
- **Gradle:** 7.x (or use the Gradle wrapper included in the project)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-repo/backend-code-coverage-example.git
    cd backend-code-coverage-example
    ```

2. Build the project:

    ```bash
    ./gradlew build
    ```

3. Run the application:

    ```bash
    ./gradlew run
    ```

4. Execute end-to-end tests (you may need to adjust this step according to your specific E2E setup):

    ```bash
    ./gradlew test
    ```

5. Generate the Jacoco code coverage report:

    ```bash
    ./gradlew jacocoTestReport
    ```

## Code Coverage

The Jacoco coverage report will be generated in both HTML and XML formats. You can find the HTML report in the following location:

```plaintext
build/reports/jacoco/test/html/index.html