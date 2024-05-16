# DevOps
DevOps

Course Content :


01 Week 0 - DevOps SRE Fundamentals
DevOps/SRE tools setup on AWS
DevOps Flow
Redhat Linux - Introduction, and common commands
Linux folder and file structure 
AWS account setup
AWS basics / SRE system overview
DevOps projects and real time scenarios
Git and Github Overview.


02Week 1 - Source Code management & Networking Concepts
Difference between CVCS and DVCS
Importance of Git
Installation of Git
Git three-stage Architecture
Detail explanation of Repository, Commit, Tags, Snapshots, Push-Pull Mechanism, and Branching Strategy
Working with Git stash and Git pop
Resolve Merge conflicts in Git
Git Revert and Reset (Reset vs Revert)
Git rebase
Working with git Squash
Git cherrypick
What is Git fork?
Git Integration on VScode, Git Authentication with Github via SSH and HTTPS Protocol
Github Introduction, Creating Repositories, PR’s
Networking Concepts in Detail


03Week 2 - Continuous Integration and Continuous Delivery
Continuous Integration/Continuous Deployment (CICD) Workflow Overview
Understanding JenkinsFile: Exploring Jenkins Jobs, Jenkins Pipeline, and Jenkins File
Build Triggers in Jenkins: SCM Polling, GITScm Polling, Build Periodically - Uncovering the What, Why, and How
Groovy File Creation: Conceptualizing and Crafting Groovy Scripts for Jenkins
Integrating GitHub with Jenkins: Establishing Webhooks for Seamless Collaboration
Grasping Merge Request Concepts in the CI/CD Process
Jenkins Master-Slave Configuration: Optimizing Resource Utilization in CI/CD
Triggering Pipelines Directly from JenkinsFile: Streamlining Automation
GitLab Branching Strategy: Best Practices for Code Collaboration and Version Control
Hands-On Experience: Building a Jenkins CI Pipeline with Groovy, Incorporating Various Stages
Configuring Docker Engineer as the Jenkins Slave - Jenkins Dynamic Slave Configuration
Jenkins Plugins - Docker, Git, Maven and other common used plugins
Integrating Kubernetes with jenkins


04Week 3 - Package Management ( Docker) Using Real Time Scenarios & Understanding SonarQube
Conceptual Concepts of Dockers
What is Virtualization before deep dive into the Containerization
O.S level virtualization
Docker vs Virtual Machine
What is Docker and its History
Docker Architecture
Advantages and limitations of Docker
Components of Docker (Docker Daemon, Docker Client, Docker Host)
Docker Image
Docker lifecycle
Docker Image TAR and Unarchive, Docker container states, Docker Networking
(Create and Manage), Dockerfile and CD flow
CD Tools with Docker (Integrating CD tools like Jnekins and Github action using projects) 
Docker Networking
Docker Security Introduction
Docker volume
SonarQube, Quality Gates, and Profiles:
  Understanding SonarQube's Role in Code Quality Assessment
  Implementing Quality Gates to Ensure Code Quality Standards
  Configuring and Managing SonarQube Profiles for Code Analysis
  
  
05Week 4 - Automation Using Shell Scripting & RedHat Linux Administration
Shell Scripting
Basics of Shell Scripting
Real - Time Scenarios We have in shell Scripting. 
Red hat Linux Administration
   Introduction to Red Hat Linux
   File System Management
   User and Group Administration
   Package Management with Yum
   System Services and systemd
   Networking Configuration
   Networking Concepts - SNAT, DNAT,IP, Netmask  
   Security and Permissions
   System Performance Monitoring
   Storage Management
   Backup and Restore
   Kernel and Module Management
   Remote Access with SSH
   CPU Scheduling, Job Scheduling
Python Based Automation Scripts


06Week 5 - Deep Dive Kubernetes
Introduction to Kubernetes
Defining Kubernetes and its Role in Container Orchestration
Exploring the Features and History of Kubernetes
Kubernetes Architecture
In-Depth Analysis of Kubernetes Architecture
Understanding Node Components, Manifest File Components, and Service Components
Overview of Node and Pod Fundamentals
Role of Master Node and Components of the Control Plane
Installing and Configuring kubectl and minikube
Kubernetes Basics
Kubernetes Commands: Navigating and Interacting with Kubernetes
Creation and Deletion of Pods
Managing Kubernetes YAML Configurations
Higher-Level Kubernetes Objects and Object Management
Labels and Selectors in Kubernetes
Kubernetes Networking, Services, and NodePort
Understanding Namespaces in Kubernetes
Multi Container Pod Setup
Pods Design pattern - Sidecar, Ambassador
Working with Applications in Kubernetes:
Installing Kubernetes on AWS
Deploying Microservices Applications to Kubernetes Cluster
ConfigMap and Secret Usage in Kubernetes
Exploring Volumes in Kubernetes
Persistent Volume and LivenessProbe in Kubernetes
Replication, Auto-Healing, and Deployment in Kubernetes
Advanced Kubernetes Topics:
Helm And Istio Service mesh 
Role-Based Access Control (RBAC) and Service Accounts
Helm and Istio Integration in Kubernetes
Kubernetes Interview Questions
Differences Between Monolithic and Microservices Architecture
HPA, Ingress, Taint and toleration,


