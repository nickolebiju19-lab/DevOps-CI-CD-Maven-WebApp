CI/CD Maven Web Application using Jenkins

Project Overview

This project demonstrates an end-to-end Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Java Maven Web Application.

The application source code is hosted on GitHub. Jenkins automatically clones the repository, builds the project using Maven, performs static code analysis with SonarQube, uploads the generated WAR artifact to Nexus Repository, and deploys the application to Apache Tomcat running on AWS EC2.



Technologies Used

- Java
- Maven
- Git & GitHub
- Jenkins
- SonarQube
- Nexus Repository
- Apache Tomcat
- AWS EC2
- Linux (Ubuntu & Amazon Linux)

---

CI/CD Workflow

```text
GitHub
   │
   ▼
Jenkins
   │
   ▼
Maven Build
   │
   ▼
SonarQube Analysis
   │
   ▼
Nexus Repository
   │
   ▼
Apache Tomcat
   │
   ▼
Running Web Application
```

---

Pipeline Stages

- Clone Repository
- Maven Build
- SonarQube Code Analysis
- Upload Artifact to Nexus Repository
- Deploy WAR to Apache Tomcat

---

Project Screenshots

- Jenkins Pipeline Success
- SonarQube Dashboard
- Nexus Repository
- Tomcat Manager
- Running Web Application

---

Project Outcome

Successfully implemented an automated CI/CD pipeline capable of building, analyzing, storing, and deploying a Java web application with minimal manual intervention.

---

## 👨‍💻 Author

**Nickole Biju**
