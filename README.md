# Java Hello World

A simple Java application that displays "Hello, World!" in the console. This project demonstrates the basic structure of a Java application and serves as a starting point for Java development.

## Description

This is a basic Java project built using Gradle. It prints the classic "Hello, World!" message to the console when executed. The project is structured according to modern Java conventions and uses the Gradle build system for dependency management and build automation.

## Requirements

- Java Development Kit (JDK) 8 or higher
- Gradle (or use the included Gradle wrapper - recommended)

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/java-hello-world.git
cd java-hello-world
```

No additional installation steps are required as the project includes a Gradle wrapper.

## Gradle Wrapper

This project includes a Gradle wrapper, which means you don't need to install Gradle separately. The wrapper is a script that invokes a declared version of Gradle, downloading it if necessary. This ensures that the build uses the correct Gradle version regardless of what's installed on the developer machine.

## Building the Project

Build the project using the Gradle wrapper:

```bash
# For Unix/Linux/macOS
./gradlew build

# For Windows
gradlew.bat build
```

## Running the Application

To run the application, you can use the Gradle `run` task or execute the compiled Java class directly:

### Using Gradle (recommended)

```bash
# For Unix/Linux/macOS
./gradlew run

# For Windows
gradlew.bat run
```

### Executing the compiled class

```bash
# For Unix/Linux/macOS
# Build the project first
./gradlew build

# Run the application
java -cp build/classes/java/main org.example.Main

# For Windows
# Build the project first
gradlew.bat build

# Run the application
java -cp build\classes\java\main org.example.Main
```

## Testing

The project is configured to use JUnit 5 for testing. Run the tests with the following command:

```bash
# For Unix/Linux/macOS
./gradlew test

# For Windows
gradlew.bat test
```

## Project Structure

```
.
├── build.gradle.kts        # Gradle build configuration
├── settings.gradle.kts     # Gradle settings
├── gradle/wrapper/         # Gradle wrapper files
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

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

Please make sure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to all contributors who have helped improve this project
- The Java community for providing excellent documentation and resources
