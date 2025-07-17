
![Screenshot 2024-07-11 at 5 23 56 PM](https://github.com/basahota/aws-cicd/assets/25712816/342e97bf-5fbe-490f-bf76-b5bdd33ce415)

<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

<img src="AWS_CI-CD_Project.png" width="30%" style="position: relative; top: 0; right: 0;" alt="Project Logo"/>

# AWS_CI-CD_PROJECT

<em>Accelerate Innovation with Seamless Cloud Delivery</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/iamashishxo/AWS_CI-CD_Project?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/iamashishxo/AWS_CI-CD_Project?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/iamashishxo/AWS_CI-CD_Project?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Markdown-000000.svg?style=flat&logo=Markdown&logoColor=white" alt="Markdown">
<img src="https://img.shields.io/badge/Spring-000000.svg?style=flat&logo=Spring&logoColor=white" alt="Spring">
<img src="https://img.shields.io/badge/Docker-2496ED.svg?style=flat&logo=Docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/XML-005FAD.svg?style=flat&logo=XML&logoColor=white" alt="XML">
<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat&logo=YAML&logoColor=white" alt="YAML">

</div>
<br>

---

## 📄 Table of Contents

- [Overview](#-overview)
- [Getting Started](#-getting-started)
    - [Prerequisites](#-prerequisites)
    - [Installation](#-installation)
    - [Usage](#-usage)
    - [Testing](#-testing)
- [Features](#-features)

---

## ✨ Overview

AWS_CI-CD_Project is a comprehensive developer tool designed to automate the build, test, and deployment processes for Spring Boot-based microservices within AWS environments. It integrates CI/CD pipelines, Docker containerization, and cloud deployment best practices to streamline development workflows.

**Why AWS_CI-CD_Project?**

This project simplifies the complexities of deploying scalable, reliable microservices on AWS. The core features include:

- **🛠️ Build Automation:** Automates compilation, testing, and container image creation with a robust buildspec.yaml.
- **🚀 Containerization:** Encapsulates applications within Docker containers for consistent runtime environments.
- **🔧 Continuous Deployment:** Facilitates seamless integration and delivery pipelines, ensuring rapid iteration.
- **🌐 RESTful API Management:** Provides REST endpoints for managing course data, supporting modern API-driven architectures.
- **✅ Health & Readiness Checks:** Ensures applications load correctly and are ready for production deployment.
- **🌟 Cloud-Ready Architecture:** Supports scalable deployment within microservices ecosystems on AWS.

---

## 📌 Features

|      | Component       | Details                                                                                     |
| :--- | :-------------- | :------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture**  | <ul><li>Microservices-oriented with REST APIs</li><li>Spring Boot framework for backend</li><li>Containerized via Docker</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Uses Maven for dependency management and build lifecycle</li><li>Adheres to Java best practices</li><li>Includes OpenAPI documentation via springdoc-openapi</li></ul> |
| 📄 | **Documentation** | <ul><li>Dockerfile for container setup</li><li>README.md with project overview</li><li>OpenAPI UI for API docs</li></ul> |
| 🔌 | **Integrations**  | <ul><li>CI/CD pipeline configured with AWS CodeBuild (buildspec.yaml)</li><li>Docker Hub for container registry</li><li>Spring Boot with OpenAPI for API documentation</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separate modules for core services</li><li>Configurable via YAML and XML files</li></ul> |
| 🧪 | **Testing**       | <ul><li>Includes unit tests with JUnit 5</li><li>Potential integration tests via Maven</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Uses OpenJDK 17 for optimal JVM performance</li><li>Containerized for scalable deployment</li></ul> |
| 🛡️ | **Security**      | <ul><li>API documentation secured with Spring Security</li><li>Uses HTTPS in deployment (implied via best practices)</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Managed via Maven (`pom.xml`)</li><li>Includes Spring Boot, springdoc-openapi, and OpenJDK 17</li></ul> |

---

## 🚀 Getting Started

### 📋 Prerequisites

This project requires the following dependencies:

- **Programming Language:** Java
- **Package Manager:** Maven
- **Container Runtime:** Docker

### ⚙️ Installation

Build AWS_CI-CD_Project from the source and install dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/iamashishxo/AWS_CI-CD_Project
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd AWS_CI-CD_Project
    ```

3. **Install the dependencies:**

**Using [docker](https://www.docker.com/):**

```sh
❯ docker build -t iamashishxo/AWS_CI-CD_Project .
```
**Using [maven](https://maven.apache.org/):**

```sh
❯ mvn install
```

### 💻 Usage

Run the project with:

**Using [docker](https://www.docker.com/):**

```sh
docker run -it {image_name}
```
**Using [maven](https://maven.apache.org/):**

```sh
mvn exec:java
```

### 🧪 Testing

Aws_ci-cd_project uses the {__test_framework__} test framework. Run the test suite with:

**Using [docker](https://www.docker.com/):**

```sh
echo 'INSERT-TEST-COMMAND-HERE'
```
**Using [maven](https://maven.apache.org/):**

```sh
mvn test
```

---

<div align="left"><a href="#top">⬆ Return</a></div>

---

