# AWS GenAI Restaurant Onboarding Assistant

A web application that streamlines restaurant onboarding by enabling owners to upload menus for AI-driven product suggestions, securely storing data in DynamoDB via API Gateway, and delivering results through a GraphQL interface.

## Features
- **User Authentication**: Secure sign-in with AWS Cognito.
- **Menu Upload**: Upload `.docx` menus to Amazon S3.
- **AI Processing**: Lambda function processes menus and generates suggestions (mock AI).
- **Data Storage**: Stores menu metadata and suggestions in DynamoDB via API Gateway.
- **GraphQL Queries**: Retrieve suggestions using AWS AppSync.
- **Future Scope**: Generate contracts based on suggestions.

## Tech Stack
- **Front-End**: React, AWS Amplify (Auth, Storage, API)
- **Back-End**: AWS Lambda, S3, DynamoDB, API Gateway, AppSync (GraphQL)
- **Authentication**: AWS Cognito User Pool

## Prerequisites
- Node.js (v18.x or higher)
- AWS CLI (configured with credentials)
- Amplify CLI (`npm install -g @aws-amplify/cli`)

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd onboarding-react
