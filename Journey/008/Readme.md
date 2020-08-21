![placeholder image](awsLambda.png)

# Day8 of My Severless Journey

## Introduction

A simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet.

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.


[Tweet](https://twitter.com/martynzYoung/status/1296837310798016515)
