Scalable voting system using AWS

1.	Services Used:
The following cloud services are deployed to implement the scalable voting system using a serverless architecture:

•	Amazon S3: This service is used to host the front-end website.

 •	Amazon API Gateway: This service is used to route incoming requests to the appropriate AWS Lambda function.
 
•	AWS Lambda: This service is used to implement the business logic of the application, including reading and writing data to the database.

•	Amazon DynamoDB: This service is used to store the data of the voting system.

2.	Working of the Services:
The working of the services is as follows:

•	User visits the front-end website hosted on Amazon S3.

•	When the user votes, the request is passed through Amazon API Gateway to the appropriate AWS Lambda function.

•	The AWS Lambda function communicates with Amazon DynamoDB to read or write the required data.

•	After reading or writing the data, the AWS Lambda function returns a response string to Amazon API Gateway.
•	The result is reflected on the front-end website, so the user can see the change immediately.
