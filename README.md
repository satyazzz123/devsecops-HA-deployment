# Devsecops-HA-deployment


![Screenshot from 2024-04-12 23-31-57](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/279da7ea-bb65-43b8-bfb9-49c204996ccd)


So in this Project I created  CI/CD pipeline setup using Jenkins, SonarQube, Trivy,,OWASP, Docker and set up a HA Kubernetes cluster for seamless application and deployment. Also intergrated Prometheus for metric collection and Grafana for viewing dashboards.Also integrated Email Notification with Jenkins.

## Features

- **Source Code Management (SCM) Integration:** Integrated GitHub repositories with Jenkins for version control and source code management.
  
- **Continuous Integration with Jenkins:** Configured Jenkins to automatically pull web application code from GitHub and trigger builds upon code changes using webhooks.

- **Code Quality Testing with SonarQube:** Integrated SonarQube for automated code quality analysis and static code scanning, ensuring adherence to industry best practices and standards.

- **Vulnerability Scanner with Trivy:** Integrated Trivy for thorough image scanning to identify and address vulnerabilities, enhancing the overall security posture of the deployment.

- **OWASP for Dependency Checks:** Integrated OWASP for comprehensive vulnerability checks in dependencies, contributing to a more secure and reliable application.

- **Containerized Deployment with Docker:** Orchestrated the deployment of the web application in a Docker container for consistent and scalable deployment. Automated Docker container creation and deployment through Jenkins pipelines for a seamless integration experience.

- **Monitoring with Prometheus and Grafana:** Implemented Prometheus and Grafana for robust monitoring of the CI/CD pipeline. Integrated Jenkins with Prometheus for effective monitoring.Used Node Exporter for monitoring node-level metrics in Prometheus.

- **Deployed with Kubernetes:** Established a Kubernetes Cluster with Node groups using kubeadm, kubelet, and kubectl on a 20.04 Ubuntu AMI machine. Written manifest files for deployment and service, and crafted a YAML script for seamless configuration with Prometheus and Grafana, ensuring a resilient and scalable infrastructure.

# Here's the Details on Project
![Screenshot from 2024-03-13 01-38-32](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/e67e45d8-7345-4038-bf33-6ac6d47c1e46)
![Screenshot from 2024-03-13 01-39-20](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/408ebf9a-c0b2-49da-8205-318fb4c69015)
![Screenshot from 2024-03-13 01-39-36](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/71f1b8ab-65e2-407a-b966-fc16def61bc9)
![Screenshot from 2024-03-13 01-40-10](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/987b8ce8-2576-4919-ab1b-aa9f11891b69)
![Screenshot from 2024-03-13 01-40-21](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/e46d5ffe-ee01-48a9-803e-14839f7c6367)
![Screenshot from 2024-03-13 01-40-35](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/1a7047cd-544f-4e64-b458-bf37e1cbcd78)
![Screenshot from 2024-03-13 01-41-43](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/821b7a58-a8b0-4f5f-b485-42a1c8811ead)
![Screenshot from 2024-03-13 01-41-50](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/dd59082f-a2b1-4d89-8527-27bdc05c2dfb)
![Screenshot from 2024-03-13 01-41-58](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/52d3d7b5-1e46-4990-be60-6adc934e0e1d)
![Screenshot from 2024-03-13 01-42-06](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/124ed33e-3513-40fb-9648-6c5189479650)
![Screenshot from 2024-04-12 23-48-27](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/6594354d-a663-4c3d-9f24-a320e52c4b51)
![Screenshot from 2024-03-13 01-53-48](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/5e626070-9093-4e4a-bc59-3378562e6537)
![Screenshot from 2024-03-13 01-46-23](https://github.com/satyazzz123/devsecops-HA-deployment/assets/105061492/aa707e82-ded8-49e6-b151-2c3bcbc8a11a)











