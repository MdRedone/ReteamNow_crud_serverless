# ReteamNow_crud_serverless

Here is the list of AWS resources that the project template creates:

✔️ AWS Lambda

✔️ Amazon DynamoDB

✔️ Amazon API Gateway

✔️ AWS IAM

✔️ AWS Cloudformation

✔️ Amazon S3 (that is where your CloudFormation template will be stored)

1️⃣ The request which includes all necessary information is sent to Amazon API Gateway restful service.

2️⃣ API Gateway transfers the collected user information to a Lambda function.

3️⃣ AWS Lambda function executes event-based logic calling DynamoDB database.

4️⃣ DynamoDB provides a persistence layer where data can be stored/retrieved by the API's Lambda function.


![High level overview of microservice architecture](https://user-images.githubusercontent.com/106739132/199459978-6e7bd1e4-5696-4dc0-a3d9-8e0d1eb19777.jpg)

