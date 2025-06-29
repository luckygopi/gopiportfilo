# gopiportfilo
This repository hosts the source code for my personal portfolio website, deployed on AWS.

Project Overview
This project demonstrates a robust and automated workflow for hosting a static website on Amazon Web Services (AWS). It leverages the following AWS services:

Amazon S3: For highly available and scalable storage of static website assets.

Amazon CloudFront: As a Content Delivery Network (CDN) to serve the website globally with low latency and enhanced security.

AWS CodePipeline: For continuous integration and continuous deployment (CI/CD), automating the deployment process from GitHub to S3.

CI/CD Workflow
The deployment pipeline is fully automated. Any changes pushed to the main branch of this GitHub repository will automatically trigger a CodePipeline workflow:

Source Stage: CodePipeline detects changes in this GitHub repository.

Deploy Stage: The updated website files are automatically deployed to the S3 bucket.

CloudFront Integration: CloudFront, configured to use the S3 bucket as its origin, serves the latest content globally.

This setup ensures that website updates are delivered quickly and efficiently without manual intervention.

Technologies Used
HTML5

CSS3

JavaScript (if applicable)

Amazon S3

Amazon CloudFront

AWS CodePipeline

GitHub
