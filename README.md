This project demonstrates a fully serverless web application using AWS services like S3, DynamoDB, API Gateway, Lambda, CloudFront, and Route 53. The application securely stores and retrieves employee data in a scalable and cost-efficient manner.

Architecture Overview
DynamoDB: Stores employee data.
S3: Hosts the frontend (HTML, JS).
Lambda: Acts as the backend to process API requests.
API Gateway: Exposes Lambda functions as REST APIs.
CloudFront & ACM: Ensures secure and fast content delivery.
Route 53: Manages the custom domain.
Key Features
✅ Fully serverless architecture
✅ Scalable and cost-efficient
✅ Secure API access with IAM roles
✅ HTTPS-enabled via CloudFront and ACM

Deployment Steps
Create a DynamoDB table for storing employee data.
Deploy frontend assets to S3.
Set up Lambda functions to handle API requests.
Configure API Gateway to expose REST APIs.
Secure the application with CloudFront and ACM.
Set up a custom domain with Route 53.
This project showcases a practical serverless approach with AWS, eliminating the need for traditional server management. 🚀
