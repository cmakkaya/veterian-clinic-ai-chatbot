# Developing a Scalable AI Chatbot Using Azure OpenAI (LLM provider), Java Microservices, and MySQL – A Complete Guide
## Step-by-Step Tutorial: Integrating an AI Chatbot into a Microservices Application with MySQL DB Using Azure's OpenAI as the LLM provider.

<img width="2064" height="1591" alt="image" src="https://github.com/user-attachments/assets/20e0cc1b-9a21-4146-a0bd-49b5e3be0ff8" />

## 📗 Medium Articles Link:

- [📝Integrating an AI Chatbot into a Microservices App Using Azure's OpenAI as the LLM provider - A Hands-On Guide]() `Coming soon.`



## Topics we will cover:

Introduction
1. What are LLM and LLM Providers
2. Azure's OpenAI
* 2.1. What types of models are supported on Azure OpenAI?
* 2.2. Azure OpenAI Use Cases
* 2.3. Azure OpenAI Service pricing
Hands-on
3. Creating and deploying an Azure OpenAI
4. Deploying a Model
* 4.1. Using Azure Portal
* 4.2. Using az command
5. Testing the Functionality of the Azure OpenAI "gpt-4o-mini" Deployment Using the "curl" Command.
6. Running a Java-based microservices Application with MySQL DB on Azure Cloud
* 6.1. Cloning the Source Code of the Java-based Microservices Application to your VM
* 6.2. Architecture Diagram of the Spring Microservices App
* 6.3. Creating Jar Files and Images
* 6.4. Preparing Docker Compose File
* 6.5. Creating an .env File
* 6.6. Modifying the application.yml of spring-petclinic-genai-service to integrate the Spring/Azure AI Chatbot
* 6.7. Starting the Installation of the Microservices Application
* 6.8. Checking that the application is running properly
7. MySQL Database configuration
* 7.1. Starting a MySQL Database
* 7.2. Testing Database Functionality
* 7.3. Checking Whether Records Have Been Written to the Database Using the MySQL Query
* 7.3.1. Connect to MySQL Database
* 7.3.2. Running the SQL Query to Check the Records
* 7.3.3. Useful MySQL Commands for Microservices App's MySQL database
8. Testing the Azure AI Chatbot
9. Try AI Chatbot out on GPT-5-chat and compare it with GPT-4o-mini model deployments
10. Best Practices and Security for Using Azure OpenAI
11. Clean Up
12. Conclusion
13. Next post: "Building a Scalable AI Chatbot on a Kubernetes Cluster Using Azure OpenAI (LLM Provider), Java Microservices, and MySQL - A Complete Guide"
14. References


## You can access the following services at the given location:

* Discovery Server - http://localhost:8761
<img width="1870" height="1503" alt="image" src="https://github.com/user-attachments/assets/5f2ff0bf-5454-4067-a299-84e8b343dd6f" />

* Config Server - http://localhost:8888
  <img width="1496" height="325" alt="image" src="https://github.com/user-attachments/assets/d174faef-90bc-4bf2-a9be-7ae61f5dbede" />

* AngularJS frontend (API Gateway) - http://localhost:8080
  <img width="1868" height="1353" alt="image" src="https://github.com/user-attachments/assets/2ee388e5-ad6b-4b3a-a773-bf5f2fe857ea" />

* Customers, Vets, Visits, and GenAI Services - random port, check Eureka Dashboard 
* Tracing Server (Zipkin) - http://localhost:9411/zipkin/
  <img width="1870" height="1349" alt="image" src="https://github.com/user-attachments/assets/85c47373-b944-4c29-8974-955f90e4ac85" />

* Admin Server (Spring Boot Admin) - http://localhost:9090
  <img width="1884" height="1573" alt="image" src="https://github.com/user-attachments/assets/7ac987dc-b403-4dca-bb91-8a16706571dc" />

* Prometheus - http://localhost:9091
  <img width="1872" height="1235" alt="image" src="https://github.com/user-attachments/assets/4114bf1f-80cd-4a60-bef2-ac4851fcd018" />

* Grafana Dashboards - http://localhost:3000
  <img width="1026" height="486" alt="image" src="https://github.com/user-attachments/assets/7ff3e181-395d-49bc-bbb4-6c81ca932768" />


## Hi there, <img src = "https://github.com/cmakkaya/cmakkaya/blob/main/wavehand.gif" width = "40" align="center"> Nice to see you. <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="40"/>  

✏️ Don't forget to follow [my LinkedIn account](https://www.linkedin.com/in/cumhurakkaya/) or [my Medium account](https://cmakkaya.medium.com/)  to be informed about new updates in the repository.

⭐ Also, thank you for giving `stars` to my GitHub.

I hope they are useful to you.

🙏 I wish you growing success.

----------
### 📗 Note-1: If you learn detailed information about Artificial Intelligence (AI) and AWS AI Services, you can review my articles below:

- [📝 AWS AI Services-2: Hands-on use cases for Amazon Rekognition.](https://cmakkaya.medium.com/aws-ai-services-2-hands-on-use-cases-for-amazon-rekognition-4d98501ddcee)
- [📝 AWS AI Services-1: What are Artificial Intelligence (AI) and AWS AI Services?](https://cmakkaya.medium.com/aws-ai-services-1-what-is-artificial-intelligence-ai-and-aws-ai-services-c5f2adf60243)


### 📗 Note-2: If you want to learn more about deploying a Microservices Application with RDS MySQL DB into a Kubernetes Cluster with High Availability, Auto-Healing, Reliability, Auto Scaling, Monitoring, and Securing, you can read my Medium articles below. 

- [📝 Deploying a Microservices Application with RDS MySql DB into Kubernetes Cluster With High Availability, Auto-Healing, Reliability, Auto Scaling, Monitoring, and Securing.](https://cmakkaya.medium.com/deploying-a-microservices-application-with-rds-mysql-db-into-kubernetes-cluster-with-high-818c7c51ab12)

<img width="1606" height="898" alt="image" src="https://github.com/user-attachments/assets/521a6174-55ec-4562-9a50-23626df538f9" />

Step by Step Full DevOps Project, we will create a Kubernetes Cluster with High Availability, Auto-Healing, Reliability, Auto Scaling, Monitoring, and Securing on the Amazon EKS via Terraform or Cloudformation. To do these, we will create and use GitOps Workflow(ArgoCD), Jenkins, Rancher, Amazon Elastic Kubernetes Service (EKS), RDS MySQL Database, VPC (with both public and private subnets) for Amazon EKS, AWS Secrets Manager, Amazon Route53, Amazon Cloudfront, AWS Certificate Manager, Let's Encrypt-Cert Manager, CloudWatch, Prometheus, and Grafana. We will do these practically, step by step.

----------
### Connect with me 📫 You can learn more about me

- 🌐 [LinkedIn](https://www.linkedin.com/in/cumhurakkaya/)
- ✏️ [Medium Articles](https://cmakkaya.medium.com/)  100+ Articles
- 🌐 [GitHub](https://github.com/cmakkaya/)

------------
###  The source codes of this project
The Spring PetClinic Sample Application project was used in the source code of this project. You can find more detailed information about the source codes from [this link](https://github.com/spring-petclinic/).

[![Build Status](https://github.com/spring-petclinic/spring-petclinic-microservices/actions/workflows/maven-build.yml/badge.svg)](https://github.com/spring-petclinic/spring-petclinic-microservices/actions/workflows/maven-build.yml)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

