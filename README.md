#  Securing Critical Web Applications on AWS

<img width="1021" height="541" alt="image" src="https://github.com/user-attachments/assets/a21f8b70-609a-43d7-add2-71b41784fa47" />


🚀This is an AWS system design and implementation of security, scalability, and high availability cloud architecture supporting a containerized web application.

# Key solution deliverables included:

## Network Architecture:
-Configured AWS Transit Gateway to enable seamless connectivity between a public VPC hosting internet-facing services and a private VPC containing sensitive workloads.
-Ensured route table associations and propagation settings allowed for scalable multi-VPC communication.

<img width="1908" height="448" alt="image" src="https://github.com/user-attachments/assets/0369a21a-cc9f-4f96-b60b-1b6e5045c0b7" />
<img width="1911" height="454" alt="image" src="https://github.com/user-attachments/assets/ac8a7700-63ed-4468-a4ef-670fc2d1c1f5" />
<img width="1906" height="403" alt="image" src="https://github.com/user-attachments/assets/87a03a60-f6a3-431c-8e10-a93b27f8b0b9" />



---

## Load Balancing & Target Groups:
-Created and managed EC2 target groups for both Application Load Balancer (ALB) and Network Load Balancer (NLB).
-Configured health checks and listener rules to support diverse traffic handling requirements.
<img width="1892" height="437" alt="image" src="https://github.com/user-attachments/assets/9c92f93c-def3-41b2-aeda-485fad287104" />

<img width="1890" height="456" alt="image" src="https://github.com/user-attachments/assets/a197e416-d011-47a7-8c7f-87faa3df9e2e" />

---

## Containerized Application Deployment:
-Built and deployed a containerized application using Amazon ECS (Elastic Container Service) with Fargate, enabling serverless compute.
-Defined ECS task definitions, services, and cluster configuration, ensuring reliable auto-scaling and fault tolerance.
<img width="1903" height="386" alt="image" src="https://github.com/user-attachments/assets/f3004de8-2f7d-452b-b187-f7f414fb6c82" />
<img width="1883" height="806" alt="image" src="https://github.com/user-attachments/assets/85363f88-ad1b-4e77-b8a5-d62076a23be0" />
<img width="1884" height="785" alt="image" src="https://github.com/user-attachments/assets/f0446d49-3af0-47f6-a41c-5bbe2018e65b" />
<img width="1895" height="815" alt="image" src="https://github.com/user-attachments/assets/50fd4838-16b3-4b9c-a06b-3c95d9a112de" />


---


## Security Hardening with AWS WAF:
-Deployed a Web Application Firewall (WAF) to protect the ALB from common web exploits and attacks like SQL injection or cross-site scripting (XSS)
-Created custom rules and integrated managed rule sets for enhanced threat protection.

<img width="1886" height="811" alt="image" src="https://github.com/user-attachments/assets/d4f3e5f9-6075-482c-a13b-f416d88a72c6" />
<img width="1881" height="817" alt="image" src="https://github.com/user-attachments/assets/580599a1-c948-4c27-92cf-9ab4f08e3c66" />


---

## Technologies used for the solution:
Transit Gateway
VPC 
EC2
ALB/NLB
ECS (Fargate) 
WAF 
Docker

## Solution Outcomes:
🌐Achieving secure VPC communication with minimum latency.
📈Enabled scalable and resilient web application hosting.
🔐Hardened application security posture through proactive threat mitigation.
