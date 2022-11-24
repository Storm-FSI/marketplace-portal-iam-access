# AWS Marketplace Portal IAM Access Solution

Manage Marketplace portal listings using an IAM role deployed by this CFT

# Description
This template create a trust relationship between an AWS account where you manage your AWS Marketplace Subscriptions (Account A) and another "jump account" (Account B).

After deployment you can access the Account A by switch role from the Account B.

# Deployment

Click to deploy [Quick Create Stack](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=eu-central-1#/stacks/quickcreate?templateUrl=https%3A%2F%2Fstormfsi-solutions.s3.amazonaws.com%2F/marketplace-portal-iam-access/marketplace-management-FSI-template.json&stackName=MarketPlacePortalRole&param_AWSRegion=eu-central-1) in your Marketplace Account

