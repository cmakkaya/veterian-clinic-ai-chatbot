# Full CI/CD pipelines for microservices, based java dynamic web applications with database.  

#### I worked with a Spring pet clinic application consisting of 10 microservices. It is a Java-based web application developed by Spring company. I ran it on Development, Testing, Staging, and Production environments by using different DevOps tools (Jenkins, Kubernetes and Helm, Docker, Docker Compose, Terraform, Rancher, Nexus Repository, Maven, Ansible, Prometheus and Grafana, GitHub,  Selenium Jobs and Jacoco, Kompose conversion tool, Let’s Encrypt ACME and Cert Manager) and AWS Tools (Amazon Route 53, AWS Certificate Manager, AWS RDS MySql Database, AWS S3 Bucket, Amazon EKS(Kubernetes Service), Amazon ECS(Container Service), Amazon ECR(Container Repository), Amazon EC2, Amazon VPC's Components etc.). I created each environment and ran my application in it. When I worked in Staging and Production environments, I created full CI/CD Jenkins pipelines for each. Jenkins Server deployed on Elastic Compute Cloud (EC2) Instance is used as CI/CD Server to build pipelines. It has profiles: Testing/Staging/Production.

#### Also, finally, I set “Domain Name”, create an “A record” in my hosted zone by using AWS Route 53 domain registrar for the microservices app, and then, bind it to my the “Kubernetes cluster of the app”. I configured a TLS (Transport Layer Security) certificate for HTTPS connection to the domain name using Let’s Encrypt and Cert Manager. Thus, I provided a secure connection to my application on the Internet. 

![Spring Petclinic Microservices screenshot](docs/outputletsencrypt.jpg)

## 📗 Medium Articles Link:

- [📝Boost App Speed Using Redis Sentinel + Insight: Build a Highly Available Database Cache - A Hands-On Guide](https://cmakkaya.medium.com/boost-app-speed-using-redis-sentinel-insight-build-a-highly-available-database-cache-a-dacd71d929d0)

Learn how to build a highly available and scalable Redis database cache using Redis Sentinel. Boost your app's performance with this hands-on guide that covers caching strategies, Sentinel setup, failover testing, and Redis Insight monitoring.



## Topics we will cover:

9. Clean Up
10. Conclusion
11. Next post: "Caching Azure Database for PostgreSQL Flexible Server Using Redis Sentinel"
12. References


## If everything goes well, you can access the following services at the given location:

* Discovery Server - http://localhost:8761
* Config Server - http://localhost:8888
* AngularJS frontend (API Gateway) - http://localhost:8080
* Customers, Vets, Visits, and GenAI Services - random port, check Eureka Dashboard 
* Tracing Server (Zipkin) - http://localhost:9411/zipkin/ (we use [openzipkin](https://github.com/openzipkin/zipkin/tree/main/zipkin-server))
* Admin Server (Spring Boot Admin) - http://localhost:9090
* Grafana Dashboards - http://localhost:3000
* Prometheus - http://localhost:9091

## Hi there, <img src = "https://github.com/cmakkaya/cmakkaya/blob/main/wavehand.gif" width = "40" align="center"> Nice to see you. <img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="40"/>  

✏️ Don't forget to follow [my LinkedIn account](https://www.linkedin.com/in/cumhurakkaya/) or [my Medium account](https://cmakkaya.medium.com/)  to be informed about new updates in the repository.

⭐ Also, thank you for giving `stars` to my GitHub.

I hope they are useful to you.

🙏 I wish you growing success.


### 📗 Note: If you want to learn more about deploying a Microservices Application with RDS MySQL DB into a Kubernetes Cluster with High Availability, Auto-Healing, Reliability, Auto Scaling, Monitoring, and Securing, you can read my Medium articles below. 

- [📝 Deploying a Microservices Application with RDS MySql DB into Kubernetes Cluster With High Availability, Auto-Healing, Reliability, Auto Scaling, Monitoring, and Securing.](https://cmakkaya.medium.com/deploying-a-microservices-application-with-rds-mysql-db-into-kubernetes-cluster-with-high-818c7c51ab12)

<img width="2508" height="1402" alt="image" src="https://github.com/user-attachments/assets/e4af0dab-4c06-44ac-8bc6-af3d1353db5b" />

### Connect with me 📫 You can learn more about me

- 🌐 [LinkedIn](https://www.linkedin.com/in/cumhurakkaya/)
- ✏️ [Medium Articles](https://cmakkaya.medium.com/)  100+ Articles
- 🌐 [GitHub](https://github.com/cmakkaya/)
- 🌐 [GitLab](https://gitlab.com/cmakkaya)
- 🏢 [Portfolio/Resume Page](https://portfolio.cmakkaya-awsdevops.link/)
- 📺 [YouTube](https://www.youtube.com/channel/UCWcRIvy70tBBfrmBocDR5hA)


##  The source codes of this project
The Spring PetClinic Sample Application project was used in the source code of this project. You can find more detailed information about the source codes from [this link](https://github.com/spring-petclinic/).

[![Build Status](https://github.com/spring-petclinic/spring-petclinic-microservices/actions/workflows/maven-build.yml/badge.svg)](https://github.com/spring-petclinic/spring-petclinic-microservices/actions/workflows/maven-build.yml)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

