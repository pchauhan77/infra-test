# CloudFormation Project

## Overview

This project contains an AWS CloudFormation template that creates the infrastructure shown in the architecture diagram.

## Deploying the Stack

To deploy the stack, follow these steps:

1. Log in to your AWS Management Console.
2. Navigate to the CloudFormation service.
3. Click "Create stack" and select "Upload a template file".
4. Upload the `cloudformation-template.yaml` file and click "Next".
5. Follow the prompts to configure stack options, and then click "Create stack".

## Prerequisites

- AWS account with necessary permissions.
- An AMI ID for the EC2 instances (update the template with your specific AMI ID).

## Files

- `cloudformation-template.yaml`: The CloudFormation template for the infrastructure.