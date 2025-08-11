# Integrating an AI Chatbot into a Microservices App Using Azure's OpenAI as the LLM provider.
## Step-by-Step Tutorial: Integrating an AI Chatbot into a Microservices Application with MySQL DB Using Azure's OpenAI as the LLM provider.

<img width="2064" height="1591" alt="image" src="https://github.com/user-attachments/assets/20e0cc1b-9a21-4146-a0bd-49b5e3be0ff8" />

## 📗 Medium Articles Link:

- [📝Integrating an AI Chatbot into a Microservices App Using Azure's OpenAI as the LLM provider - A Hands-On Guide]() `Coming soon.`



## Topics we will cover:

9. Clean Up
10. Conclusion
11. Next post: "Caching Azure Database for PostgreSQL Flexible Server Using Redis Sentinel"
12. References


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
### 📗 Note: If you want to learn more about deploying a Microservices Application with RDS MySQL DB into a Kubernetes Cluster with High Availability, Auto-Healing, Reliability, Auto Scaling, Monitoring, and Securing, you can read my Medium articles below. 

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

