# Backend Code Coverage Example

## Overview

This project is designed to demonstrate the collection of backend code coverage using Jacoco after executing end-to-end (E2E) tests. The project is built using the Micronaut framework and Gradle as the build system. Jacoco is used to instrument the code and generate a coverage report based on the E2E tests.

## Prerequisites

Ensure you have the following installed:

- **Java Development Kit (JDK):** 17
- **Gradle:** 7.x (or use the Gradle wrapper included in the project)

## Collect backend code coverage after E2E tests execution

1. Clone the repository:

    ```bash
    git clone https://github.com/Azzee-efil/Backend-Code-Coverage-Example.git
    cd backend-code-coverage-example
    ```

2. Build the project:

    ```bash
    ./gradlew build
    ```

3. Run the instrumented application:

    ```bash
    ./gradlew runInstrumented
    ```

4. Interact with the UI


5. Generate the Jacoco code coverage report:

    ```bash
    ./gradlew jacocoTestReport
    ```

## Code Coverage

The Jacoco coverage report will be generated in both HTML and XML formats. You can find the HTML report in the following location:

```plaintext
build/jacocoHtml/index.html
```

## Example Coverage Report

You can view an example of the generated coverage report [here](https://azzee-efil.github.io/Backend-Code-Coverage-Example/coverage_report_example/index.html).