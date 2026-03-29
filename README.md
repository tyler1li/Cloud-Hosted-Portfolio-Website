# Cloud Portfolio Website

This project is a cloud-hosted portfolio website built and deployed on AWS, designed to showcase my projects and hands-on experience in cloud and security.

The site is hosted at: tylerinthecloud.com

---

## Technologies Used

-Amazon S3 – Static website hosting

-Amazon CloudFront – CDN for global content delivery and HTTPS

-Amazon Route 53 – Domain registration and DNS management

-AWS Certificate Manager (ACM) – SSL/TLS certificate provisioning

-HTML / CSS / JavaScript – Front-end customization

-Formspree – Contact form email handling


---

## WHAT WAS DONE


-Architected and deployed a serverless static website using AWS core services

-Configured Amazon S3 for static hosting with secure bucket policies

-Implemented CloudFront distribution to enable HTTPS and improve performance via edge caching

-Integrated AWS Certificate Manager (ACM) for secure SSL/TLS encryption

-Configured Route 53 DNS records to route traffic from a custom domain to CloudFront

-Applied least-privilege access controls using private S3 buckets and Origin Access Control (OAC)

-Customized a front-end template using HTML/CSS/JavaScript to create a professional portfolio

-Integrated Formspree for secure client-side contact form submissions

-Added a downloadable resume functionality for improved recruiter accessibility



---

## What I Learned

-How to design and deploy a scalable, serverless web architecture on AWS

-Differences between direct S3 hosting vs CloudFront distribution

-DNS routing concepts and troubleshooting with Route 53

-SSL/TLS certificate validation and HTTPS configuration using ACM

-Importance of securing S3 origins and preventing public access

-Debugging real-world issues such as:
404 errors (NoSuchKey) from incorrect object paths

DNS propagation delays

CloudFront caching and invalidation behavior

---

## Notes

- Focus was placed on security, performance, and real-world deployment practices rather than just basic functionality
  
-Future improvements may include:

  Implementing Infrastructure as Code (IaC) using tools like AWS CloudFormation or Terraform to automate provisioning of S3, CloudFront, Route 53, and ACM resources
  
  Adding backend functionality using AWS Lambda and API Gateway
  
  Implementing authentication/authorization with Amazon Cognito
  
  Enhancing security with logging and monitoring (e.g., CloudTrail, WAF)

---
