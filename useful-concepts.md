What is target folder and JAR file in java project?
```
In Java projects, the target folder is typically where the build artifacts are stored. If you see a .jar file in the
target folder, it represents a Java Archive (JAR) file, which is the output of your project’s build process.
```

What is build artifact?
```
A build artifact is the output of the software build process. It is a file or a collection of files that result from
compiling and packaging source code, along with any other necessary resources, into a deployable or usable format.
```

What is mvn clean package?
```
The mvn clean package command is used in Maven, a popular build automation tool for Java projects. This command is a 
combination of two lifecycle phases: clean and package
1. mvn clean
The clean phase removes all files generated during the previous build. Specifically, it deletes the target directory,
where Maven stores compiled classes, packaged artifacts (like JARs/WARs), and other temporary files.
2. mvn package
The package phase compiles the source code, runs tests, and packages the compiled code into a distributable format
(e.g., a JAR, WAR, or EAR file).

mvn clean package
First, it cleans up the target directory.Then, it compiles, tests, and packages the code into the final build artifact.
```

What is mvn clean install?
```
mvn clean install
Clean: Deletes the target directory for a fresh build.
Full Build Lifecycle: Executes all build lifecycle phases (validate → compile → test → package → install).
Installation: Installs the final artifact into the local Maven repository for reuse by other projects.
```

What is Sonarqube?
```
SonarQube is an open-source platform for continuous code quality inspection. It analyzes source code to detect bugs,
security vulnerabilities, code smells (maintainability issues), and technical debt. SonarQube integrates with build
tools, version control systems, and CI/CD pipelines, providing detailed reports and metrics to help developers write
cleaner, safer, and more maintainable code. Its key services include static code analysis for multiple programming
languages, quality gate enforcement to ensure code meets defined standards, and dashboards to visualize code health
trends. It supports both on-premises and cloud deployment, making it a powerful tool for improving code quality in
software development workflows.
```
