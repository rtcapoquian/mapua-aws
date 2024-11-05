# 3-Month AWS Beginner Projects Guide 🌐☁️

This guide includes five beginner-friendly projects to help you build foundational AWS skills. Each project takes about two weeks to complete, allowing you to cover all projects in three months.

---

## Project 1: Build and Host a Static Website on Amazon S3

**🎯 Objective**: Gain hands-on experience with Amazon S3 and learn the basics of cloud storage and static website hosting.

### 🔍 Overview
- **Services Used**: Amazon S3, Route 53 (optional for custom domain), CloudFront (optional for CDN)
- **Skills Learned**: S3 bucket management, static website hosting, basic security configurations

### 📌 Steps
1. **Create an S3 Bucket** for your website and enable public access.
2. **Upload Website Files** (HTML, CSS, JavaScript) to the bucket.
3. **Enable Static Website Hosting** in the S3 bucket properties.
4. **(Optional)**: Use Amazon Route 53 for a custom domain or add CloudFront for content delivery.

### 📖 Resources
- [Static Website Hosting with Amazon S3 - AWS Docs](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html)
- [Video Tutorial on Hosting with S3 by RejiCodes](https://www.youtube.com/@RejiCodes)

---

## Project 2: Create a Serverless Contact Form with API Gateway and Lambda

**🎯 Objective**: Set up a serverless backend using API Gateway and Lambda, and store data in DynamoDB.

### 🔍 Overview
- **Services Used**: AWS Lambda, Amazon API Gateway, DynamoDB
- **Skills Learned**: Serverless architecture, API creation, Lambda function basics, DynamoDB storage

### 📌 Steps
1. **Create a Lambda Function** to process form submissions (using Node.js or Python).
2. **Set Up an API Gateway Endpoint** to receive form submissions and trigger the Lambda function.
3. **Connect Lambda to DynamoDB** to store form data.
4. **Test the API Endpoint** with your contact form.

### 📖 Resources
- [API Gateway and Lambda - AWS Docs](https://docs.aws.amazon.com/apigateway/latest/developerguide/how-to-create-api.html)
- [Video on API Gateway & Lambda by RejiCodes](https://www.youtube.com/@RejiCodes)

---

## Project 3: Deploy a Web Application on an EC2 Instance with Load Balancer

**🎯 Objective**: Understand EC2 by deploying a simple web app and using an Elastic Load Balancer for high availability.

### 🔍 Overview
- **Services Used**: Amazon EC2, Elastic Load Balancing, Auto Scaling, CloudWatch
- **Skills Learned**: EC2 instance management, load balancing, auto-scaling, basic monitoring

### 📌 Steps
1. **Launch an EC2 Instance** and install a web server (e.g., Apache).
2. **Deploy a Web App** by uploading code to the server.
3. **Set Up an Elastic Load Balancer (ELB)** to distribute traffic to multiple instances.
4. **Enable Auto Scaling** to add or remove instances based on traffic.
5. **Monitor Performance** with CloudWatch metrics and alarms.

### 📖 Resources
- [Video on Launching an EC2 Instance by RejiCodes](https://www.youtube.com/@RejiCodes)
- [Video on Auto Scaling & Load Balancer by RejiCodes](https://www.youtube.com/@RejiCodes)

---

## Project 4: Set Up a Relational Database in Amazon RDS and Connect to a Web App

**🎯 Objective**: Deploy and manage a relational database using Amazon RDS, and connect it to a web application.

### 🔍 Overview
- **Services Used**: Amazon RDS (MySQL or PostgreSQL), Amazon EC2 (for the application server)
- **Skills Learned**: Database creation, RDS management, connecting applications to RDS

### 📌 Steps
1. **Create an RDS Instance** (MySQL or PostgreSQL) and configure security groups for access.
2. **Configure the Database** with basic schemas and tables.
3. **Launch an EC2 Instance** to host your web application.
4. **Connect the Application** to the RDS database using the connection string.

### 📖 Resources
- [Video on Setting Up RDS by RejiCodes](https://www.youtube.com/@RejiCodes)
- [Video on RDS Database Connection by RejiCodes](https://www.youtube.com/@RejiCodes)

---

## Project 5: Implement Logging and Monitoring with CloudWatch and CloudTrail

**🎯 Objective**: Set up CloudWatch and CloudTrail to monitor and log activities across your AWS account.

### 🔍 Overview
- **Services Used**: Amazon CloudWatch, AWS CloudTrail
- **Skills Learned**: Monitoring metrics, creating alarms, setting up logging, understanding audit trails

### 📌 Steps
1. **Enable CloudTrail** to log API requests and events across AWS services.
2. **Configure CloudWatch Alarms** for metrics on EC2 instances and RDS databases.
3. **Set Up Log Streams** in CloudWatch Logs to store application logs.
4. **Analyze CloudWatch Logs** to monitor application and system performance.

### 📖 Resources
- [CloudWatch Monitoring - AWS Docs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
- [CloudTrail Logging - AWS Docs](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
- [Video Tutorial on AWS Monitoring](https://www.youtube.com/watch?v=hD-Q6Qv1NeA)

---

### 🌟 Wrap-Up

These projects offer a structured approach to learning AWS, covering:
- **Storage**
- **Compute**
- **Networking**
- **Serverless Architecture**
- **Databases**
- **Monitoring & Logging**

This foundation will prepare you for more advanced AWS challenges!

---

