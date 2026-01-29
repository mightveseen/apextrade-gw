# Template

Repository template for new projects
---

## What's included

- **Spring Boot 3.2** with Web and Actuator
- **Java 21**, **Gradle 8.11** (wrapper committed)
- **CI:** build and tests on every push/PR (GitHub Actions)
- **Dependabot:** monthly PRs for dependency and Actions updates
- `.gitignore` for Java, Gradle, IDEs (IntelliJ, VS Code, Cursor), Spring Boot

---

## Requirements

- Java 21+
- Gradle 8.11.x (wrapper in repo is enough)

## Build and run

```bash
./gradlew bootRun
```

If `gradle/wrapper/gradle-wrapper.jar` is missing, run once:

```bash
gradle wrapper --gradle-version 8.11.1
```