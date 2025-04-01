# Java Hello World

A simple Java application that displays "Hello, World!" in the console.

## Description

This is a basic Java project built using Gradle. It serves as a template or starting point for Java development.

## Requirements

- Java Development Kit (JDK) 8 or higher
- Gradle (or use the included Gradle wrapper)

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone [repository-url]
cd [project-directory]
```

## Building the Project

Build the project using the Gradle wrapper:

```bash
./gradlew build
```

For Windows:

```bash
gradlew.bat build
```

## Running the Application

To run the application, first build the project and then run the compiled Java class:

```bash
# Build the project
./gradlew build

# Run the application
java -cp build/classes/java/main org.example.Main
```

For Windows:
```bash
# Build the project
gradlew.bat build

# Run the application
java -cp build\classes\java\main org.example.Main
```

## Testing

The project is configured to test using JUnit 5. Run the tests with the following command:

```bash
./gradlew test
```

## Project Structure

```
.
├── build.gradle.kts        # Gradle build configuration
├── settings.gradle.kts     # Gradle settings
├── src
│   └── main
│       └── java
│           └── org
│               └── example
│                   └── Main.java  # Application main class
└── README.md               # This file
```

## Dependencies

- JUnit 5 (for testing)

## License

[Insert license here]
