# 3-Tier Architecture Serverless in AWS

This project demonstrates how to build a 3-Tier Serverless Web Application using AWS Cloud services.

The architecture separates the application into three layers:
- Frontend Tier
- Application Logic Tier
- Database Tier

This improves scalability, security, and maintainability.

## Features
- Serverless architecture
- Automatic scaling
- Low operational cost
- Fully managed AWS services
- Secure API communication

## Architecture Diagram
![3 Tier Serverless Architecture in AWS](architecture.png)

## Technologies Used
- Cloud Front
- S3
- API Gateway
- AWS Lambda 
- DynamoDB

## How to Run the Project
Follow these steps to run the project.

### Step 1: Clone the Repository

```bash
git clone https://github.com/Decsika-tech/3-Tier-Architecture-Serverless-in-AWS-Cloud.git
```
### Step 2: Upload Frontend to S3
1. Go to AWS Console and Open Amazon S3
2. Create a bucket
3. Upload the frontend files (HTML, JS)
4. Enable Static Website Hosting

### Step 3: Create DynamoDB Table
1. Open DynamoDB
2. Create a new table
3. Add a primary key (BookingID or UserID)

### Step 4: Create Lambda Function
1. Open AWS Lambda
2. Create a new function using Python
3. Add code to process API requests
4. Connect Lambda to DynamoDB

### Step 5: Create API Gateway
1. Open API Gateway
2. Create a REST API
3. Connect the API endpoint to the Lambda function
4. Deploy the API

### Step 6: Test the Application
1. Open the S3 website URL
2. Submit the form
3. Data will be stored in DynamoDB through Lambda

## Screenshot
![3 Tier Serverless Architecture in AWS](result.png)

## Contributing
Pull requests are welcome! If you find any issues, feel free to open an issue.
