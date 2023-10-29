# AWS Online Code Judger

Welcome to the AWS Online Code Judger repository! This project is an online code judging system designed to execute and evaluate code in various programming languages on the Amazon Web Services (AWS) platform. This README provides essential information for you to understand, set up, and run the project.

## Contributors

We would like to thank the following contributors for their valuable contributions to this project:

- [Contributor Name 1](https://github.com/Gxaite)
- [Contributor Name 2](https://github.com/rafaelcarvalhoj)

## Overview

The AWS Online Code Judger is an application that allows users to submit their source code and receive execution and evaluation results. The platform is highly scalable and can handle multiple programming languages, providing detailed feedback to users.

## Features

- **Code Submission**: Users can submit their code to be executed within the system.
- **Secure Execution**: Code execution is isolated and secure to prevent unwanted impacts on the environment.
- **Code Evaluation**: Codes are evaluated based on specific criteria, such as correctness, efficiency, etc.
- **Detailed Results**: Users receive detailed results about the execution of their code.
- **Multiple Language Support**: The system is compatible with several programming languages.

## Prerequisites

Before setting up the AWS Online Code Judger, make sure you have the following prerequisites:

- An AWS account.
- Basic knowledge of AWS Lambda, AWS API Gateway, AWS S3, and AWS DynamoDB.

## Configuration

1. **Create AWS Resources**:
   - Create a Lambda function for executing codes.
   - Set up an API Gateway to expose the service.
   - Use an S3 bucket to store submitted codes.

2. **Configure the Database**:
   - Create a DynamoDB table to store information about code execution results.

3. **Set Environment Variables**:
   - Define the necessary environment variables in the Lambda, such as AWS credentials and database settings.

4. **Deploy the Code**:
   - Deploy the source code from this repository to Lambda.

5. **Configure Access Policies**:
   - Ensure that access policies are correctly configured to ensure security.

6. **Testing**:
   - Test the system with sample codes to ensure everything is working as expected.

## Usage

Users can access the AWS Online Code Judger through the API interface. They can submit their code and receive feedback on execution and evaluation. Make sure to provide adequate documentation for end-users.

## Contribution

If you wish to contribute to the project, feel free to create issues or send pull requests. We are always open to improvements and new features.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute it in accordance with the terms of the license.

## Contact

If you have any questions or need assistance, please contact us at [your-email@example.com].

Thank you for using the AWS Online Code Judger! We hope this project proves to be useful for your application.