07Week 6 - Cloud Services & AWS Fundamentals
Overview of AWS Global Infrastructure
Detailed Overview of Elastic Compute Cloud (EC2)
Setting Up Your First EC2 Instance
In-Depth Guide to EC2 Instance Configuration
Exploring EC2 Options in Detail
Connecting to Cloud Instances
Security Group Handling and Management
Introduction to Amazon S3
Auto Scaling and Load Balancing
Understanding Cloud Formation and CloudWatch
Exploring Simple Notification Service (SNS) and Simple Queue Service (SQS)
Overview of Relational Database Service (RDS) and Identity and Access Management (IAM)
Project-Based Learning: ECS and ECR
Serverless Architecture
Utilizing CloudWatch for Monitoring and Setting Billing Alarms
Hands-On Experience with AWS Services:
AWS VPC
AWS Lambda
Amazon API Gateway
Amazon SNS
Amazon CloudFront
AWS CloudFormation


08Week 7 - Ansible
Defining Ansible and Understanding the Need for Configuration Management 
In-Depth Exploration of Ansible Architecture
Analyzing the Architecture of Ansible for Efficient Configuration Management.
Detailed Steps for Installing and Setting Up Ansible.
Exploring Essential Components such as Ansible Roles, Ansible Collections, Ad-hoc Commands, and Playbooks Setup.
Automation with Ansible Playbooks
Creating Playbooks for Automation.
Building Playbooks to Copy Files with Special Variables.
Utilizing Ansible Handlers and Notifiers for Effective Automation.
Implementing Playbooks for Downloading Artifacts and Unzipping Files.
Advanced Automation Scenarios with Ansible
Leveraging Ansible Tags for Targeted Deployment to Servers.
Automating the Installation of Apache and Configuring the Corresponding Configuration Files
Configure Multi node k8s cluster with Ansible 
Manage Variable and Ansible Facts


09Week 8 - Infrastructure As Code using Terraform
Introduction to Infrastructure as Code (IaC)
Getting Started with Terraform
Terraform Basics: Variables, Resources, Attributes, and Dependencies
Terraform State Management
Advanced Terraform Concepts: for-each and module
Terraform Project Development
AWS Infrastructure Security with Terraform
CIDR Setup Example with /16
Subnet Configuration with Terraform
Terraform State Locking
Terraform Modules


10Week - 9 Monitoring And Logging
Installation Of grafana 
Database Installation MySQL
Grafana Setup with My SQL 
Installation of prometheus 
Setting Up Prometheus on Kubernetes cluster 
Monitoring K8 Cluster with prometheus 
Alerts in Grafana
Grafana Plugins.

# DevOps Topics

## Table of Contents
1. [Introduction](#introduction)
2. [Tools](#tools)
3. [Practices](#practices)
4. [Workflows](#workflows)
5. [Resources](#resources)

## Introduction
Briefly explain what DevOps is and its importance in modern software development and operations.

## Tools
List popular DevOps tools with brief descriptions and links to their official websites or repositories.

- **Version Control**
  - Git: Distributed version control system. [Link](https://git-scm.com/)
  - GitHub: Git repository hosting service. [Link](https://github.com/)

- **Continuous Integration/Continuous Deployment (CI/CD)**
  - Jenkins: Automation server for CI/CD pipelines. [Link](https://www.jenkins.io/)
  - Travis CI: CI service for GitHub projects. [Link](https://www.travis-ci.com/)

- **Configuration Management**
  - Ansible: Automation tool for configuration management. [Link](https://www.ansible.com/)
  - Puppet: Configuration management and automation tool. [Link](https://puppet.com/)

- **Containerization**
  - Docker: Containerization platform. [Link](https://www.docker.com/)
  - Kubernetes: Container orchestration platform. [Link](https://kubernetes.io/)

- **Monitoring and Logging**
  - Prometheus: Monitoring and alerting toolkit. [Link](https://prometheus.io/)
  - ELK Stack (Elasticsearch, Logstash, Kibana): Log management and analysis. [Link](https://www.elastic.co/elastic-stack)

## Practices
Describe common DevOps practices and methodologies.

- **Infrastructure as Code (IaC)**
  - Using tools like Terraform or CloudFormation to define and manage infrastructure.

- **Continuous Integration/Continuous Deployment (CI/CD)**
  - Automating build, test, and deployment processes to achieve faster and more reliable software delivery.

- **Microservices Architecture**
  - Designing applications as a collection of loosely coupled services for scalability and flexibility.

## Workflows
Explain typical DevOps workflows or pipelines.

### CI/CD Pipeline Workflow
1. **Code**
2. **Build**
3. **Test**
4. **Deploy**
5. **Monitor**

## Resources
Provide links to useful resources for learning more about DevOps.

- **Books**
  - null
  - null

- **Online Courses**
  - null
  - null

- **Blogs and Websites**
  - null
  - null

---

Customize the above template according to your specific needs, adding more tools, practices, workflows, or resources as necessary. Ensure to keep the README concise, informative, and well-organized to help users quickly understand and navigate through the DevOps topics.
