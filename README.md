# Java Hello World

A simple Java application that prints "Hello, World!" to the console.

## Description

This is a basic Java project built with Gradle. It serves as a template or starting point for Java development.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Gradle (or use the included Gradle wrapper)

## Setup

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

On Windows:

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

On Windows:
```bash
# Build the project
gradlew.bat build

# Run the application
java -cp build\classes\java\main org.example.Main
```

## Testing

The project is configured with JUnit 5 for testing. Run tests with:

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
│                   └── Main.java  # Main application class
└── README.md               # This file
```

## Dependencies

- JUnit 5 (for testing)

## License

[Specify your license here]
