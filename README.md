🚀 DevOps Real-time Project: Swiggy Application Deployment
Welcome to the Swiggy Application Deployment project! In this project, I have leveraged modern DevSecOps tools to automate, secure, and optimize the deployment pipeline for a feature-rich Swiggy-like application. 🎉

This project showcases Infrastructure as Code (IaC), Continuous Integration (CI), Continuous Deployment (CD), Containerization, and Security Best Practices in a real-world scenario.

🔥 Tech Stack & Tools Used
The project integrates multiple DevOps tools for infrastructure provisioning, CI/CD automation, security analysis, and container management:

Terraform – Infrastructure as Code (IaC) for cloud provisioning
GitHub – Version control and source code repository
Jenkins – Continuous Integration & Deployment (CI/CD)
SonarQube – Static code analysis for code quality
OWASP ZAP – Security vulnerability scanning
Trivy – Container image vulnerability scanning
Docker & DockerHub – Containerization and image hosting
📂 Project Architecture
The Swiggy Application Deployment project follows a structured CI/CD pipeline:

✅ Steps in the Workflow
Code Management: Developers push the latest application code to GitHub.
Automated Build & Testing: Jenkins automatically triggers builds and runs unit tests.
Static Code Analysis: SonarQube scans for code quality issues.
Security & Vulnerability Checks:
OWASP ZAP performs penetration testing.
Trivy scans Docker images for vulnerabilities.
Containerization: Docker is used to build and package the application.
Deployment to Cloud: The containerized app is deployed using Terraform & AWS ECS/Kubernetes.
🛠️ Setup & Installation
1️⃣ Prerequisites
Ensure you have the following installed:

Terraform
Jenkins
Docker
SonarQube
Trivy
OWASP ZAP
An AWS Account with necessary IAM permissions
2️⃣ Infrastructure Provisioning with Terraform
Use Terraform to set up AWS resources:

terraform init
terraform plan
terraform apply
📌 Architecture Diagram
Architecture

📜 License
This project is open-source and available under the MIT License.

📩 Contact
For any queries or collaborations, reach out to me at:
📧 Email: mohannaik050@gmail.com
🌐 LinkedIn: www.linkedin.com/in/mohan-naik-megavath-431797188

Happy Coding! 🚀
