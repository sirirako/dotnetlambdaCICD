# Lab 2 - Deploy AWS Lambda with Azure DevOps (VSTS)
### Overview
In this lab, you will learn how to use VSTS to deploy AWS Lambda severless function.


### High-Level Instructions

1. Install VSTS AWS tool to your VSTS account.
2. In your AWS Account, create IAM user which will be used in VSTS account to integrate to your AWS Account.
3. Create Credential in VSTS.
4. Create AWS Lambda Project. Choose from the following options:
- Use Visual Studio to create a AWS Lambda Project then push it to VSTS git repo.
- Use .Net Core CLI to create a new project then push it to VSTS git repo.
- Clone a simple project and then push it to VSTS git repo.
5. In VSTS, create Build Pipeline which will build the Lambda Project and store in VSTS Artifact Location.
6. In VSTS, create Deploy Pipeline to deploy the Artifact to you AWS Account to create the Lambda function. 

# Detailed Instructions
[Deploy AWS Lambda with Azure DevOps (VSTS) - Detailed Instructions](./Lab-2-detail-steps.md)