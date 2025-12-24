# java-practice
A Simple Maven Java Project for beginners

## Quickstart

1. Clone the repo

```bash
git clone https://github.com/DineshKuppan/java-practice.git
# or SSH
# git clone git@github.com:DineshKuppan/java-practice.git
```

2. Prerequisites

- Java 11+ (or the JDK version configured for the project)
- Maven 3.6+

3. Build (compile & package)

```bash
# Build and create a jar (skip tests)
mvn clean package -DskipTests
```

4. Run

You can run the application either with Maven's exec plugin or directly from the generated JAR:

```bash
# Run using the packaged JAR
java -cp target/java-practice-1.0-SNAPSHOT.jar dev.dinesh.app.App

# Or run with Maven exec plugin
mvn exec:java -Dexec.mainClass="dev.dinesh.app.App"
```


## License

This project is licensed under the MIT License — see the `LICENSE` file for details.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository and create a feature branch (use `feature/` or `bugfix/` prefixes).
2. Implement your changes and add tests where applicable.
3. Run the test suite locally:

```bash
mvn test
```

4. Commit with a clear message and open a Pull Request against `main`.

Guidelines:

- Follow the existing code style and project structure.
- Keep changes small and focused; one feature/fix per PR.
- Include unit tests for new features or bug fixes.
- Ensure all tests pass before submitting a PR.

## Roadmap

Planned improvements (high level):

- Add more example modules and exercises for beginners
- Improve documentation and usage examples
- Add CI configuration (GitHub Actions) for build and test
- Provide pre-built release artifacts

If you'd like to contribute to any item above, open an issue or a PR.

## Issues

Please use the GitHub Issues tracker to report bugs or request features. When opening an issue, include:

- A short, descriptive title
- Steps to reproduce the problem
- Expected vs actual behavior
- Environment details (OS, Java version, Maven version)
- Any relevant log output or stack traces

Label issues clearly (bug, enhancement, docs) and link related PRs. For larger changes, open an issue first to discuss the design.
