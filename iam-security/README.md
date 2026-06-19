# Cloud Security with AWS IAM

## Overview
Used AWS Identity and Access Management (IAM) to control access to 
AWS resources as part of the Nextwork AWS Cloud Beginner series. 
Simulated onboarding a new intern by setting up permissions that 
allowed access to a development environment but not production.

## AWS Services Used
- AWS IAM
- Amazon EC2

## What I Did
- Launched two EC2 instances tagged for production and development environments
- Created an IAM policy to allow access to development instances only
- Created an AWS account alias for easier login access
- Created an IAM user group and attached the policy to it
- Created an IAM user and added them to the user group
- Tested the intern's access by verifying they could stop the development instance but were denied access to the production instance

## Key Concepts Learned
- What IAM is and how it controls authentication and authorization in AWS
- How IAM policies use JSON to define permissions
- How EC2 instance tags can be used to control access by environment
- The difference between IAM users, user groups, and policies
- How account aliases simplify the AWS console login URL

## Screenshots
<!-- Add your screenshots here -->

## Resources
- [Nextwork Project Guide](https://learn.nextwork.org/projects/aws-security-iam)
- [AWS IAM Documentation](https://docs.aws.amazon.com/iam/)
