# Static Website Hosting on AWS S3 & CloudFront

### 🔗 Live Website  
**CloudFront URL:** https://dfqgubps2yve4.cloudfront.net/

---

## 📌 Project Overview

In this project, I deployed a static website using **Amazon S3** and **Amazon CloudFront**. Since static websites only require HTML, CSS, and JavaScript files with no server-side processing, the cloud is an ideal place to host them.

My project focuses on two main objectives:

1. Hosting a static website on an S3 bucket  
2. Accessing the cached website pages using CloudFront's content delivery network (CDN), which provides low latency and high transfer speeds

Static website hosting requires a **public S3 bucket**, but CloudFront can work with both public and private buckets.

---

## 🚀 What I Implemented

Here are the steps I followed to deploy my website:

1. **Created a public S3 bucket**  
   - Uploaded all website files including HTML, CSS, JS, and images.

2. **Configured the S3 bucket for static website hosting**  
   - Set the index and error document.  
   - Added necessary IAM policies to secure the bucket.

3. **Set up CloudFront for content delivery**  
   - Connected CloudFront to my S3 bucket.  
   - Enabled caching for faster loading across global edge locations.

4. **Accessed the website through CloudFront**  
   - Used the CloudFront endpoint to load the hosted website.

---

## 📦 Prerequisites

Before starting the project, I downloaded and unzipped the **student-ready starter code** provided by the instructor.

---

## 🧩 Topics Covered

- Creating an S3 bucket  
- Configuring S3 for static website hosting  
- Applying IAM policies for security  
- Distributing a website via CloudFront  
- Accessing the final website through the CloudFront URL  

---

## 🛠️ Technologies Used

- **Amazon S3**  
- **Amazon CloudFront**  
- **AWS IAM**  
- **HTML, CSS, JavaScript**

---


## 🌐 Final Output

My static website is successfully deployed and globally accessible using CloudFront.

👉 **Live Site:** https://dfqgubps2yve4.cloudfront.net/


