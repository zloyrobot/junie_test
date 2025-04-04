# Java Hello World

[![Java](https://img.shields.io/badge/Java-8%2B-blue.svg)](https://www.oracle.com/java/technologies/javase-downloads.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple Java application that displays "Hello, World!" in the console.

## Description

This is a basic Java project built using Gradle. It serves as a template or starting point for Java development. The project demonstrates:

- Basic Java application structure
- Gradle build system configuration
- JUnit 5 test setup

## Features

- Simple console output
- Gradle build configuration
- JUnit 5 testing framework integration
- Cross-platform compatibility

## Requirements

- Java Development Kit (JDK) 8 or higher
- Gradle (or use the included Gradle wrapper)

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/java-hello-world.git
cd java-hello-world
```

## Building the Project

Build the project using the Gradle wrapper:

```bash
# For Linux/macOS
./gradlew build

# For Windows
gradlew.bat build
```

## Running the Application

To run the application, first build the project and then run the compiled Java class:

```bash
# Build the project
./gradlew build

# Run the application (Linux/macOS)
java -cp build/classes/java/main org.example.Main

# Run the application (Windows)
java -cp build\classes\java\main org.example.Main
```

You can also run the application directly with Gradle:

```bash
# For Linux/macOS
./gradlew run

# For Windows
gradlew.bat run
```

## Testing

The project is configured to test using JUnit 5. Run the tests with the following command:

```bash
# For Linux/macOS
./gradlew test

# For Windows
gradlew.bat test
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

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## Author

Your Name - [your.email@example.com](mailto:your.email@example.com)

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2023 Your Name

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
