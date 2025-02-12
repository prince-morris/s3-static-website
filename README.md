# Static Website Hosting with AWS S3 and CloudFront

This repository contains a quick overview of hosting a scalable, secure, and highly available static website using AWS services.

## Architecture Overview
![dark](https://github.com/user-attachments/assets/0e97e1f7-96d8-47d4-9a1f-b8326ce4ef34)


### Key Components
- **Amazon S3**: Stores static website files like HTML, CSS, and JavaScript.
- **Amazon CloudFront**: Delivers content globally with low latency.
- **Origin Access Control (OAC)**: Ensures secure access to the S3 bucket.

## Quick Overview
1. **Create an S3 Bucket**: Store your static files and keep public access blocked.
2. **Set Up CloudFront**: Configure it to use the S3 bucket as the origin and enable OAC.
3. **Test Your Site**: Deploy the CloudFront distribution and access the website through the distribution URL.

## Learn More
For a detailed step-by-step guide, visit the full project documentation on [Medium](https://medium.com/@morrisaddu/building-a-scalable-static-website-with-amazon-s3-and-cloudfront-a-step-by-step-guide-0a5507daf21f).

