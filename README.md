# Program 3: Working with Gradle: Setting Up a Gradle Project, Understanding Build Scripts (Groovy and Kotlin DSL), Dependency Management and Task Automation.

## 1. Setting up a Gradle Project:

- To create a new Gradle project using the command line:
  - gradle init
 
## 2. Understanding Build Scripts

- Gradle uses a DSL (Domain-Specific Language) to define the build scripts. Gradle supports two DSLs:
  - Groovy DSL (default)
  - Kotlin DSL (alternative)
- Groovy DSL: This is the default language used for Gradle build scripts (build.gradle).
- Kotlin DSL: Gradle also supports Kotlin for its build scripts (build.gradle.kts).

## 3. Dependency Management

- Gradle provides a powerful dependency management system.
- You define your project’s dependencies in the dependencies block.
- Adding dependencies:
  - Gradle supports various dependency scopes such as implementation, compileOnly, testImplementation, and others.
  ```
  dependencies {
    implementation 'com.google.guava:guava:30.1-jre'
    testImplementation 'org.junit.jupiter:junit-jupiter-api:5.7.1'
  }
  ```
- Declaring repositories:
  - To resolve dependencies, you need to specify repositories where Gradle should look for them.
  ```
  repositories {
  mavenCentral()
  }
  ```

## 4. Task Automation

- Gradle tasks automate various tasks in your project lifecycle, like compiling code, running tests, and creating builds.

- Using predefined tasks: Gradle provides many predefined tasks for common activities, such as:
  - build – compiles the project, runs tests, and creates the build output.
  - test – runs tests.
  - clean – deletes the build output.

## 5. Working:

- gradle init
- yes
- 1
- 1
- [Project name (Program-3)]
- 1
- 2
- 1
- yes
- gradle run
