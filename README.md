# Java Hello World 项目

一个在控制台显示 "Hello, World!" 的简单 Java 应用程序。

## 描述

这是一个使用 Gradle 构建的基础 Java 项目。它可以作为 Java 开发的模板或起点。

## 要求

- Java 开发工具包 (JDK) 8 或更高版本
- Gradle (或使用包含的 Gradle 包装器)

## 安装

克隆仓库并导航到项目目录：

```bash
git clone [仓库地址]
cd [项目目录]
```

## 构建项目

使用 Gradle 包装器构建项目：

```bash
./gradlew build
```

对于 Windows：

```bash
gradlew.bat build
```

## 运行应用程序

要运行应用程序，首先构建项目，然后运行编译后的 Java 类：

```bash
# 构建项目
./gradlew build

# 运行应用程序
java -cp build/classes/java/main org.example.Main
```

对于 Windows：
```bash
# 构建项目
gradlew.bat build

# 运行应用程序
java -cp build\classes\java\main org.example.Main
```

## 测试

该项目配置为使用 JUnit 5 进行测试。使用以下命令运行测试：

```bash
./gradlew test
```

## 项目结构

```
.
├── build.gradle.kts        # Gradle 构建配置
├── settings.gradle.kts     # Gradle 设置
├── src
│   └── main
│       └── java
│           └── org
│               └── example
│                   └── Main.java  # 应用程序主类
└── README.md               # 本文件
```

## 依赖项

- JUnit 5 (用于测试)

## 许可证

[在此插入许可证]
