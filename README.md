# Web-Application
Simple Web Application on AWS
# AWS Architecture Project: Web Application

This project demonstrates a **beginner-friendly web application architecture** on AWS using core services.

---

## **AWS Services Used**

- **EC2** – Hosts the web application server  
- **RDS (MySQL)** – Relational database for storing data  
- **S3** – Stores static assets (CSS, JS, images)  
- **Elastic Load Balancer (ELB)** – Distributes traffic across EC2 instances  
- **VPC** – Isolated network environment for security  
- **Security Groups** – Control access to EC2 and RDS  
- **CloudFront** – Optional CDN for faster content delivery  
- **Route 53** – Domain management  

---

## **Project Structure**
---

## **Deployment Steps**

1. **VPC & Networking**  
   - Create a VPC with public and private subnets  
   - Set up an Internet Gateway and route tables  

2. **EC2 Web Servers**  
   - Launch EC2 instances in public subnet  
   - Install and deploy Flask web app  

3. **RDS Database**  
   - Launch RDS MySQL instance in private subnet  
   - Configure Security Groups to allow access only from EC2  

4. **Load Balancer (ELB)**  
   - Create ELB in public subnet  
   - Register EC2 instances  

5. **S3 Static Assets**  
   - Upload CSS/JS/images to S3  
   - Optionally serve via CloudFront  

6. **Domain & DNS (Route 53)**  
   - Point your domain to ELB or CloudFront  

---

## **Architecture Diagram**

See `diagram/aws_architecture.png` for a visual representation of the project architecture.

---

## **Learning Outcomes**

- Understand AWS networking (VPC, subnets)  
- Launch and configure EC2 instances  
- Deploy a backend web application  
- Connect a web server to a database  
- Implement load balancing for scalability  
- Use S3 for static content and CloudFront for CDN  
- Manage a domain with Route 53  

---

## **Author**

Your Name – Cloud Computing Beginner  
[GitHub Profile](https://github.com/sbennett020586sb-glitch)  
[LinkedIn Profile](https://linkedin.comwww.linkedin.com/in/
stuart-bennett-9436b6352)
