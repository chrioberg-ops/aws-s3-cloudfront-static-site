# AWS S3 + CloudFront Static Website

A static website hosted on Amazon S3 and delivered globally using CloudFront.

## Architecture

User -> CloudFront CDN -> Private S3 Bucket

## AWS Services Used

- Amazon S3
- Amazon CloudFront
- IAM Policies
- Origin Access Control (OAC)

## Features

- HTTPS enabled
- Private S3 bucket
- Global CDN delivery
- Secure access through CloudFront
- Static website hosting

## Project Structure

```bash
.
├── index.html
├── styles.css
└── README.md
```

## Deployment Steps

1. Create S3 bucket
2. Upload static files
3. Create CloudFront distribution
4. Configure Origin Access Control
5. Set default root object
6. Deploy globally

## What I Learned

- Hosting static websites on AWS
- Using CloudFront as a CDN
- Securing S3 buckets
- Configuring HTTPS delivery
- Basic AWS networking and permissions
