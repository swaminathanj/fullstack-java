# Full Stack Development with Java

Aum Amma

## Spring Boot

### Getting Started
- Install JDK 23 (latest one) - https://www.oracle.com/java/technologies/downloads/#jdk23
- Download and decompress Spring Test Suite (STS) for Eclipse - https://spring.io/tools
- Launch STS application by navigating into the decompressed folder.
- Create the workspace under the top-level decompressed folder. This is just a matter of convenience. When you copy STS from one system to another, you will not forget to copy the workspace. That's it.
- Windows -> Preferences -> Java -> Installed JRE (Add jdk23 folder to be sure latest java version is used).

### Creating a new Spring Started Project
Typically follow the steps (Sec 1.2 and 1.3) in prescribed book Spring In Action 6th Edition by Craig Walls
- New Project -> Spring Starter Project
  - Step 1: Give project name, group, artifact, choose Maven type and click Next
  - Step 2: Add 3 dependencies: Developer tools -> Spring Boot Dev Tools, Template Engines -> Thymeleaf, Web -> Spring Web (The book tells only the first one explicitly) and click Next
     Step 3: Nothing to do. Click Finish.
- Understand the folder structure and the files there in. They are explained.
- Build the project from (i) Command line using mvnw and (ii) STS
- Testing can be done with mock tests that simulates browser action
- You can launch the project from Boot Dashboard lower left corner
- You will also add controller: HomeController.java, template: home.html and resources: images/TacoCloud.png
- And repeat the build - launch project - test steps
- You will make silly mistakes, encounter errors. That's inevitable. Pursue this till you get it right.
- Keep reading/referring to the section content to get a better grip and understanding of what's in there.
