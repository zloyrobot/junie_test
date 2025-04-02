# Java Hello World

Простое Java-приложение, которое выводит "Hello, World!" в консоль.

## Описание

Это базовый Java-проект, построенный с использованием Gradle. Он служит шаблоном или отправной точкой для разработки на Java.

## Требования

- Java Development Kit (JDK) 8 или выше
- Gradle (или используйте включенный Gradle wrapper)

## Установка

Клонируйте репозиторий и перейдите в директорию проекта:

```bash
git clone [repository-url]
cd [project-directory]
```

## Сборка проекта

Соберите проект, используя Gradle wrapper:

```bash
./gradlew build
```

Для Windows:

```bash
gradlew.bat build
```

## Запуск приложения

Чтобы запустить приложение, сначала соберите проект, а затем запустите скомпилированный Java-класс:

```bash
# Сборка проекта
./gradlew build

# Запуск приложения
java -cp build/classes/java/main org.example.Main
```

Для Windows:
```bash
# Сборка проекта
gradlew.bat build

# Запуск приложения
java -cp build\classes\java\main org.example.Main
```

## Тестирование

Проект настроен для тестирования с использованием JUnit 5. Запустите тесты следующей командой:

```bash
./gradlew test
```

## Структура проекта

```
.
├── build.gradle.kts        # Конфигурация сборки Gradle
├── settings.gradle.kts     # Настройки Gradle
├── src
│   └── main
│       └── java
│           └── org
│               └── example
│                   └── Main.java  # Главный класс приложения
└── README.md               # Этот файл
```

## Зависимости

- JUnit 5 (для тестирования)

## Лицензия

[Вставьте лицензию здесь]
