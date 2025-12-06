# Static Website Hosting on AWS (S3 + CloudFront)
i have deployed the static website on s3 and then use cloudfront 

## Features
- S3 website hosting
- CloudFront CDN
- HTTPS using ACM
- Fully serverless and scalable

## AWS Services Used
- Amazon S3
- CloudFront
- IAM



## How to Deploy
1. Create S3 bucket
2. Enable static hosting
3. Upload HTML/CSS/JS files
4. Make bucket public
5. Create CloudFront distribution


## Architecture
User → CloudFront → S3 → Website Files
