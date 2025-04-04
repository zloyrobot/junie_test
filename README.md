# Java Hello World

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java Version](https://img.shields.io/badge/Java-8%2B-blue)](https://www.oracle.com/java/technologies/javase-downloads.html)
[![Gradle](https://img.shields.io/badge/Gradle-7.x-green)](https://gradle.org/)

A simple Java application that displays "Hello, World!" in the console.

## Features

- Minimal Java application demonstrating basic project structure
- Gradle build system with wrapper for easy setup
- JUnit 5 testing framework integration
- Cross-platform compatibility (Windows, macOS, Linux)

## Description

This is a basic Java project built using Gradle. It serves as a template or starting point for Java development. The application simply prints "Hello, World!" to the console when executed, demonstrating the fundamental structure of a Java program.

## Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/java-hello-world.git
cd java-hello-world

# Build and run the application
./gradlew run
```

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

Alternatively, you can use the Gradle run task:

```bash
./gradlew run
```

For Windows:
```bash
# Build the project
gradlew.bat build

# Run the application
java -cp build\classes\java\main org.example.Main

# Or use the Gradle run task
gradlew.bat run
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

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

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
