# AWS Resume 

Check it out here:
 S3 Website URL: http://resumesitetos3.s3-website-us-east-1.amazonaws.com/
 CloudFront URL: https://d1p0gz8ox3l41q.cloudfront.net
This project demonstrates building a resume website hosted on AWS with a visitor counter.

## Features

- Static resume site hosted on Amazon S3
- Visitor counter implemented using:
  - API Gateway
  - AWS Lambda
  - DynamoDB
- Fronted with CloudFront CDN and HTTPS enabled

## Deployment

- The website is served from an S3 bucket configured for static website hosting.
- API Gateway exposes the visitor counter Lambda function.
- CloudFront distribution caches content globally and serves with SSL.

## How to run

1. Upload `index.html` and assets to your S3 bucket.
2. Deploy the visitor counter Lambda and configure API Gateway.
3. Set up CloudFront distribution pointing to your S3 bucket.
4. Access your resume site via the CloudFront URL.

