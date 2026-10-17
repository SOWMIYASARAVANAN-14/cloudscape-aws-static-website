# CloudScape - AWS Static Website Hosting

CloudScape is a static website built with HTML and CSS and deployed on Amazon S3. Amazon CloudFront is used to distribute the website content and provide HTTPS access.

## Project Overview

This project demonstrates how to host a static website using AWS services and make it accessible from desktop and mobile devices.

## Technologies Used

- HTML
- CSS
- Amazon S3
- Amazon CloudFront
- HTTPS

## Architecture

```text
User (Laptop / Mobile)
        |
        v
Amazon CloudFront (HTTPS + Content Delivery)
        |
        v
Amazon S3 (Website Files)
```

## Features

- Static website built with HTML and CSS
- Website files stored in Amazon S3
- Amazon CloudFront distribution for content delivery
- HTTPS access through the CloudFront domain
- Tested on desktop and mobile devices

## Deployment Summary

1. Created an S3 bucket.
2. Uploaded the website files (`index.html` and `style.css`) to the bucket.
3. Enabled S3 static website hosting.
4. Configured bucket permissions for the initial S3 website endpoint.
5. Created a CloudFront distribution with the S3 bucket as its origin.
6. Configured `index.html` as the default root object.
7. Tested the CloudFront URL on desktop and mobile.

## Project Structure

```text
cloudscape-aws-static-website/
├── index.html
├── style.css
└── README.md
```

## Learning Outcomes

- Learned the basics of Amazon S3 static website hosting.
- Practiced configuring bucket policies and access permissions.
- Learned how Amazon CloudFront connects to an S3 origin.
- Tested HTTPS delivery using a CloudFront distribution.

## Notes

- Do not upload AWS access keys, secret keys, passwords, or other credentials to GitHub.
- Check the AWS Billing dashboard regularly, as charges may depend on account eligibility and usage.
- If the CloudFront domain changes, update the Live Demo URL above.

## Author

Sowmiya
