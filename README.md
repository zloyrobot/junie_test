# Java Hello World

A simple Java application that displays "Hello, World!" in the console.

## Description

This is a basic Java project built using Gradle. It serves as a template or starting point for Java development. The project demonstrates:

- Basic Java application structure
- Gradle build system configuration
- JUnit 5 test setup
- Project organization following standard conventions

This project is ideal for beginners learning Java or as a starting point for new Java applications.

## Requirements

- Java Development Kit (JDK) 8 or higher
- Gradle (or use the included Gradle wrapper)

## Quick Start

For the impatient, here's how to get the application running in the shortest time possible:

```bash
# Clone the repository
git clone https://github.com/yourusername/java-hello-world.git
cd java-hello-world

# Build and run in one command
./gradlew build && java -cp build/classes/java/main org.example.Main
```

You should see `Hello, World!` printed to your console.

## Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/java-hello-world.git
cd java-hello-world
```

Alternatively, you can download the project as a ZIP file and extract it to your preferred location.

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

- JUnit 5.10.0 (for testing)

## Troubleshooting

### Common Issues

1. **Java Not Found Error**
   - Ensure Java is installed and properly set in your PATH environment variable
   - Verify your Java installation by running `java -version` in your terminal

2. **Gradle Build Fails**
   - Make sure you have the correct Gradle version (the wrapper should handle this)
   - Check that your JDK version is compatible with the project
   - Run `./gradlew --info build` for more detailed error information

3. **ClassNotFoundException when running**
   - Ensure you've built the project before running
   - Verify you're using the correct classpath in your run command

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please make sure to update tests as appropriate and adhere to the existing coding style.

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2023 Your Name or Organization

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
