# Pharmacy Management System

This project contains source code and supporting files for a serverless Pharmacy Management Application that you can deploy with SAM CLI

## Features

- APIs for Order Management 
- Bulk Bill Generator for Audit
- Patient Management System


## Tech

The programming language used is JAVA and the deployment stack is AWS.
- [API Gateway]
- [Lambda]
- [DynamoDB]
- [Simple Notification Service] - SNS
- [JAVA] - Programming Language
- [Cloudwatch] - For logs and alerts
- [Simple Storage Service] - S3
- [Cloud Formation] - for deployment

## Deploy the application

The Serverless Application Model Command Line Interface (SAM CLI) is an extension of the AWS CLI that adds functionality for building and testing Lambda applications. It uses Docker to run your functions in an Amazon Linux environment that matches Lambda. It can also emulate your application's build environment and API.

To use the SAM CLI, you need the following tools.

* SAM CLI - [Install the SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)
* Java11 - [Install the Java 11](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html)
* Maven - [Install Maven](https://maven.apache.org/install.html)
* Docker - [Install Docker community edition](https://hub.docker.com/search/?type=edition&offering=community)

To build and deploy your application for the first time, run the following in your shell:

```bash
sam build
sam deploy --guided
```

## Cleanup

To delete the sample application that you created, use the AWS CLI. Assuming you used your project name for the stack name, you can run the following:

```bash
aws cloudformation delete-stack --stack-name ordersapi
```

## License

**Free Software, Hell Yeah!**
