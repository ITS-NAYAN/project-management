
---

## 🏗️ PROJECT MANAGEMENT WEB APP — FULL STACK ON AWS

A secure, scalable **Project Management Application** built with **Next.js**, **Node.js**, and **PostgreSQL**, deployed on **AWS** using real-world production architecture and DevOps best practices.

---

## 📌 TECH STACK

| Layer                | Technology                                               |
| -------------------- | -------------------------------------------------------- |
| Frontend             | Next.js, TypeScript, Redux Toolkit, Tailwind CSS, Shadcn |
| Backend              | Node.js, Express.js, Prisma ORM                          |
| Database             | Amazon RDS (PostgreSQL)                                  |
| Authentication       | AWS Cognito                                              |
| Hosting & Networking | EC2, VPC, Subnets, IGW, Route Tables                     |
| Security             | IAM, Security Groups, Private DB Access                  |
| API Access           | Amazon API Gateway (HTTPS)                               |
| Deployment           | AWS Amplify Hosting for CI/CD                            |

---

## ✅ KEY AWS FEATURES IMPLEMENTED   

🔹 **Custom VPC** with public + private subnets<br>
🔹 **Secure Private RDS** (no public access)<br>
🔹 **EC2 backend with PM2** for process management<br>
🔹 **API Gateway** to resolve HTTPS / mixed content issues<br>
🔹 **Amplify Frontend Deployment** with environment variables<br>
🔹 **Strict Security Group Rules** (backend-only DB access)<br>
🔹 **Multi-AZ subnet group** for DB high availability<br>
🔹 **Prisma migration + seeding on EC2**

This deployment follows **AWS Well-Architected Framework security principles** ✅

---

## 🧪 FEATURE 

✔ User login/signup with AWS Cognito<br>
✔ Create, Update, Delete projects<br>
✔ Task management<br>
✔ Secure API communication over HTTPS<br>
✔ Production-grade deployment pipeline<br>

---

 
## 🏗️ ARCHITECTURE DIAGRAM <br>

Here is the architecture used for secure AWS deployment:

<p align="center">
  <img src="[assets/architecture.png](https://github.com/ITS-NAYAN/project-management/blob/main/ARCHITECTURE%20DIAGRAM.png)" width="750"/>
</p>

---


## 🚀 AWS DEPLOYMENT OVERVIEW 

| Component    | Service               | Access               |
| ------------ | --------------------- | -------------------- |
| Frontend     | AWS Amplify           | Public HTTPS         |
| Backend      | Amazon EC2            | Public + API Gateway |
| Database     | Amazon RDS PostgreSQL | Private Subnets      |
| Auth         | AWS Cognito           | Managed Login        |
| API Security | API Gateway           | HTTPS enforced       |

---

## 🎯 LEARNING OUTCOMES  

✅ Cloud Networking (VPC, Subnets, Routing, SGs)<br>
✅ Full-stack CI/CD on AWS<br>
✅ Secure database deployment in private subnets<br>
✅ API Gateway integration patterns<br>
✅ Production app monitoring & maintenance (PM2)<br>

---

## 📌 Repository Link

🔗 *https://github.com/ITS-NAYAN/project-management.git*

---


## 🤝 Contributions

Pull requests are welcome. Feel free to open an issue for suggestions or bugs.

---

## ✨ Author

**ITS NAYAN**
🚀 Cloud & DevOps Engineer | <br>
📌 Passionate about scalable and secure AWS architectures

---
