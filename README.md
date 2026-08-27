# CloudNova-website-AWS-Deployment
A responsive website deployed and hosted on Amazon EC2

##  Project Overview

CloudNova is a responsive website that I designed and deployed on Amazon Web Services (AWS) using an Amazon EC2 instance.

The purpose of this project was to gain practical experience with cloud infrastructure by taking a website and deploying it to a cloud-based virtual server.

The project involved configuring AWS networking, launching and configuring an EC2 instance, setting up a web server, configuring security rules, and making the website accessible through the internet.

---

##  Project Objectives

The main objectives of this project were to:

* Launch and configure an Amazon EC2 instance
* Create and configure an AWS VPC
* Configure a public subnet
* Configure a route table
* Attach an Internet Gateway
* Configure an EC2 Security Group
* Configure a web server
* Deploy the CloudNova website to EC2
* Test the website through the internet
* Gain practical experience with AWS cloud infrastructure

---

##  Project Architecture

The CloudNova website was hosted on an EC2 instance located inside a public subnet within an AWS VPC.

### Architecture Flow

**User → Internet → Internet Gateway → Public Subnet → EC2 → Web Server → CloudNova Website**

The architecture demonstrates how the different AWS networking components work together to allow an EC2-hosted website to be accessed from the internet.

---

##  Deployment Process

### 1. VPC Configuration

A VPC was created to provide the networking environment for the project.

### 2. Public Subnet

A public subnet was configured within the VPC to host the EC2 instance.

### 3. Internet Gateway

An Internet Gateway was attached to the VPC to allow communication between the VPC and the internet.

### 4. Route Table

A route table was configured to direct internet-bound traffic through the Internet Gateway.

### 5. EC2 Instance

An Amazon EC2 instance was launched inside the public subnet.

The instance was configured with the required networking and security settings.

### 6. Security Group

A Security Group was configured to control traffic to the EC2 instance.

The required ports were opened for server administration and website access.

### 7. Web Server Configuration

The EC2 instance was configured as a web server so that it could serve the CloudNova website.

### 8. Website Deployment

The CloudNova website files were transferred to the EC2 instance and placed in the appropriate web server directory.

### 9. Testing

The website was accessed through the EC2 instance's public IP address to verify that it was successfully deployed and accessible.

---

## Skills Demonstrated

This project allowed me to demonstrate practical skills in:

* AWS EC2 deployment
* AWS VPC networking
* Public subnet configuration
* Route table configuration
* Internet Gateway configuration
* Security Group configuration
* Linux server administration
* Web server configuration
* Website deployment
* Cloud troubleshooting
* Basic cloud architecture
* Technical documentation

---

## Project Outcome

The CloudNova website was successfully deployed and hosted on an Amazon EC2 instance.

The project demonstrated the process of taking a website and deploying it to a cloud environment with the necessary networking, server, and security configuration.


