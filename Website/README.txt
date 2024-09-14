# Cloud Resume Challenge

## Overview

This repository contains my implementation of the **Cloud Resume Challenge** created by [Mr. Forrest](https://cloudresumechallenge.dev/docs/contribute/). The challenge aims to build a cloud-based resume using various cloud services and technologies. The goal is to showcase skills in cloud computing, web development, and infrastructure as code.

## Project Features

- **Host a static resume** on a cloud platform (AWS S3).
- **Use a custom domain** for the resume ([Ikoh Sylva](http://ikohsylva.net.ng)).
- **Implement a contact form** that captures user submissions and sends emails using AWS services.
- **Deploy serverless functions** to handle backend operations (AWS Lambda).
- **Store incoming messages** in a database (DynamoDB).
- **Create a CI/CD pipeline** for automated deployments.

## Technologies Used

- **AWS Services**:
  - Amazon S3 (for static website hosting)
  - AWS Lambda (for serverless functions)
  - Amazon API Gateway (for exposing the Lambda function)
  - Amazon DynamoDB (for visitors count)
  - Amazon Route 53 (for DNS management)
  - AWS IAM (for user permissions and roles)

- **Infrastructure as Code**:
  - Terraform (for deploying infrastructure)

- **Frontend Technologies**:
  - HTML
  - CSS
  - JavaScript

- **Deployment Tools**:
  - GitHub Actions (for CI/CD)

## Getting Started

To view the deployed resume, visit: [Ikoh Sylva](http://ikohsylva.net.ng)

### Prerequisites

- An AWS account
- Basic knowledge of HTML, CSS, and JavaScript
- Familiarity with AWS services and cloud concepts

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
Special thanks to [Mr. Forrest](https://cloudresumechallenge.dev/docs/contribute/) for the inspiration and guidance throughout this challenge.
Thanks to the AWS community for their numerous resources and support.
