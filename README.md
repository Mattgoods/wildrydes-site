# Wild Rydes Unicorn Ride-Sharing Application 🦄🚗

Welcome to the **Wild Rydes Unicorn Ride-Sharing Application**, a full-stack project designed for serverless deployment on AWS, inspired by the popular Uber model but with a magical twist—unicorns! This project showcases my skills in leveraging multiple AWS services to build scalable, modern applications.

## 📋 Project Overview

The Wild Rydes Unicorn Ride-Sharing Application allows users to:
- Register and log in securely.
- Request a "unicorn ride" by clicking on a map location.
- Track their unicorn's journey as it "arrives" at their location.

The project incorporates key AWS services to handle user management, serverless computing, storage, and CI/CD integration, making it an ideal example of cloud application deployment and microservice architecture.

## 🌐 Live Demo
When fully deployed, the application generates a public URL for real-time access and sharing.

## ⚙️ Technologies & AWS Services Used

This project uses a range of AWS services, creating a robust, secure, and highly scalable application infrastructure:

- **Amazon Amplify**: Frontend hosting with CI/CD integration.
- **Amazon Cognito**: User authentication and account management.
- **AWS Lambda**: Serverless backend for managing ride requests.
- **Amazon DynamoDB**: NoSQL database for storing ride information.
- **Amazon API Gateway**: REST API setup to trigger Lambda functions from the frontend.
- **GitHub**: Source control and CI/CD integration with Amplify.

## 🚀 Deployment and CI/CD

The application is designed for quick and efficient deployment, thanks to the CI/CD pipeline through AWS Amplify. Whenever updates are made to the codebase on GitHub, the Amplify service automatically deploys the latest changes, ensuring the application stays up-to-date.

## 🔒 Security and Authentication

User authentication is powered by Amazon Cognito, which ensures secure, scalable user management. The application also uses secure token-based authentication through API Gateway, giving users access to their ride-sharing account while keeping data protected.

## 📑 Getting Started

To deploy this application, follow these steps:

1. **Clone the Repository**:
   Clone this repository into your GitHub account and create a new repo using the template.

2. **Set Up AWS Services**:
   - Create a new Amazon Cognito user pool for secure user management.
   - Set up a DynamoDB table named `Rides` to store ride request data.
   - Deploy Lambda functions to handle ride requests and data processing.
   - Configure Amazon API Gateway to handle client requests and integrate with Lambda.

3. **Connect Amplify with GitHub**:
   Connect your Amplify app to this GitHub repository to set up continuous deployment.

4. **Deploy**:
   Amplify will handle the rest! It will pull the code from GitHub, deploy the backend resources, and host the frontend.

5. **Test the App**:
   Open the Amplify-hosted URL to see the application live. Register as a new user and request a unicorn to test functionality.

## 🧩 Key Components

- **Frontend**: Built with HTML and JavaScript, hosted on Amazon Amplify, and dynamically updated with Amplify’s CI/CD pipeline.
- **Backend**: Serverless Lambda functions perform the core logic for ride requests, selecting unicorns, and communicating with DynamoDB.
- **Data Storage**: Amazon DynamoDB stores ride information securely.
- **API**: API Gateway creates a RESTful API to interact with the Lambda backend and user data in DynamoDB.

## 🗑️ Cleanup (To Avoid Charges)

1. **Delete the Amplify App**.
2. **Remove Cognito User Pool**.
3. **Delete Lambda Functions and DynamoDB Table**.
4. **Clear API Gateway**.
5. **Remove CloudWatch Logs**.

## 📧 Contact

If you have any questions about the project, feel free to reach out through GitHub. Thank you for checking out this project, and I hope it showcases my ability to develop and deploy cloud-based applications with AWS!
