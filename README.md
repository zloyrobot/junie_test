# Java Hello World

コンソールに「Hello, World!」を表示するシンプルなJavaアプリケーションです。

## 説明

これはGradleを使用して構築された基本的なJavaプロジェクトです。Java開発のテンプレートまたは出発点として機能します。

## 要件

- Java Development Kit (JDK) 8以上
- Gradle（または付属のGradle wrapperを使用）

## インストール

リポジトリをクローンし、プロジェクトディレクトリに移動します：

```bash
git clone [repository-url]
cd [project-directory]
```

## プロジェクトのビルド

Gradle wrapperを使用してプロジェクトをビルドします：

```bash
./gradlew build
```

Windowsの場合：

```bash
gradlew.bat build
```

## アプリケーションの実行

アプリケーションを実行するには、まずプロジェクトをビルドし、次にコンパイルされたJavaクラスを実行します：

```bash
# プロジェクトのビルド
./gradlew build

# アプリケーションの実行
java -cp build/classes/java/main org.example.Main
```

Windowsの場合：
```bash
# プロジェクトのビルド
gradlew.bat build

# アプリケーションの実行
java -cp build\classes\java\main org.example.Main
```

## テスト

プロジェクトはJUnit 5を使用してテストするように設定されています。以下のコマンドでテストを実行します：

```bash
./gradlew test
```

## プロジェクト構造

```
.
├── build.gradle.kts        # Gradleビルド設定
├── settings.gradle.kts     # Gradle設定
├── src
│   └── main
│       └── java
│           └── org
│               └── example
│                   └── Main.java  # アプリケーションのメインクラス
└── README.md               # このファイル
```

## 依存関係

- JUnit 5（テスト用）

## ライセンス

[ここにライセンスを記入]
