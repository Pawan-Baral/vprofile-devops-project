# 🚀 VProfile DevOps Lift & Shift Project

## 📌 Overview

This project demonstrates a complete **Lift & Shift migration** of a Java web application to the cloud using modern DevOps practices.

It includes CI/CD automation, configuration management, and infrastructure provisioning.

---

## 🧰 Tech Stack

* Java (Spring MVC)
* Maven
* Apache Tomcat
* Jenkins (CI/CD)
* Ansible (Configuration Management)
* AWS (EC2, S3, IAM)
* Nginx
* MySQL
* Memcached
* RabbitMQ

---

## ⚙️ Architecture

The system is deployed on AWS using multiple services:

* EC2 instances for application and services
* Nginx as reverse proxy
* MySQL for database
* Memcached for caching
* RabbitMQ for messaging

---

## 🔄 CI/CD Pipeline

1. Developer pushes code to GitHub
2. Jenkins triggers pipeline
3. Maven builds the application (WAR file)
4. Ansible provisions and configures servers
5. Application deployed to Tomcat
6. Nginx routes traffic

---

## 📂 Project Structure

* `Jenkinsfile` → CI/CD pipeline
* `ansible/` → automation scripts
* `userdata/` → provisioning scripts
* `src/` → application code

---

## 🎯 Key Highlights

* Automated deployment using Jenkins + Ansible
* Infrastructure as Code approach
* Scalable multi-tier architecture
* Real-world DevOps workflow

---

## 📸 Architecture Diagram

GitHub → Jenkins → Ansible → AWS EC2
                                ↓
        ┌───────────────┬───────────────┬
        ↓               ↓               ↓
     Tomcat         MySQL         Memcached
        ↓                                |             
     Nginx (Public Access)             Database

---

## 🚀 How to Run

1. Clone repo
2. Setup Jenkins
3. Configure AWS EC2 instances
4. Run Ansible playbooks
5. Deploy using Jenkins pipeline

---

