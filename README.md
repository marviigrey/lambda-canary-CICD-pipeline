We will be creating a CICD pipeeline to deploy a serverless microservice 
This microservice will run on AWS lambda functions in a canary deployment strategy. 
What does a canary deployment strategy mean? To put it straight,lets say we have a
version of our application already running on production and we want to introduce a new version
of our application to our users. We will only deploy the new version of that application to a subset
of users, which means not all of our users will get the new version. This strategy help to prevent
any harmful conditions of our application, it is used to test the safety of our application. with 
time, we start to expose the new version of the application to more of our users.

In this project we will be making use of:
1. AWS Lambda.
2. AWS CodeDeploy.
3. AWS CDK (Cloud Development Kit). This is a framework which is used to define infastructure as code
   and Provisioning it through AWS CloudFormation.
4. AWS CloudFormation (Stacks). AWS Cloud formation is an IaC tool used for provisioning AWS services.
   It enables you to create and manage AWS resources and entire cloud environments using templates
   
7.  A programming language: Can be python, Go, javascript,java etc.
8.  
