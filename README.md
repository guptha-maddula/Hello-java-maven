# Simple Java-Maven Build By Jenkins
---
## Overview

This repository contains a basic Java application designed to demonstrate the process of automating builds using Maven and Jenkins. It's a beginner-friendly project that showcases the fundamentals of Continuous Integration (CI) workflows.

---

## Features

- A simple Java application that prints a message to the console.
- A `pom.xml` file for managing dependencies and configuring Maven builds.
- Ready-to-use setup for Jenkins integration to automate the build process.

---

## Project Structure

```
hello-java-maven/
├── src/main/java/com/example/HelloWorld.java
├── pom.xml
```

---

## Requirements

To set up and run this project, you’ll need the following:

1. **Java JDK**: Version 8 or 11.
2. **Maven**: Build automation tool.
3. **Jenkins**: For automating the build process (configured with Maven and Java).
4. (Optional) **Git**: To manage and clone the repository.

---

## Steps to Use

1. Clone the repository to your local machine or server.
2. Ensure Java, Maven, and Jenkins are correctly installed and configured.
3. Open Jenkins, create a Freestyle job, and configure it to build this project using Maven (`clean package` goal).
4. Run the job and verify the successful build in Jenkins.
---
![Giving Build Sucess](./Pictures/Screenshot%202025-04-19%20231930.png)

![jenkins freestyle-build](./Pictures/Screenshot%202025-04-19%20232020.png)

---
## Checking Maven locally 
After completing the files and setting configurations on jenkins level and EC2 instance level. Checking the java-maven freestyle build by cloning the repo to your instance and go to `repo` Then,
---
Run : `mvn clean package`
![Output](./Pictures/Screenshot%202025-04-19%20232124.png)
## Output

The successful build produces a `.jar` file, located in the `target/` directory. This file can be executed to display the application's output.

